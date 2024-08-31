# iyzico Zaman Serisi Projesi

Bu proje, iyzico veri seti kullanılarak bir zaman serisi tahmin modeli oluşturmayı amaçlamaktadır.

## Kullanılan Kütüphaneler

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `lightgbm`
- `re`
- `warnings`

## Nasıl Çalıştırılır

1. **Depoyu klonlayın:**
   ```bash
   git clone https://github.com/ibrahmkocaa/iyzico_forecasting
   ```
2. **Gerekli kütüphaneleri yükleyin:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Jupyter Notebook dosyasını açın ve hücreleri çalıştırın:**
   ```bash
   jupyter notebook iyzico_forecasting.ipynb
   ```

## Dosyalar

- `iyzico_forecasting.ipynb`: Veri yükleme, ön işleme ve model eğitimi için ana notebook dosyası.
- `requirements.txt`: Gerekli kütüphanelerin listesi.

## Proje Adımları

1. **Gerekli kütüphanelerin import edilmesi**: Notebook, veri manipülasyonu, görselleştirme ve model eğitimi için gerekli kütüphaneleri (pandas, numpy, matplotlib, seaborn, LightGBM) içe aktararak başlar.
   
2. **Veri Yükleme**: Veriler, `iyzico_data.csv` adlı bir CSV dosyasından pandas DataFrame'e yüklenir.

3. **Veri Ön İşleme**: Notebook, özel karakterleri kaldırmak için düzenli ifadeler kullanarak sütun adlarının yeniden adlandırılması ve veri setinin model eğitimi için hazırlanması adımlarını içerir.

4. **Model Eğitimi**: Projede, tahmin modeli eğitimi için popüler bir gradyan artırma algoritması olan LightGBM kullanılır. Hiperparametreler tanımlanır ve model, belirli metrikler ve parametrelerle eğitilir.

5. **Özellik Önem Derecesi Grafikleri**: Notebook, LightGBM modelinin kullandığı özelliklerin önem derecelerini göstermek için grafikler oluşturup gösteren fonksiyonlar içerir.

## Açıklama

Bu proje, LightGBM algoritmasını kullanarak bir tahmin modeli oluşturma sürecini detaylandırmaktadır. Model, geçmiş işlem verileri üzerinde eğitilir ve notebook, modelin karar verme sürecine dair içgörüler sağlamak amacıyla özellik önem derecelerinin görselleştirilmesini içerir.

## Katkıda Bulunma

Bu projeye katkıda bulunmak isterseniz, lütfen önce ne tür bir değişiklik yapmak istediğinizi belirtmek için bir issue açın. Daha sonra bir pull request gönderebilirsiniz.
