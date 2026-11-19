# Düzenli Ana Ekran — Android başlangıç projesi

Bu proje, Android için basit bir ana ekran (launcher) örneğidir.

## Neler yapar?
- Telefonunda başlatılabilir uygulamaları listeler.
- Uygulamaları isim ve Android'in uygulama kategorisi bilgisine göre yaklaşık olarak gruplar.
- Bir uygulama simgesine dokununca onu açar.
- Android'in varsayılan ana ekran seçimine gitmek için düğme sunar.

## Önemli sınırlar
- Bu bir başlangıç projesidir; mevcut ana ekranındaki ikonları taşımaz.
- Kategoriler otomatik tahmindir. Bazı uygulamalar "Diğer uygulamalar" altında kalabilir.
- Uygulamaları listelemek için yalnızca başlatılabilir uygulamalar sorgulanır.
- APK bu paketin içinde derlenmiş değildir.

## APK oluşturma
1. Bilgisayara Android Studio ve Android SDK 35 kur.
2. Bu klasörü Android Studio ile aç.
3. Gradle eşitlemesinin bitmesini bekle.
4. Build > Build Bundle(s) / APK(s) > Build APK(s) seç.
5. Oluşan APK'yı telefonuna aktar ve yükle.
6. Uygulamayı açıp "Varsayılan ana ekranı seç" düğmesine dokun; listeden "Düzenli Ana Ekran"ı seç.

Güvenlik için Android'in varsayılan ana ekran seçimini kendin onaylamalısın. İstediğin zaman Ayarlar'dan eski launcher'ına dönebilirsin.
