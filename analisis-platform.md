# Analisis Komparatif Platform Web, Desktop, dan Mobile

## 1. Analisis Komparatif Platform

| Aspek | Web | Desktop | Mobile |
|---|---|---|---|
| Bahasa utama | HTML dan CSS membangun tampilan, sedangkan JavaScript atau TypeScript menangani interaksi. Bahasa backend menyesuaikan kebutuhan server. | Bahasa seperti C#, Java, C++, dan Python digunakan sesuai jenis aplikasi dan framework yang dipilih. | Kotlin umum digunakan pada Android native, Swift pada iOS, sedangkan Dart dengan Flutter dapat digunakan untuk mengembangkan aplikasi lintas platform. |
| Arsitektur | Umumnya memisahkan sisi client dan server. Browser menangani tampilan serta interaksi, sementara server dapat mengelola autentikasi, logika bisnis, dan basis data. | Logika aplikasi dapat berjalan langsung pada komputer pengguna. Untuk aplikasi kolaboratif, pemrosesan dan penyimpanan data juga dapat melibatkan server. | Aplikasi berjalan pada sistem operasi seluler dan dapat menggabungkan komponen antarmuka, logika bisnis, penyimpanan lokal, serta layanan API. |
| Cara distribusi | Pengembang menerapkan aplikasi pada hosting atau server. Pengguna mengaksesnya melalui URL sehingga pembaruan di server dapat tersedia tanpa instalasi ulang di setiap komputer. | Aplikasi dapat dibagikan melalui installer, paket distribusi, toko aplikasi, atau sistem internal. Kompatibilitas sistem operasi perlu diperhatikan. | Aplikasi dapat dipublikasikan melalui Play Store atau App Store. Distribusi juga harus mempertimbangkan persyaratan toko, penandatanganan aplikasi, dan kompatibilitas perangkat. |
| Keunggulan | Cocok untuk sistem informasi yang digunakan banyak orang dari lokasi berbeda. Pemeliharaan terpusat mempermudah penerapan pembaruan dan pengelolaan layanan. | Cocok untuk pekerjaan yang membutuhkan integrasi sistem operasi, penggunaan perangkat keras tertentu, atau pemrosesan lokal yang intensif. | Mendukung penggunaan saat bepergian dan integrasi dengan fitur seperti kamera, GPS, sensor gerak, serta notifikasi. |
| Keterbatasan | Perbedaan browser dapat memengaruhi tampilan atau perilaku aplikasi. Fitur tertentu membutuhkan izin browser, dan layanan berbasis server bergantung pada konektivitas jaringan. | Pengembang dapat menghadapi perbedaan sistem operasi, kebutuhan instalasi, serta proses pembaruan pada perangkat pengguna. | Fragmentasi ukuran layar dan kemampuan perangkat menambah kebutuhan pengujian. Penggunaan GPS, kamera, dan proses latar belakang juga harus memperhatikan izin serta konsumsi baterai. |
| Contoh aplikasi | Sistem informasi akademik berbasis browser, dashboard pemantauan jaringan, dan layanan kolaborasi berbasis web. | Visual Studio Code, perangkat lunak desain seperti Blender, dan aplikasi pengelolaan basis data desktop. | Aplikasi navigasi, aplikasi pemantauan kebugaran, dan aplikasi perbankan digital. |
| Pertimbangan pemilihan | Dipilih ketika akses lintas perangkat, pembaruan terpusat, dan kemudahan distribusi menjadi prioritas. | Dipilih ketika kontrol terhadap lingkungan komputer, integrasi sistem, atau pemrosesan lokal lebih penting. | Dipilih ketika layanan perlu digunakan secara praktis di perjalanan atau bergantung pada fitur perangkat seluler. |


## 3. Referensi

1. MDN Web Docs. Introduction to the Web. https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website
2. Microsoft Learn. Windows app development documentation. https://learn.microsoft.com/en-us/windows/apps/
3. Android Developers. Application fundamentals. https://developer.android.com/guide/components/fundamentals
4. Apple Developer. App Store distribution. https://developer.apple.com/app-store/
