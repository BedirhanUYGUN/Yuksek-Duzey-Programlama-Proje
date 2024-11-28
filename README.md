# Yüksek Düzey Programlama Proje 

Bedirhan UYGUN - 202013171014

**Proje** **Adı**: Tabak Durumu Sınıflandırması (Cleaned vs Dirty)

**Proje** **Rapor** **Linki**: https://github.com/BedirhanUYGUN/Yuksek-Duzey-Programlama-Proje/blob/main/Rapor.pdf

**Kaggle** **Linki**: https://www.kaggle.com/code/bedirhanuygun/cleaned-and-dirty-pytorch-traind-and-optimizing 



Aşağıda, projeniz için önerilen bir README dosyası bulunmaktadır:

---

## Proje Özeti

Bu çalışmada, tabakların temiz veya kirli olduğunu otomatik olarak tanıyabilen bir görüntü sınıflandırma modeli geliştirilmiştir. Modelin temelinde, görsel verilerden anlamlı özellikler çıkarabilen bir derin öğrenme yöntemi olan Convolutional Neural Network (CNN) bulunmaktadır. Veri seti, piksellerin normalizasyonu ve yeniden boyutlandırılması ile model için uygun hale getirilmiştir. Model eğitimi sırasında Adam optimizasyon algoritması ve Cross-Entropy kayıp fonksiyonu kullanılmıştır. Sonuç olarak, eğitim ve test veri setlerinde yüksek doğruluk oranları elde edilmiştir.

## Kullanılan Teknolojiler

- Python
- PyTorch
- OpenCV
- NumPy
- Pandas

## Dosya Yapısı

- `cleaned-and-dirty-pytorch-traind-and-optimizing.ipynb`: Modelin eğitimi ve optimizasyonunu içeren Jupyter Notebook dosyası.
- `Rapor.pdf`: Proje raporunu içeren PDF dosyası.

## Nasıl Çalıştırılır

1. Bu depoyu yerel makinenize klonlayın:

   ```bash
   git clone https://github.com/BedirhanUYGUN/Yuksek-Duzey-Programlama-Proje.git
   ```

2. Gerekli Python paketlerini yükleyin:

   ```bash
   pip install -r requirements.txt
   ```

3. Jupyter Notebook'u başlatın ve `cleaned-and-dirty-pytorch-traind-and-optimizing.ipynb` dosyasını açın:

   ```bash
   jupyter notebook
   ```

4. Notebook'taki hücreleri sırayla çalıştırarak modeli eğitin ve sonuçları gözlemleyin.

