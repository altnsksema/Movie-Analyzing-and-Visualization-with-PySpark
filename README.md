🎬 Movie Analytics with PySpark

Bu proje, popüler film verileri üzerinde PySpark kullanarak veri analizi yapmayı ve Python kütüphaneleri ile görselleştirme yapmayı amaçlar. Kaggle'dan alınan bir film verisi kullanılarak en çok oy alan filmler, tür bazlı dağılım gibi analizler gerçekleştirilmiştir.

📂 Proje Yapısı

📁 movie-analytics
├── movies.csv              # Kullanılan veri seti
├── movie_analysis.ipynb    # PySpark + Görselleştirme kodları
└── README.md               # Proje açıklaması

🚀 Başlangıç

📥 1. Veri Setini İndirme

Kaggle'dan popüler filmler veri setini indir:🎬 Popüler Filmler Kaggle Linki

CSV dosyası -> (https://www.kaggle.com/datasets/rajansavaliya22/popular-movies-dataset)

⚙️ 2. Gereksinimleri Kurma

Colab veya Jupyter Notebook üzerinde çalıştırabilirsiniz.

PySpark ve diğer kütüphaneleri yükleyin:

pip install pyspark matplotlib seaborn

▶️ 3. Çalıştırma

Notebook’u açın ve hücreleri sırayla çalıştırın:

# PySpark kurulumu ve başlatma
from pyspark.sql import SparkSession
spark = SparkSession.builder.appName("MovieAnalytics").getOrCreate()

📊 Yapılan Analizler

✅ En çok oy alan 10 film:PySpark ile vote_count sütunu kullanılarak hesaplanmıştır.

✅ Film Türlerinin Dağılımı:genres sütunu parçalanarak tür bazlı analiz yapılmıştır.

✅ Görselleştirme:

Matplotlib & Seaborn ile görselleştirme yapılmıştır.

En çok oy alan 15 film grafiği:

![image](https://github.com/user-attachments/assets/4c535691-b987-4e85-b058-ffceb8860649)




🛠 Kullanılan Teknolojiler

Python 🐍

PySpark ⚡

Matplotlib & Seaborn 🎨

Colab

✍️ Katkıda Bulun

PR’lar ve öneriler her zaman kabul edilir! 🙌

📜 Lisans

MIT License

