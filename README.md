# ENG \ Real-Time Messaging Application

A comprehensive real-time communication platform built with Django and WebRTC, featuring text, voice, and video messaging capabilities.

## 🌟 Features

### Text Messaging
- Real-time messaging using WebSocket
- Message read status indicators
- Image sharing with drag-and-drop support
- Emoji support
- Password-protected chat rooms
- Cloud storage integration with Firebase

### Voice & Video Calls
- Real-time voice and video communication using WebRTC
- Dynamic participant management
- Audio level visualization
- Microphone sensitivity control
- Camera toggle functionality
- Multi-participant support

## 🛠 Technologies Used
- **Backend:**
  - Python
  - Django
  - Django Channels
  - Daphne
- **Frontend:**
  - HTML
  - CSS
  - JavaScript
- **Real-time Communication:**
  - WebSocket
  - WebRTC
- **Storage:**
  - Firebase
  - Cloudinary (for image storage)

## ⚙️ System Architecture

### Text Messaging Components
- WebSocket-based real-time communication
- XOR-based message encryption
- Base64 message encoding
- Firebase integration for message storage
- Cloudinary integration for image handling

### Voice/Video Components
- WebRTC peer connections management
- ICE candidate handling
- Real-time audio level monitoring
- Dynamic participant management
- Audio/Video stream handling

## 🚀 Setup and Installation

1. Clone the repository
```bash
git clone [repository-url]
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Configure environment variables
```bash
# Create .env file with following variables
FIREBASE_CONFIG=
CLOUDINARY_CONFIG=
```

4. Run migrations
```bash
python manage.py migrate
```

5. Start the server
```bash
python manage.py runserver
```

## 💡 Usage

### Creating a Chat Room
1. Register/Login to the application
2. Create a new room (with optional password protection)
3. Share the room link with participants

### Starting a Voice/Video Call
1. Join a chat room
2. Click on the call button
3. Grant necessary permissions for camera/microphone
4. Start communicating!

## 👥 Contributors
- **Frontend & Authentication**: Ferhan Hacısalioğlu
- **-Video Implementation**: Batuhan Akçan
- **Voice and WebRTC Implementation**: Ferhan Hacısalioğlu
- **Text Messaging System**: Both contributors

## 🔒 Security Features
- Password-protected rooms
- Secure WebRTC connections
- Firebase authentication
- Message read status verification

## 📸 Screenshots

![Screenshot 2025-01-08 104002](https://github.com/user-attachments/assets/8d59a41d-7e88-4207-b6e1-9a9629459dd3)

![Screenshot 2025-01-08 103948](https://github.com/user-attachments/assets/a1989448-6192-4d3b-bea4-89fdf2e194f7)

![Screenshot 2025-01-08 104209](https://github.com/user-attachments/assets/43ec7bf7-60d0-46fc-a668-4c5e9dc58bd6)

## 🎓 Academic Context
This project was developed as part of the Computer Networks course (BSM307) at Bartın University, Faculty of Science, Department of Computer Technology and Information Systems, under the supervision of Assoc. Prof. Dr. Evrim GÜLER.

---

# TR \ Gerçek Zamanlı Mesajlaşma Uygulaması

Django ve WebRTC ile geliştirilmiş, metin, ses ve görüntülü iletişim özelliklerine sahip kapsamlı bir gerçek zamanlı iletişim platformu.

## 🌟 Özellikler

### Metin Mesajlaşma
- WebSocket kullanarak gerçek zamanlı mesajlaşma
- Mesaj okundu durumu göstergeleri
- Sürükle-bırak destekli görüntü paylaşımı
- Emoji desteği
- Şifre korumalı sohbet odaları
- Firebase ile bulut depolama entegrasyonu

### Sesli ve Görüntülü Aramalar
- WebRTC kullanarak gerçek zamanlı ses ve görüntü iletişimi
- Dinamik katılımcı yönetimi
- Ses seviyesi görselleştirme
- Mikrofon hassasiyeti kontrolü
- Kamera açma/kapama işlevi
- Çoklu katılımcı desteği

## 🛠 Kullanılan Teknolojiler
- **Backend:**
  - Python
  - Django
  - Django Channels
  - Daphne
- **Frontend:**
  - HTML
  - CSS
  - JavaScript
- **Gerçek Zamanlı İletişim:**
  - WebSocket
  - WebRTC
- **Depolama:**
  - Firebase
  - Cloudinary (görüntü depolama için)

## ⚙️ Sistem Mimarisi

### Metin Mesajlaşma Bileşenleri
- WebSocket tabanlı gerçek zamanlı iletişim
- XOR tabanlı mesaj şifreleme
- Base64 mesaj kodlama
- Firebase mesaj depolama entegrasyonu
- Cloudinary görüntü işleme entegrasyonu

### Ses/Görüntü Bileşenleri
- WebRTC eş bağlantıları yönetimi
- ICE aday yönetimi
- Gerçek zamanlı ses seviyesi izleme
- Dinamik katılımcı yönetimi
- Ses/Görüntü akışı yönetimi

## 🚀 Kurulum ve Yükleme

1. Depoyu klonlayın
```bash
git clone [depo-url]
```

2. Bağımlılıkları yükleyin
```bash
pip install -r requirements.txt
```

3. Ortam değişkenlerini yapılandırın
```bash
# .env dosyası oluşturun ve aşağıdaki değişkenleri ekleyin
FIREBASE_CONFIG=
CLOUDINARY_CONFIG=
```

4. Migrasyonları çalıştırın
```bash
python manage.py migrate
```

5. Sunucuyu başlatın
```bash
python manage.py runserver
```

## 💡 Kullanım

### Sohbet Odası Oluşturma
1. Uygulamaya kayıt olun/giriş yapın
2. Yeni bir oda oluşturun (isteğe bağlı şifre koruması ile)
3. Oda bağlantısını katılımcılarla paylaşın

### Sesli/Görüntülü Arama Başlatma
1. Bir sohbet odasına katılın
2. Arama butonuna tıklayın
3. Kamera/mikrofon için gerekli izinleri verin
4. İletişime başlayın!

## 👥 Katkıda Bulunanlar
- **Frontend ve Kimlik Doğrulama**: Ferhan Hacısalioğlu
- **Görüntü Uygulaması**: Batuhan Akçan
- **Ses ve WebRTC Uygulaması**: Ferhan Hacısalioğlu
- **Metin Mesajlaşma Sistemi**: Her iki katkıda bulunan

## 🔒 Güvenlik Özellikleri
- Şifre korumalı odalar
- Güvenli WebRTC bağlantıları
- Firebase kimlik doğrulama
- Mesaj okundu durumu doğrulama

## 📸 Ekran Görüntüleri

![Screenshot 2025-01-08 104002](https://github.com/user-attachments/assets/8d59a41d-7e88-4207-b6e1-9a9629459dd3)

![Screenshot 2025-01-08 103948](https://github.com/user-attachments/assets/a1989448-6192-4d3b-bea4-89fdf2e194f7)

![Screenshot 2025-01-08 104209](https://github.com/user-attachments/assets/43ec7bf7-60d0-46fc-a668-4c5e9dc58bd6)

## 🎓 Akademik Bağlam
Bu proje, Bartın Üniversitesi Fen Fakültesi Bilgisayar Teknolojisi ve Bilişim Sistemleri Bölümü'nde, Doç. Dr. Evrim GÜLER danışmanlığında, Bilgisayar Ağları (BSM307) dersi kapsamında geliştirilmiştir.
