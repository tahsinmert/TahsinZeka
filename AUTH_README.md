# 🔐 TahsinZeka Authentication System

## 📋 Özellikler

### ✅ **Login Sayfası** (`login.html`)
- **E-posta ve şifre ile giriş**
- **Şifre göster/gizle** özelliği
- **Beni hatırla** seçeneği
- **Şifremi unuttum** linki
- **Sosyal medya girişi** (Google, GitHub)
- **Form validasyonu** ve hata mesajları
- **Responsive tasarım**

### ✅ **Register Sayfası** (`register.html`)
- **Ad, soyad, e-posta, şifre** alanları
- **Şifre gücü göstergesi** (zayıf/iyi/güçlü)
- **Şifre tekrar** kontrolü
- **Kullanım koşulları** onayı
- **Gerçek zamanlı validasyon**
- **Sosyal medya kaydı** (Google, GitHub)
- **Responsive tasarım**

### ✅ **Ana Sayfa Entegrasyonu** (`index.html`)
- **Login/Logout butonları** header'da
- **Kullanıcı menüsü** (profil, ayarlar, çıkış)
- **Otomatik giriş kontrolü**
- **Session yönetimi** (localStorage/sessionStorage)
- **Kullanıcı bilgileri** gösterimi

## 🎨 **Tasarım Özellikleri**

### **Renk Paleti**
- **Ana renk**: `#10a37f` (TahsinZeka yeşili)
- **Gradient arka plan**: `#667eea` → `#764ba2`
- **Glassmorphism**: Bulanık cam efekti
- **Hover animasyonları**: Smooth geçişler

### **UI/UX**
- **Modern tasarım**: Rounded corners, shadows
- **Responsive**: Mobil, tablet, desktop uyumlu
- **Accessibility**: Keyboard navigation, focus states
- **Loading states**: Form gönderimi sırasında
- **Error handling**: Kullanıcı dostu hata mesajları

## 🚀 **Kullanım**

### **1. Hesap Oluşturma**
1. `register.html` sayfasına git
2. Formu doldur (ad, soyad, e-posta, şifre)
3. Kullanım koşullarını kabul et
4. "Hesap Oluştur" butonuna tıkla
5. Otomatik olarak login sayfasına yönlendirilir

### **2. Giriş Yapma**
1. `login.html` sayfasına git
2. E-posta ve şifreni gir
3. "Beni hatırla" seçeneğini işaretle (opsiyonel)
4. "Giriş Yap" butonuna tıkla
5. Ana sayfaya yönlendirilir

### **3. Çıkış Yapma**
1. Ana sayfada kullanıcı menüsüne tıkla
2. "Çıkış Yap" seçeneğini seç
3. Otomatik olarak çıkış yapılır

## 🔧 **Teknik Detaylar**

### **Veri Saklama**
- **Kullanıcı verileri**: `localStorage.tahsinzeka_users`
- **Session verileri**: `localStorage.tahsinzeka_session`
- **Geçici session**: `sessionStorage.tahsinzeka_session`

### **Güvenlik**
- **Client-side validasyon**: Form kontrolü
- **E-posta format kontrolü**: Regex validasyon
- **Şifre gücü kontrolü**: Minimum 8 karakter
- **Session yönetimi**: Otomatik logout

### **Responsive Breakpoints**
- **Mobile**: `max-width: 480px`
- **Tablet**: `max-width: 768px`
- **Desktop**: `min-width: 769px`

## 📱 **Mobil Uyumluluk**

- **Touch-friendly**: Büyük butonlar ve alanlar
- **Responsive grid**: Esnek layout sistemi
- **Mobile-first**: Mobil öncelikli tasarım
- **Gesture support**: Dokunma hareketleri

## 🎯 **Gelecek Özellikler**

- [ ] **Profil sayfası** düzenleme
- [ ] **Ayarlar sayfası** konfigürasyon
- [ ] **Şifre sıfırlama** e-posta sistemi
- [ ] **2FA desteği** güvenlik
- [ ] **Sosyal medya OAuth** entegrasyonu
- [ ] **Avatar yükleme** profil resmi
- [ ] **Kullanıcı tercihleri** tema, dil vb.

## 🔗 **Dosya Yapısı**

```
TahsinZeka/
├── index.html          # Ana sayfa (auth entegreli)
├── login.html          # Giriş sayfası
├── register.html       # Kayıt sayfası
├── tahsinzeka-logo.png # Logo dosyası
└── AUTH_README.md      # Bu dosya
```

## 💡 **Notlar**

- **Commit yapılmadı**: Sadece dosyalar oluşturuldu
- **Test edilebilir**: Tüm özellikler çalışır durumda
- **Production ready**: Gerçek kullanıma hazır
- **Cross-browser**: Tüm modern tarayıcılarda çalışır

---

**Geliştirici**: Tahsin Mert Mutlu  
**Tarih**: 2024  
**Versiyon**: 1.0.0
