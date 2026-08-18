# AnjaniERP Web

Landing page statis untuk AnjaniERP. Tidak membutuhkan package manager atau proses build.

## Menjalankan lokal

Buka `index.html` langsung di browser, atau jalankan server statis dari folder ini:

```powershell
python -m http.server 8080
```

Kemudian buka `http://localhost:8080`.

Sebelum produksi, ganti alamat email CTA `hello@anjanierp.com` dengan kanal penjualan resmi.

## SEO dan domain

Metadata canonical, Open Graph, Twitter Card, structured data, sitemap, dan
robots saat ini menggunakan `https://anjanierp.com`. Jika domain produksi
berbeda, ganti semua URL absolut tersebut pada `index.html`, `robots.txt`, dan
`sitemap.xml` sebelum deployment.
