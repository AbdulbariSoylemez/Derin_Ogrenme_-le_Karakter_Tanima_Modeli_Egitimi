# Derin_Ogrenme_-le_Karakter_Tanima_Modeli_Egitimi

###  İşaret Dili Tanıma CNN Modeli ile 


Bu proje, işaret dilini tanıyan bir Convolutional Neural Network (CNN) modeli içermektedir.

## Kullanım Kılavuzu

1. **Veri Kümesi Oluşturma:**
   - `Veri` sınıfını kullanarak işaret dilini içeren bir veri kümesi oluşturun.
   - Veri kümesini eğitim ve test alt kümelerine ayırın.

2. **Modeli Eğitme:**
   - `Net` sınıfını kullanarak CNN modelini oluşturun.
   - Modeli belirli parametrelerle eğitin ve sonuçları TensorBoard üzerinde gözlemleyin.

3. **TensorBoard Kullanımı:**
   - TensorBoard'u kullanarak modelin eğitim metriklerini ve parametrelerini gözlemleyin.
   - `tensorboard --logdir=runs` komutuyla TensorBoard'u başlatın.

4. **Modeli Kaydetme ve Yükleme:**
   - Eğitilmiş modeli `torch.save()` ile kaydedin ve `torch.load()` ile yükleyin.
   - Modelin ağırlıklarını ayrıca kaydedip yükleyebilirsiniz.

5. **Test ve Doğruluk Analizi:**
   - Eğitilmiş modeli kullanarak test veri kümesinde doğruluk analizi yapın.
   - Modelin genel doğruluğunu değerlendirin.

6. **TensorBoard Görselleştirmeleri:**
   - Modelin yapısını, parametrelerini, kayıp ve doğruluk grafiğini TensorBoard üzerinde inceleyin.

7. **Görüntü Tahminleri:**
   - Eğitilmiş modeli kullanarak test veri kümesinden rastgele birkaç görüntüde tahmin yapın ve sonuçları görselleştirin.

## Gereksinimler

- PyTorch
- Torchvision
- TensorBoard
- Matplotlib
- Pandas
- Scikit-image
- NumPy

