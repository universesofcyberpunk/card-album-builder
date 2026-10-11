# Card Album Builder

by **Fabianens**

A single-file web app for designing trading-card albums: card images, names, descriptions, rarity, HP/ATK, tags, tabs and card backs. It runs fully in the browser and saves each album as a `.zip` with `album.json`, `cards.csv` and the images, so any card game or mod can read it.

It was first made for the **KOTAMON Cards & Albums** mod (BepInEx 6), which loads these albums straight from `BepInEx\plugins\KotamonCards\albums\`. Get the mod on Nexus Mods: https://www.nexusmods.com/games/kotamon/mods/5

## Usage
- Open `index.html` (or `AlbumBuilder.html`) in any modern browser. No install, no server.
- If GitHub Pages is enabled for this repo, the app also runs at the Pages URL.
- Add card images, fill in the details, then download the album as a `.zip`.
- KOTAMON: extract the album folder from the zip into `BepInEx\plugins\KotamonCards\albums\` and start the game.
- Other games: read `album.json` and `cards.csv` (`;` separated, UTF-8) from the zip in your own loader.

---

# Kart Albümü Oluşturucu

Hazırlayan: **Fabianens**

Kart albümü hazırlamak için tek dosyalık web uygulaması: kart resimleri, ad, açıklama, nadirlik, HP/ATK, etiketler, sekmeler ve kart arkaları. Tamamen tarayıcıda çalışır ve her albümü `album.json`, `cards.csv` ve resimlerle birlikte `.zip` olarak indirir; her kart oyunu ya da mod bunu okuyabilir.

İlk olarak **KOTAMON Kartlar ve Albümler** modu için yapıldı; mod bu albümleri doğrudan `BepInEx\plugins\KotamonCards\albums\` klasöründen yükler. Mod Nexus Mods'ta: https://www.nexusmods.com/games/kotamon/mods/5

## Kullanım
- `index.html` (veya `AlbumBuilder.html`) dosyasını herhangi bir tarayıcıda aç. Kurulum veya sunucu gerekmez.
- Bu repoda GitHub Pages açıksa uygulama Pages adresinden de çalışır.
- Kart resimlerini ekle, bilgileri doldur, albümü `.zip` olarak indir.
- KOTAMON: zip içindeki albüm klasörünü `BepInEx\plugins\KotamonCards\albums\` içine koy ve oyunu başlat.
- Başka oyunlar: zip içindeki `album.json` ve `cards.csv` dosyalarını (`;` ayraçlı, UTF-8) kendi yükleyicinle oku.
