# Web Scraper - Daftar Provinsi & Kota/Kabupaten Indonesia

Ini adalah script Python yang menggunakan library `BeautifulSoup` dan `Requests` untuk melakukan *web scraping* pada situs `indonesiapostcode.com`. Tujuannya adalah untuk mengumpulkan daftar semua provinsi beserta kota/kabupaten yang ada di Indonesia dan menyimpannya dalam satu file CSV.

---

## 🎯 Fitur Utama

* Mengambil daftar nama **Provinsi** dari halaman utama.
* Mengunjungi halaman setiap Provinsi untuk mengambil daftar nama **Kota/Kabupaten** di dalamnya.
* Menyimpan data yang terkumpul (Provinsi, Kota/Kabupaten, dan Link URL) ke dalam sebuah file CSV.

---

## ⚙️ Instalasi & Kebutuhan

Script ini dijalankan dalam format Jupyter Notebook (`.ipynb`) dan membutuhkan Python 3.

Anda dapat meng-install semua library yang diperlukan menggunakan `pip`:

```bash
pip install requests beautifulsoup4 pandas lxml
