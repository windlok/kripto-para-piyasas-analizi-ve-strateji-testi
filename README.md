<img width="3600" height="1800" alt="bitcoin_fiyat_ve_hareketli_ortalamalar" src="https://github.com/user-attachments/assets/572a93b6-4960-4b3f-b63b-6a6d0bb9a322" /># Kripto Para Analizi

Bu proje, Bitcoin (BTC-USD) için temel zaman serisi analizleri ve görselleştirmeler yapar. Amaç: fiyat verilerini indirip hareketli ortalamalar gibi göstergelerle trendleri ve potansiyel sinyalleri incelemektir.

**Özellikler**
- **Veri Kaynağı:** Yahoo Finance (`yfinance` ile)
- **Göstergeler:** 50 ve 200 günlük Basit Hareketli Ortalama (SMA)
- **Görselleştirme:** Matplotlib ile zaman serisi grafikleri

**Kullanım**
- `main.ipynb` Bitcoin verisini indirir, `SMA_50` ve `SMA_200` hesaplar, grafiği çizer ve `bitcoin_fiyat_ve_hareketli_ortalamalar.png` olarak kaydeder.

**Örnek requirements.txt içeriği**
```
numpy
pandas
matplotlib
yfinance
jupyter
```

**Notlar**
- Yahoo Finance bağlantıları zaman zaman engellenebilir; alternatif veri kaynakları veya önbellek mekanizmaları eklemeyi düşünebilirsiniz.
<img width="3600" height="1800" alt="bitcoin_fiyat_ve_hareketli_ortalamalar" src="https://github.com/user-attachments/assets/15cb5db0-9b19-4c7c-bb9f-b50468be06ad" />

<img width="3600" height="1800" alt="bitcoin_fiyat_ve_hareketli_ortalamalar" src="bitcoin_fiyat_ve_hareketli_ortalamalar(20-50).png" />

<img width="3600" height="1800" alt="bitcoin_fiyat_ve_hareketli_ortalamalar" src="bitcoin_fiyat_ve_hareketli_ortalamalar.png" />
