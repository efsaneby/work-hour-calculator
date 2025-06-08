# Work Hour Calculator 🕒

Günlük çalışma saatlerine göre maaş hesaplama uygulaması - ASP.NET Core & Angular

## 📋 Proje Açıklaması

Çalışma saatlerimi takip edip aylık maaşımı hesaplayan basit bir uygulama.

## 🛠️ Teknolojiler

- **Backend**: ASP.NET Core Web API (.NET 8)
- **Database**: SQL Server (LocalDB)
- **ORM**: Entity Framework Core (Code First)
- **Frontend**: Angular (Planlanan)
- **Version Control**: Git & GitHub

## 📊 Veritabanı Yapısı

### WorkHours Tablosu
- Günlük çalışma kayıtları
- Başlangıç/bitiş saatleri
- Mola süreleri
- Hafta sonu/mesai takibi

### SalarySettings Tablosu
- Saatlik ücret ayarları
- Mesai/hafta sonu çarpanları
- Tarihi ayar yönetimi

## ✅ Tamamlanan Aşamalar

### 🎯 Gün 1: Proje Başlangıcı
- ✅ GitHub repo oluşturuldu
- ✅ README.md hazırlandı
- ✅ Proje mimarisi planlandı

### 🎯 Gün 2: Veritabanı Tasarımı
- ✅ Veritabanı şeması tasarlandı
- ✅ Tablo yapıları belirlendi
- ✅ İş kuralları tanımlandı

### 🎯 Gün 3: ASP.NET Core Kurulumu
- ✅ Visual Studio'da Web API projesi oluşturuldu
- ✅ Entity Framework Core kurulumu
- ✅ Model sınıfları (WorkHour, SalarySetting)
- ✅ DbContext yapılandırması
- ✅ Code First Migration
- ✅ Veritabanı oluşturuldu

## 📝 Sonraki Aşamalar

### 🎯 Gün 4: API Controller'ları
- [ ] WorkHours Controller
- [ ] CRUD operations (GET, POST, PUT, DELETE)
- [ ] Maaş hesaplama endpoint'i
- [ ] Swagger ile API test

### 🎯 Gün 5: İş Mantığı
- [ ] Maaş hesaplama servisi
- [ ] Mesai/hafta sonu hesaplamaları
- [ ] Raporlama fonksiyonları

### 🎯 Gün 6-10: Frontend (Angular)
- [ ] Angular projesi kurulumu
- [ ] Çalışma saati giriş formu
- [ ] Maaş hesaplama ekranı
- [ ] Raporlama sayfası

## 🚀 Kurulum

### Gereksinimler
- Visual Studio 2022
- .NET 8 SDK
- SQL Server LocalDB

### Adımlar
1. Repoyu klonlayın
```bash
git clone https://github.com/efsaneby/work-hour-calculator.git
```

2. Backend projesini açın
```bash
cd work-hour-calculator/backend
```

3. NuGet paketlerini yükleyin
```bash
dotnet restore
```

4. Veritabanını oluşturun
```bash
dotnet ef database update
```

5. Projeyi çalıştırın
```bash
dotnet run
```

## 📈 İlerleme Durumu

**Toplam İlerleme**: 30% tamamlandı

- ✅ Proje Kurulumu (100%)
- ✅ Veritabanı Tasarımı (100%)
- ✅ Backend Temeli (100%)
- ⏳ API Geliştirme (0%)
- ⏳ Frontend Geliştirme (0%)

## 📅 Çalışma Planı

Günlük 15-30 dakika çalışma planı ile ilerleyeceğiz.

## 📝 Notlar

- Code First yaklaşımı kullanılıyor
- Seed data ile varsayılan ayarlar yükleniyor
- DateTime alanları otomatik güncelleniyor
- Migration'lar version control'de takip ediliyor

---

**Son Güncelleme**: 8 Haziran 2025 - Gün 3 tamamlandı 🎉
