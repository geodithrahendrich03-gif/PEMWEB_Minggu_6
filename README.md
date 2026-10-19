1. Pengertian Bootstrap

Bootstrap adalah framework CSS open source untuk membuat tampilan website yang responsif dan mobile-first dengan komponen siap pakai seperti navbar, card, dan form. Kegunaannya mempercepat pembuatan tampilan, membuat halaman menyesuaikan ukuran layar, dan menjaga tampilan tetap konsisten di berbagai browser.

2. Memasang Bootstrap

Bootstrap bisa dipasang lewat CDN dengan tag <link> dan <script> dengan mengunduh file compiled lalu memanggilnya secara lokal lewat package manager seperti npm atau dengan memakai source Sass agar bisa dikustomisasi.

3. Grid dan Breakpoint

Grid adalah sistem layout yang membagi halaman menjadi 12 kolom memakai class container, row, dan col-*. Breakpoint adalah titik lebar layar (sm 576px, md 768px, lg 992px, xl 1200px, xxl 1400px) yang dipakai untuk mengubah tampilan sesuai ukuran layar misalnya col-12 col-md-6 yang menumpuk di HP dan berdampingan di desktop.

4. Class Bootstrap

Contoh class Bootstrap container untuk membungkus konten, row dan col-* untuk layout kolom, btn btn-primary untuk tombol biru, form-control untuk merapikan input, card untuk kotak konten, dan text-center untuk meratakan teks ke tengah.

5. Gambar Responsif

Tambahkan class img-fluid pada tag <img> yang menerapkan max-width: 100% dan height: auto sehingga gambar menyesuaikan lebar kontainernya dengan proporsi tetap terjaga.
