# GitHub CSS Sorunu Çözümü

## Sorun
GitHub'da dosyalar düz yüklenmiş ve CSS yüklenmiyor.

## Çözüm 1: Klasör Yapısını Koruyarak Yeniden Yükleme (ÖNERİLEN)

1. GitHub repo'nuzdan tüm dosyaları silin
2. Yerel klasörünüzdeki **TÜM KLASÖRLERLE BİRLİKTE** dosyaları yükleyin:
   - `css/` klasörü
   - `js/` klasörü  
   - `sozlesmeler/` klasörü
   - Tüm HTML dosyaları

## Çözüm 2: Dosyalar Root'ta İse

Eğer CSS dosyası root'ta ise, HTML dosyalarındaki yolları şu şekilde değiştirin:

**Ana sayfalar için:**
- `href="./css/style.css"` → `href="style.css"`
- `src="./js/script.js"` → `src="script.js"`

**sozlesmeler/ klasöründeki sayfalar için:**
- `href="../css/style.css"` → `href="../style.css"`
- `src="../js/script.js"` → `src="../script.js"`

## Kontrol

GitHub Pages'de siteyi açtığınızda:
1. F12 ile Developer Tools'u açın
2. Console sekmesinde hata var mı kontrol edin
3. Network sekmesinde CSS dosyasının yüklenip yüklenmediğini kontrol edin

