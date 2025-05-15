# HesapYonetimSistemi
# 💼 Hesap Yönetim Sistemi

Bu proje, PHP ve MySQL kullanılarak geliştirilmiş basit bir **Hesap Yönetim Sistemidir**. Sistem, kullanıcı kayıtlarını yönetmek, giriş yapmak, kullanıcıları listelemek, düzenlemek ve silmek gibi temel işlemleri gerçekleştirmek için tasarlanmıştır.

## 🚀 Özellikler

- 👤 Kullanıcı girişi (email & şifre)
- ➕ Yeni kullanıcı ekleme
- 📋 Kullanıcıları listeleme
- ✏️ Bilgi güncelleme
- ❌ Kullanıcı silme
- 🔐 Şifre gizleme (hash)

## 🛠️ Kullanılan Teknolojiler

- PHP (MySQLi)
- MySQL
- HTML + CSS

## 🧾 Veritabanı Yapısı

**Tablo Adı:** kullanicilar

| Sütun Adı       | Tür           | Açıklama                  |
|----------------|---------------|---------------------------|
| id             | INT (PK)      | Otomatik ID               |
| ad_soyad       | VARCHAR(100)  | Kullanıcının adı soyadı   |
| mail           | VARCHAR(100)  | E-posta adresi            |
| sifre          | VARCHAR(255)  | Şifre (MD5 veya SHA)      |
| personel_id    | INT           | Personel ID               |
| organizasyon_id| INT           | Organizasyon ID           |


//Proje Çıktıları Görsel olarak Proje İçinde Screenshot Klasörü İçerinde Paylaşılmıştır.


## 🚀 Kurulum Adımları

1. Bu repoyu klonlayın:
   ```bash
   git clone https://github.com/metehanunl/HesapYonetimSistemi.git
2.Veritabanınızı oluşturun ve gerekli tabloları ekleyin (örnek SQL dump dosyası database.sql olarak eklenmelidir).
3.config.php dosyasındaki veritabanı bağlantı bilgilerini kendi sunucunuza göre düzenleyin.
4.Tarayıcıdan index.php dosyasını çalıştırın.

Katkıda Bulunmak
Katkıda bulunmak isterseniz fork yaparak geliştirme yapabilir ve pull request gönderebilirsiniz. Hataları veya önerilerinizi Issues sekmesinden bildirebilirsiniz.
