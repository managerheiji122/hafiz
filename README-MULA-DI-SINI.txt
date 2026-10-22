HAFIZ PERSONAL DIGITAL HUB — PWA UNTUK ANDROID

KANDUNGAN
- index.html: halaman utama
- manifest.json: nama, ikon dan mod aplikasi
- sw.js: service worker untuk cache asas/offline
- icons/: ikon aplikasi

PENTING
PWA perlu dihoskan melalui HTTPS. GitHub Pages sesuai untuk fail statik ini. GitHub Pages lazimnya menjadikan laman web boleh diakses umum; jangan masukkan maklumat sulit.

CARA TERBITKAN DI GITHUB PAGES
1. Log masuk ke https://github.com/ dan cipta repository baharu, contohnya hafiz-personal-digital-hub.
2. Jika menggunakan GitHub Free, tetapkan repository sebagai Public.
3. Muat naik SEMUA kandungan folder ini ke akar repository (index.html, manifest.json, sw.js, folder icons). Jangan muat naik fail ZIP sahaja.
4. Dalam repository, buka Settings > Pages.
5. Di bahagian Build and deployment, pilih Deploy from a branch, branch main dan folder /(root), kemudian Save.
6. Tunggu penerbitan selesai. URL biasanya seperti https://NAMA-ANDA.github.io/hafiz-personal-digital-hub/
7. Buka URL tersebut pada Chrome Android. Buka menu ⋮ dan pilih Install app (atau Add to Home screen jika itu pilihan yang dipaparkan).
8. Selepas dipasang, buka ikon Hafiz Hub dari skrin utama. Ia menggunakan display=standalone supaya dibuka seperti aplikasi, tanpa bar alamat biasa.

NOTA
- GitHub Pages tidak boleh diterbitkan dari sini kerana perlu akses akaun GitHub anda.
- Pemasangan bergantung pada Chrome/peranti dan HTTPS.
- Service worker menyediakan cache asas untuk halaman utama; pautan luaran tetap memerlukan internet.
- Butang salin maklumat menggunakan clipboard dan biasanya memerlukan HTTPS.
- Jika anda ubah fail kemudian, muat naik semula ke repository. Jika paparan lama masih muncul, tutup aplikasi dan buka semula selepas beberapa ketika.
