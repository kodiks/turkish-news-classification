# Turkish News Classification
Turkish News Category Classification Tutorial

## Veri Kümesi

[Interpress Turkish News Category Dataset (270K - Lite Version)](https://huggingface.co/datasets/interpress_news_category_tr_lite)
 veri kümesi, 

İnterpress medya takip şirketi tarafından **2010–2017 yılları arasında** yazılı basın ve haber sitelerinden derlenen, **17 kategoride 273.601 adet haberden** oluşan Türkçe haber veri kümesidir. Veri kümesinin kolay ayrıştırılabilir ve daha az sınıflı olarak **10 kategoride ("kültürsanat", "ekonomi", "siyaset", "eğitim", "dünya", "spor", "teknoloji", "magazin", "sağlık", "gündem")** yeniden düzenlenerek "Lite" versiyonu oluşturulmuştur. 

Veri kümesinin ham haline de [buradan](https://huggingface.co/datasets/interpress_news_category_tr) ulaşabilirsiniz.


|                       |     Train     |     Test     | 
|:---------------------:|:-------------:|:------------:|
|                       |    218,880    |    54,721    |


## Çalışma Dosyaları 🖥️


### Google Colab


- [1-load_dataset_and_preprocess.ipynb](https://colab.research.google.com/github/kodiks/turkish-news-classification/blob/main/notebooks/load_dataset_and_preprocess.ipynb) - HuggingFace Datasets üzerinden veri kümesini indirme, veri kümesinin içeriğinin incelenmesi ve ön işlemlerin uygulanması işlemlerinden oluşan çalışma dosyası

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kodiks/turkish-news-classification/blob/main/notebooks/load_dataset_and_preprocess.ipynb)


- [2-feature_extraction.ipynb](https://colab.research.google.com/github/kodiks/turkish-news-classification/blob/main/notebooks/feature_extraction.ipynb) - TF-IDF kelime ve karakter vektörlerinin oluşturulması işlemlerini içeren çalışma dosyası

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kodiks/turkish-news-classification/blob/main/notebooks/feature_extraction.ipynb)
   

- [3-train.ipynb](https://colab.research.google.com/github/kodiks/turkish-news-classification/blob/main/notebooks/train.ipynb) - SVM eğitim modelin oluşturulması, eğitilmesi ve performansın değerlendrilmesi işlemlerinden oluşan çalışma dosyası

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kodiks/turkish-news-classification/blob/main/notebooks/train.ipynb)

- [4-prediction.ipynb](https://colab.research.google.com/github/kodiks/turkish-news-classification/blob/main/notebooks/prediction.ipynb) - Eğitilmiş model dosyası ile farklı haber metinleri ile test edilmesi işlemlerini içeren çalışma dosyası

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kodiks/turkish-news-classification/blob/main/notebooks/prediction.ipynb)