# 🚗 Türkiye Trafik Sigortası Prim & Hasar Dengesi Analizi

## 📌 Proje Hakkında
Bu proje, Türkiye trafik sigortası sektörünün 2015-2024 yılları arasındaki
prim üretimi ve hasar ödemesi dengesini analiz etmektedir.
Veriler Türkiye Sigorta Birliği (TSB) yıllık istatistik bültenlerine dayanılarak oluşturulmuştur.

## 📊 Analizler ve Görselleştirmeler

### Yıllara Göre Prim vs Hasar Trendi
![Prim Hasar Trend](outputs/01_prim_hasar_trend.png)

### Araç Tipine Göre Hasar/Prim Oranı
![Araç Tipi Hasar](outputs/02_arac_tipi_hasar.png)

### İl Bazlı Risk Analizi
![İl Bazlı Hasar](outputs/03_il_bazli_hasar.png)

### Aylık Mevsimsellik Analizi
![Mevsimsellik](outputs/04_aylik_mevsimsellik.png)

### Korelasyon Matrisi
![Korelasyon](outputs/05_korelasyon_matrisi.png)

## 🛠️ Kullanılan Teknolojiler
- Python 3.12
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Jupyter Notebook

## 📁 Proje Yapısı

    turkiye-trafik-sigortasi-analizi/
    ├── data/                  # Ham veri
    ├── notebooks/             # Jupyter defterleri
    ├── outputs/               # Grafikler
    ├── requirements.txt
    └── README.md

## 🚀 Nasıl Çalıştırılır

    pip install -r requirements.txt
    jupyter notebook notebooks/01_veri_analizi.ipynb

## 🔍 Temel Bulgular
- Ortalama hasar/prim oranı **%86** olup sektör baskı altındadır
- Motosiklet en riskli araç tipi olarak öne çıkmaktadır
- Kış aylarında hasar oranı belirgin şekilde artmaktadır
- Prim geliri ile hasar ödemesi arasında güçlü korelasyon (0.99) bulunmaktadır

## 📬 İletişim
[LinkedIn](www.linkedin.com/in/elifcakir1705) | [GitHub](https://github.com/elifcakir1875)