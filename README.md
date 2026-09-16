# E-Commerce Customer Behavior & Sales Analysis

## Project Overview

Bu proje, bir e-ticaret sitesine ait veri seti üzerinden müşteri davranışlarının ve satışların incelendiği bir veri analizi projesidir. Analizler; ürün kategorisi, şehir, müşteri durumu, indirim, zaman ve cihaz türü gibi farklı değişkenler üzerinden gerçekleştirilmiştir.

Projede Python programlama dili ile birlikte Pandas, NumPy ve Matplotlib kütüphaneleri kullanılmıştır.

## Dataset

Veri setinde 5.000 satır ve 18 sütun bulunmaktadır. Veri seti, bir e-ticaret sitesindeki müşteri davranışlarını ve satış verilerini temsil etmektedir. Veri seti üzerinden müşteri davranışları ve satışlar farklı değişkenlere göre analiz edilmiştir. Özellikle ürün kategorisi, şehir, toplam satış tutarı, tarih ve müşteri durumu gibi değişkenler üzerinde durulmuştur.

## Technologies

- Python: Veri analizi için kullanılan programlama dili.
- Pandas: Veri setini inceleme, düzenleme ve analiz etme işlemlerinde kullanılmıştır.
- NumPy: Sayısal işlemler ve veri üzerinde hesaplamalar yapmak için kullanılmıştır.
- Matplotlib: Analiz sonuçlarını görselleştirerek verilerin daha kolay anlaşılmasını sağlamak için kullanılmıştır.
- Jupyter Notebook: Kod, analiz ve sonuçların düzenli bir şekilde bir arada tutulması için kullanılmıştır.

## Analysis

- Product Category Analysis: Electronics kategorisinin toplam satış ve ortalama sipariş tutarında diğer kategorilere göre daha yüksek olduğu görülmüştür.
- City Analysis: İstanbul, en yüksek toplam satış tutarına ve sipariş sayısına sahip şehirdir.
- Customer Analysis: Geri dönen müşterilerin sayısı daha fazla olsa da iki müşteri grubunun ortalama sipariş tutarları arasında belirgin bir fark bulunmamaktadır.
- Discount & Sales Analysis: İndirim miktarı ile toplam satış tutarı arasında pozitif yönlü ancak güçlü olmayan bir ilişki bulunmuştur.
- Time-Based Analysis: Aylık satışların düzenli bir artış veya azalış yerine inişli çıkışlı bir seyir izlediği görülmüştür.
- Device Analysis: Mobile cihazlarda ortalama sipariş tutarı en yüksek, Tablet cihazlarda ise en düşük bulunmuştur.

## Visualizations

Analiz sonuçlarının daha anlaşılır hale getirilmesi amacıyla Matplotlib kullanılarak farklı grafikler oluşturulmuştur.

- Ürün kategorilerine göre toplam satış
- Şehirlere göre toplam satış
- Yeni ve geri dönen müşterilerin ortalama sipariş tutarı
- İndirim miktarı ve toplam satış tutarı ilişkisi
- Aylık satış tutarları
- Cihaz türlerine göre ortalama sipariş tutarı

## Project Structure

ecommerce-sales-analysis/

├── data/

│ └── sales.csv

├── notebooks/

│ └── analysis.ipynb

└── README.md

## How to Run

1. Projeyi bilgisayarınıza indirin veya GitHub üzerinden klonlayın.
2. `notebooks/analysis.ipynb` dosyasını Jupyter Notebook veya VS Code ile açın.
3. Gerekli Python kütüphanelerinin yüklü olduğundan emin olun.
4. Notebook içerisindeki hücreleri sırasıyla çalıştırın.

## Dataset Source

Bu projede kullanılan veri seti Kaggle üzerinden alınmıştır.

**Dataset:** E-Commerce Customer Behavior & Sales Analysis -TR
**Author:** UmutUygurr
**Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/umuttuygurr/e-commerce-customer-behavior-and-sales-analysis-tr)

Veri seti CC0 (Public Domain) lisansı altında paylaşılmıştır.
