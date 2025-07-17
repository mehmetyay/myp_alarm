# ⏰ C# Alarm Uygulaması

Bu proje, C# ve Windows Forms kullanılarak geliştirilmiş basit ama işlevsel bir masaüstü alarm uygulamasıdır. Uygulamanın amacı, kullanıcının belirlediği saate göre sesli uyarı vererek bir alarm sistemi oluşturmaktır. Eğitim ve kişisel gelişim amaçlı hazırlanmıştır.

## 🧩 Özellikler

- Saat ve dakika seçimi ComboBox ile yapılabilir
- “Alarm Kur” butonu ile alarm başlatılır
- Belirlenen saat geldiğinde proje klasöründeki `.mp3` dosyası çalar
- Media Player kontrolü ile ses dosyası çalıştırılır
- Temiz, sade ve geliştirilebilir kod yapısı

## 🖼️ Kullanım

1. Proje çalıştırıldığında saat ve dakika ComboBox'ları ile hedef zaman seçilir.
2. "Alarm Kur" butonuna basıldığında sistem saati arka planda kontrol edilmeye başlar.
3. Zaman geldiğinde uygulama klasöründe yer alan `alarm.mp3` dosyası otomatik olarak çalınır.

## 💡 Amaç

Bu proje, özellikle C# ile masaüstü uygulama geliştirmek isteyenler için sade ve anlaşılır bir örnek sunmayı hedeflemektedir. WinForms kontrolleri, Timer kullanımı, medya oynatıcı entegrasyonu gibi temel konular hakkında pratik sağlar.

## 🔧 Kullanılan Teknolojiler

- C# (.NET Framework)
- Windows Forms (WinForms)
- Windows Media Player (ActiveX bileşeni)

## 📌 Notlar

- Uygulama şu an için yalnızca yerel saat kontrolüyle çalışmaktadır. Geliştirilerek tekrar eden alarmlar, özel ses seçenekleri, alarm listesi gibi özellikler eklenebilir.
- `alarm.mp3` dosyasının proje klasöründe bulunması zorunludur. Farklı ses dosyalarıyla değiştirilebilir.

## 👨‍💻 Geliştirici

Bu proje **Mehmet Yay** tarafından geliştirilmiştir.  
Her türlü geri bildirim, katkı ve öneri memnuniyetle karşılanır.

## 📄 Lisans

Bu proje açık kaynaklıdır. Lisans detayları için [LICENSE](./LICENSE) dosyasına göz atabilirsiniz.
