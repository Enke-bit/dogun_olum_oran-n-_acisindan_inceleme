# Ölüm Oranı ve Toplum Üzerindeki Etkisi Projesi

Bu proje, ölüm oranlarının toplum üzerindeki etkilerini analiz etmek ve tahminler yapmak amacıyla geliştirilmiştir. Proje, veri analizi, görselleştirme ve makine öğrenimi modeli kurma aşamalarını kapsamaktadır.

## İçindekiler

- [Proje Hakkında](#proje-hakkında)
- [Veri Seti](#veri-seti)
- [Analiz Adımları](#analiz-adımları)
- [Model Kurma](#model-kurma)
- [Sonuçlar](#sonuçlar)
- [Kullanım](#kullanım)
- [Yazarlar](#yazarlar)
- [Lisans](#lisans)

## Proje Hakkında

Bu proje, ölüm oranları verilerini kullanarak toplumsal etkileri incelemeyi amaçlar. Veriler analiz edilip görselleştirilmiş ve bir LSTM (Long Short-Term Memory) model kullanılarak tahminler yapılmıştır.

## Veri Seti

Veri seti, çeşitli ülkeler ve yıllar bazında ölüm oranları ve diğer toplumsal göstergeleri içermektedir. Veri setinin bazı özellikleri şunlardır:
- `Country Name`: Ülke adı
- `Years`: Yıl
- `Death Rate`: Ölüm oranı
- Diğer özellikler: Fertility Rate, GDP Growth, HDI, vb.

## Analiz Adımları

1. **Veriye İlk Temas**
   - Verinin ilk beş ve son beş satırını yazdırma.
   - Verinin indekslerini ve yapısını inceleme.
   - Boş veri olup olmadığını kontrol etme.
   - Ülkelerin isimlerini görme.

2. **Veri Görselleştirme**
   - Kıtalar bazında ölüm oranlarını görselleştirme.
   - Türkiye'ye özgü verileri inceleme.
   - Verinin son tarihindeki ülkelerin değerlerini görselleştirme.

3. **Model Kurma**
   - LSTM modeli kurma ve eğitme.
   - Tahminler yapma ve sonuçları değerlendirme.
   - Tahmin sonuçlarını görselleştirme.

## Model Kurma

Proje, ölçeklenmiş özellikler ve hedef değişkenler kullanarak bir LSTM modeli eğitir. Modelin doğruluğu, Mean Squared Error (MSE) metriği ile değerlendirilmiştir. Sonuç olarak, modelin MSE değeri 2.1974978531370075 olarak elde edilmiştir.

## Kullanım

1. Proje dosyalarını klonlayın veya indirin.
2. Gerekli kütüphaneleri yükleyin: `numpy`, `pandas`, `matplotlib`, `sklearn`, `tensorflow`.
3. Jupyter Notebook veya bir Python IDE kullanarak kodu çalıştırın.
4. Veri analizi ve model kurma adımlarını takip edin.

## Yazarlar

- [İbrahim Püsküllü] - Proje geliştiricisi

## Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Daha fazla bilgi için [Lisans Dosyasını](LICENSE) inceleyebilirsiniz.
