# Fırsatlarım — PWA

Kampanya, indirim ve fırsat kodlarını tek yerden takip etmek için mobil web uygulaması.

## Özellikler
- Ekran görüntüsünden otomatik fırsat ekleme (Claude AI ile)
- Son kullanma tarihi uyarıları
- Tarayıcı bildirimleri
- Ana ekrana eklenebilir PWA
- Tüm veriler cihazda saklanır

## GitHub Pages'e Yükleme (Adım Adım)

### 1. Repository oluştur
- GitHub'da yeni bir repository aç (ör: `firsatlarim`)
- **Public** olarak işaretle

### 2. Dosyaları yükle
- `index.html` ve `manifest.json` dosyalarını repository'e yükle

### 3. GitHub Pages'i aç
- Repository → **Settings** → **Pages**
- Source: **Deploy from a branch**
- Branch: **main** → **/ (root)**
- **Save** tıkla

### 4. Linkini al
Birkaç dakika sonra:
`https://KULLANICI_ADIN.github.io/firsatlarim`

### 5. Telefona ekle
- Telefonda bu linki aç
- Safari (iOS): Paylaş → **Ana Ekrana Ekle**
- Chrome (Android): Menü → **Ana ekrana ekle**

## API Anahtarı (Ekran Görüntüsü Analizi)
Uygulamayı paylaştığın kişiler Ayarlar ekranından kendi Anthropic API anahtarlarını girerler.
Anahtar almak için: https://console.anthropic.com/settings/keys
