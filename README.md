# GeziRehberi - City Data JSON Files

## 📍 Hazır JSON Dosyaları

Bu klasörde GitHub'a yüklenmeye hazır şehir veri dosyaları bulunmaktadır.

### Mevcut Şehirler:
- ✅ **istanbul.json** - 5 lokasyon
- ✅ **tokyo.json** - 5 lokasyon
- ✅ **rome.json** - 5 lokasyon
- ✅ **london.json** - 5 lokasyon
- ✅ **new_york.json** - 5 lokasyon
- ✅ **barcelona.json** - 5 lokasyon
- ✅ **dubai.json** - 5 lokasyon

### GitHub'a Yükleme:
1. GitHub'da `gezi-rehberi-data` repository'si oluşturun
2. `cities/` klasörü oluşturun
3. Bu JSON dosyalarını yükleyin
4. Raw URL'yi alın ve `cityDataService.ts`'de güncelleyin

### Örnek Raw URL:
```
https://raw.githubusercontent.com/KULLANICI_ADINIZ/gezi-rehberi-data/main/cities/istanbul.json
```

### JSON Format:
Her dosya bir lokasyon dizisi içerir:
```json
[
  {
    "id": "unique_id",
    "name": "Lokasyon Adı",
    "category": "Tarihi/Müze/Park/vb",
    "image": "Unsplash URL",
    "description": "Açıklama",
    "coordinates": { "latitude": 0.0, "longitude": 0.0 },
    "estimatedDuration": 90,
    "openingTime": "09:00",
    "closingTime": "18:00",
    "cost": 0,
    "interests": ["Tarihi", "Müze"]
  }
]
```

Daha fazla lokasyon eklemek için mevcut formata uyun!
