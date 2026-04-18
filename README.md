# Website Profil Desa Sukamaju

## Cara Hosting

1. Letakkan folder `web_desa` di folder root server lokal atau hosting static.
2. Pastikan file `index.html`, `profil-desa.html`, `images/`, dan `.htaccess` berada di root folder.
3. Buka `http://localhost/web_desa/` untuk melihat situs.

## File Utama

- `index.html` — halaman awal yang mengarahkan ke `profil-desa.html`
- `profil-desa.html` — halaman profil desa utama
- `.htaccess` — agar permintaan ke root diarahkan ke `profil-desa.html`
- `images/` — folder asset gambar

## Catatan

Jika hosting tidak menggunakan Apache, `index.html` akan langsung membuka `profil-desa.html` melalui pengalihan HTML.
