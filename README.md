# IR-remote-control

Bu proje, Arduino kullanarak IR (kızılötesi) uzaktan kumanda ile LED'leri kontrol eden basit bir sistemdir.

## Özellikler
- 4 adet LED'i uzaktan kumanda ile aç/kapat
- 5. tuşla tüm LED'leri kapat
- Seri monitörde kodları gösterir

## Gereksinimler
- Arduino Uno veya benzeri
- IR alıcı modülü (örneğin TSOP4838)
- 4 adet LED
- IR uzaktan kumanda

## Bağlantılar
- IR alıcı: Pin 2
- LED'ler: Pin 8, 9, 10, 11

## Kurulum
1. IRremote kütüphanesini Arduino IDE'ye yükleyin.
2. Kodu Arduino'ya yükleyin.
3. Sistemi test edin.

## Kullanım
Uzaktan kumandanızın 1-4 tuşları ile LED'leri kontrol edin, 5. tuşla hepsini kapatın.