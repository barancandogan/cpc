# KVS Danışmanlık Limited Şirketi Web Sitesi

## GitHub'a Yükleme Talimatları

### Önemli: Klasör Yapısını Koruyun!

GitHub'a yüklerken **klasör yapısını mutlaka koruyun**. Aksi halde CSS ve JavaScript dosyaları çalışmayacaktır.

### Doğru Klasör Yapısı:

```
repo/
├── index.html
├── hakkimizda.html
├── iletisim.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── sozlesmeler/
    ├── index.html
    ├── hizmet-sartlari.html
    ├── gizlilik-guven.html
    ├── aydinlatma-metni.html
    └── kisisel-veriler.html
```

### GitHub'a Yükleme Yöntemleri:

#### Yöntem 1: GitHub Desktop ile
1. Tüm klasör yapısıyla birlikte repo'yu seçin
2. Commit ve Push yapın

#### Yöntem 2: Git Komutları ile
```bash
git add .
git commit -m "Initial commit"
git push
```

#### Yöntem 3: GitHub Web Arayüzü ile
1. "Add file" > "Upload files" seçin
2. **Tüm klasörleri** sürükleyip bırakın (css/, js/, sozlesmeler/)
3. Commit yapın

### GitHub Pages Ayarları:

1. Repo Settings > Pages
2. Source: "Deploy from a branch" seçin
3. Branch: "main" veya "master" seçin
4. Folder: "/ (root)" seçin
5. Save

### Sorun Giderme:

Eğer CSS yüklenmiyorsa:
- Tarayıcı konsolunu açın (F12)
- Network sekmesinde CSS dosyasının yüklenip yüklenmediğini kontrol edin
- Dosya yolu doğru mu kontrol edin
- Klasör yapısının korunduğundan emin olun

