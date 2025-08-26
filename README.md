Bir Python Flask uygulaması yaz.
- Uygulama "YKS KAYNAK ÖNERİSİ.xlsx" dosyasındaki tek sayfa ("BRANŞ DNM.") tablosunu okusun.
- Bu tabloda her branş ve net aralığına göre renk seviyeleri (⚪ GRİ, 🟢 YEŞİL, 🟡 SARI, 🟠 TURUNCU, 🔴 KIRMIZI) ve kaynak önerileri var.
- Backend Excel’i okuyarak şu yapıyı oluşturacak:
   { "branş": "TYT Matematik", "aralık": "30-60", "seviye": "YEŞİL", "öneriler": [ "Kaynak 1", "Kaynak 2", ... ] }
- Kullanıcı arayüzünde bir form olsun:
   1) Branş seçimi (Excel’deki tüm branşlar dropdown olarak gelsin),
   2) Net ortalaması girişi.
- Kullanıcı formu gönderdiğinde:
   - Flask backend Excel’den doğru satırı bulsun,
   - O net aralığına denk gelen **birden fazla kaynağı** HTML sayfasında liste halinde göstersin.
- Kod tam çalışır olsun:
   - Gerekli import’ları ekle,
   - Flask app.run ile uygulamayı başlat,
   - templates klasöründe index.html (form) ve result.html (öneriler) dosyalarını üret.
