# Rota — Furniture Catalog

Rota Furniture koleksiyonu için ürün kataloğu sitesi.
Product catalog site for the Rota Furniture collection.

Tek dosyalık statik site — kurulum/derleme gerektirmez.
Single-file static site — no build step required.

## Özellikler / Features
- İki dil / Bilingual: Türkçe + English (tercih hatırlanır)
- 94 ürün, 6 kategori — filtrelenebilir ürün ızgarası, tıkla-büyüt galeri (lightbox)
- Katalog PDF görüntüleme & indirme (7 sayfa)
- "Audio & Visual" kataloğu için hazır placeholder bölüm
- Tamamen responsive

Ürünler `assets/products.json` üzerinden yüklenir; görseller PDF kataloğundan otomatik ayıklanmıştır.
Products load from `assets/products.json`; images are auto-extracted from the PDF catalog.

## Çalıştırma / Run
```bash
npx serve .
```

## Yapı / Structure
```
index.html                 # tüm site (HTML + CSS + JS)
assets/
  rotalogo.png             # logo
  products.json            # ürün manifesti / product manifest
  products/*.jpg           # ayıklanmış ürün görselleri / extracted products
  pages/p1..p7.jpg         # katalog sayfaları / catalog pages
  catalog/*.pdf            # kaynak katalog / source PDF
```

---
© 2025 Rota · Merchandising · Marketing · Design · www.rotagroup.net.tr
