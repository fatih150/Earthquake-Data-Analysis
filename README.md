https://www.kaggle.com/code/mehmetfatihtosun/notebookf660ecf8e9?scriptVersionId=209247968

# Earthquake Data Analysis

## Proje Özeti
Bu projede, Endonezya'da meydana gelen depremlerle ilgili veriyi analiz ettik. Veri seti, depremlerin tarihi, konumu, derinliği, büyüklüğü ve diğer parametreleri içermektedir. Amaç, verileri analiz etmek, eksik verileri tamamlamak, korelasyonları incelemek ve görselleştirme yaparak önemli trendleri ortaya çıkarmaktır.

## Veri Seti
Veri seti, Endonezya'da gerçekleşen depremleri içeren bir CSV dosyasıdır. Aşağıdaki sütunları içerir:
- **tgl**: Depremin tarihi
- **ot**: Depremin saati
- **lat**: Enlem
- **lon**: Boylam
- **depth**: Derinlik
- **mag**: Büyüklük
- **remark**: Depremin açıklamaları
- **strike1, dip1, rake1, strike2, dip2, rake2**: Depremin tektonik özellikleri

## Kullanılan Kütüphaneler
- **pandas**: Veri işleme ve analiz
- **numpy**: Sayısal hesaplamalar
- **matplotlib** ve **seaborn**: Veri görselleştirme
- **random**: Rastgele eksik veriler eklemek için

## Yapılan Analizler
1. **Eksik Veri Analizi**: Veri setindeki eksik veriler kontrol edildi ve rastgele eksik veriler eklendi.
2. **Veri Temizleme**: Eksik veriler ortalamalarla dolduruldu.
3. **Korelasyon Analizi**: Sayısal veriler arasındaki korelasyonları görselleştirmek için ısı haritası kullanıldı.
4. **Veri Görselleştirme**: Çeşitli grafikler ile veri setinin temel özellikleri ve trendleri görselleştirildi.

## Kullanım
Bu projeyi çalıştırmak için aşağıdaki kütüphanelerin kurulu olması gerekmektedir:
- pandas
- numpy
- matplotlib
- seaborn

### Başlangıç
Projeyi çalıştırmak için öncelikle gerekli kütüphaneleri yükleyin ve ardından `earthquake_analysis.ipynb` dosyasını çalıştırarak analizlere başlayabilirsiniz.

## Sonuçlar
Bu proje, Endonezya'daki depremler hakkında önemli bilgileri ortaya koyarak, deprem aktivitelerinin analizini kolaylaştırmayı hedefler. Korelasyon analizi ve görselleştirme, depremlerin çeşitli faktörlerle nasıl ilişkilendiğini anlamaya yardımcı olmaktadır.
