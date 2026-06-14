Ders: YBS3259 - Makine Öğrenmesi Final Projesi
Öğrenci: Emir Özel
Numara: 2321223233

Proje Adı:
Spotify Popülerlik Sınıflandırma Projesi

GitHub Repository Linki:
https://github.com/buraksy/makine--grenmesi-son

Proje Özeti:
114.000 Spotify şarkısı için popülerlik (Düşük / Yüksek) sınıflandırması yapan bir makine öğrenmesi projesidir.
Ana notebook, veri analizi ve modelleme sürecini uçtan uca anlatan data storytelling formatındadır.

Ana Dosyalar:
- notebooks/Spotify_ML_Pipeline_Reorganized_v2.ipynb  → EDA + veri hazırlama + modelleme + değerlendirme
- app.py (veya app/ klasörü)                         → Random Forest sınıflandırıcı için Streamlit dashboard
- models/best_classifier_rf.pkl                      → Eğitilmiş sınıflandırma modeli
- requirements.txt                                   → Gerekli Python paketleri

Çalıştırma (Notebook):
1. python -m venv .venv
2. .venv\Scripts\activate      (Windows)
   source .venv/bin/activate   (Mac/Linux)
3. pip install -r requirements.txt
4. jupyter notebook notebooks/Spotify_ML_Pipeline_Reorganized_v2.ipynb

Çalıştırma (Streamlit Uygulaması):
1. Ortam aktifken:
   streamlit run app.py
