# BİTEM Desktop Search — Binary Releases

Public download mirror for BİTEM Desktop Search installers. Search inside documents, scanned PDFs, photos and e-mail — entirely on your own computer.

**Latest release:** see the [Releases](https://github.com/daltinderee-gif/bitem-releases/releases) page.

**Source code:** private (commercial).

## Installers

- 🪟 **Windows** 10 / 11 (x64): [`BITEM-Desktop-Search-Kurulum.exe`](https://github.com/daltinderee-gif/bitem-releases/releases/latest/download/BITEM-Desktop-Search-Kurulum.exe)
- 🍎 **macOS** 12 or newer (Apple Silicon and Intel): [`BITEM-Desktop-Search.dmg`](https://github.com/daltinderee-gif/bitem-releases/releases/latest/download/BITEM-Desktop-Search.dmg)

Each release lists the SHA-256 of every file, so IT can verify that an installer has not been altered.

## Türkçe

BİTEM Desktop Search kurulum dosyalarının herkese açık indirme sayfası. Program belgelerin, taranmış PDF'lerin, fotoğrafların ve e-postaların içinde arar; tarama ve arama yalnız sizin bilgisayarınızda yapılır, hiçbir belge bir sunucuya gönderilmez.

- **Windows 10 / 11:** [Kurulum dosyasını indir](https://github.com/daltinderee-gif/bitem-releases/releases/latest/download/BITEM-Desktop-Search-Kurulum.exe)
- **macOS 12 ve üzeri:** [.dmg dosyasını indir](https://github.com/daltinderee-gif/bitem-releases/releases/latest/download/BITEM-Desktop-Search.dmg)

Kurulum dosyaları henüz dijital imzalı değildir. Windows “Windows bilgisayarınızı korudu” derse **Ek bilgi › Yine de çalıştır**'a basın.

Mac'te uygulamayı Uygulamalar klasörüne sürükledikten sonra, ilk açılıştan önce bir kez Terminal'e şu satırı yapıştırıp Enter'a basın (yoksa “Apple doğrulayamadı” der):

```
xattr -rd com.apple.quarantine "/Applications/BİTEM Desktop Search.app"
```

Aynı adımlar .dmg içindeki “Önce Beni Oku” dosyasında da yazılı.

Kurumsal toplu kurulum (Windows):

```
BITEM-Desktop-Search-Kurulum.exe /VERYSILENT /SUPPRESSMSGBOXES /NORESTART
```

## Support

Questions and bug reports: contact the BİTEM team directly. This repository hosts installers only — no issue tracker.
