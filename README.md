# telefonno_kontrol
Matematiksel kurallara dayalı, modern arayüzlü ve Python/Flask tabanlı Kasaba Telefon Kayıt Sistemi.
# 🏙️ Kasaba Telefon Kayıt Sistemi (Town Phone Registry)

> Özel matematiksel algoritmalarla doğrulama yapan, modern ve güvenli bir telefon rehberi simülasyonu.

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Flask](https://img.shields.io/badge/Flask-2.x-green.svg)
![MySQL](https://img.shields.io/badge/MySQL-8.0-orange.svg)
![Frontend](https://img.shields.io/badge/UI-Glassmorphism-purple.svg)

## 📖 Proje Hakkında

Bu proje, sıradan bir rehber uygulamasından farklı olarak, telefon numaralarının belirli **matematiksel ve mantıksal kurallara** uymasını zorunlu kılan bir web uygulamasıdır. Kullanıcı arayüzü, modern **Glassmorphism (Buzlu Cam)** tasarım dili kullanılarak, CSS ve Vanilla JS ile geliştirilmiştir.

### 🎯 Temel Özellikler

* **Matematiksel Doğrulama:** Girilen numaranın (Örn: 123123) ilk 3 hanesinin toplamı, son 3 hanesinin toplamına eşit olmalıdır. Ayrıca tek ve çift basamakların toplamları da birbirini tutmalıdır.
* **Dinamik Arayüz:** Kullanıcı numarayı yazarken kurallar anlık olarak kontrol edilir (Frontend Validation).
* **Modern UI:** Split-screen (Bölünmüş ekran) tasarımı ve gece modu estetiği.
* **Tam Entegrasyon:** Python (Flask) Backend ve MySQL veritabanı ile tam çalışan bir kayıt sistemi.

## 🛠️ Teknolojiler

* **Backend:** Python, Flask, Flask-MySQLdb
* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **Veritabanı:** MySQL
* **Tasarım:** Custom CSS (Glassmorphism Effects)

## 🚀 Kurulum

Projeyi kendi bilgisayarınızda çalıştırmak için:

1.  Python kütüphanelerini yükleyin:
    ```bash
    pip install Flask flask-mysqldb flask-cors
    ```
2.  MySQL veritabanını oluşturun:
    ```sql
    CREATE DATABASE telefon_db;
    ```
3.  `app.py` dosyasını çalıştırın:
    ```bash
    python app.py
    ```
4.  Tarayıcıda `http://localhost:5001` adresine gidin.
   
5.  ## 🐳 Docker ile Hızlı Kurulum (Önerilen)

Projeyi bilgisayarınıza Python veya MySQL kurmadan, sadece Docker kullanarak tek komutla çalıştırabilirsiniz.

1.  Projeyi indirin ve klasöre gidin.<img width="355" height="481" alt="Ekran Resmi 2025-12-09 18 54 29" src="https://github.com/user-attachments/assets/b5d402c6-1b54-4cbc-936f-

https://github.com/user-attachments/assets/b668cc1d-6f99-49e6-9900-ba2ef8cbc1ee

2240436b4b29" />

2.  Terminali açın ve şu komutu
 çalıştırın:


```bash
docker-compose up --build
 ```

<img width="440" height="547" alt="Ekran Resmi 2025-12-09 18 57 36" src="https://github.com/user-attachments/assets/a5ac18cd-e075-4453-8d6b-05d9557c2edd" />

<img width="547" height="253" alt="Ekran Resmi 2025-12-09 18 57 54" src="https://github.com/user-attachments/assets/2c061cd5-f4a6-42b8-b774-79d77c8d4a1b" />

