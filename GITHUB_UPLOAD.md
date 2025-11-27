# 🚀 GitHub'a Toplu Yükleme Rehberi

## ✅ Hazırlananlar

**211 şehir** için JSON dosyaları oluşturuldu!
Her şehir 5 lokasyon içeriyor.

## 📦 1. Git Kurulumu

```powershell
# cities klasörüne git
cd cities

# Git başlat
git init

# Tüm dosyaları ekle
git add *.json README.md

# Commit yap
git commit -m "Add 211 cities data with 5 locations each"

# Ana branch'i ayarla
git branch -M main
```

## 🌐 2. GitHub Repository Oluştur

1. [GitHub](https://github.com) → **New repository**
2. İsim: `gezi-rehberi-data`
3. **Public** seç
4. **Create repository**

## 🔗 3. Remote Bağla ve Yükle

**GitHub kullanıcı adınızı yazın:**

```powershell
# Remote ekle (KULLANICI_ADINIZ yerine GitHub kullanıcı adınızı yazın)
git remote add origin https://github.com/KULLANICI_ADINIZ/gezi-rehberi-data.git

# Push yap
git push -u origin main
```

## ⚙️ 4. Uygulama Ayarları

`src/services/cityDataService.ts` dosyasını düzenle:

```typescript
const BASE_URL = 'https://raw.githubusercontent.com/KULLANICI_ADINIZ/gezi-rehberi-data/main';
```

## ✨ Tamamlandı!

211 şehir artık online erişilebilir!

### Test:
```
https://raw.githubusercontent.com/KULLANICI_ADINIZ/gezi-rehberi-data/main/istanbul.json
```

---

## 📊 İstatistikler

- **Toplam Şehir**: 211
- **Lokasyon/Şehir**: 5
- **Toplam Lokasyon**: 1055
- **Dosya Boyutu**: ~500KB
- **Maliyet**: ÜCRETSİZ!
