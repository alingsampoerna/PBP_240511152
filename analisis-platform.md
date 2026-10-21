# Analisis Komparatif Platform dan refleksi

## 1. Analisis Komparatif Platform

| Aspek | Web | Desktop | Mobile |
|---|---|---|---|
| Bahasa utama | HTML dan CSS membangun tampilan, sedangkan JavaScript atau TypeScript menangani interaksi. Bahasa backend menyesuaikan kebutuhan server. | Bahasa seperti C#, Java, C++, dan Python digunakan sesuai jenis aplikasi dan framework yang dipilih. | Kotlin umum digunakan pada Android native, Swift pada iOS, sedangkan Dart dengan Flutter dapat digunakan untuk mengembangkan aplikasi lintas platform. |
| Arsitektur | Umumnya memisahkan sisi client dan server. Browser menangani tampilan serta interaksi, sementara server dapat mengelola autentikasi, logika bisnis, dan basis data. | Logika aplikasi dapat berjalan langsung pada komputer pengguna. Untuk aplikasi kolaboratif, pemrosesan dan penyimpanan data juga dapat melibatkan server. | Aplikasi berjalan pada sistem operasi seluler dan dapat menggabungkan komponen antarmuka, logika bisnis, penyimpanan lokal, serta layanan API. |
| Cara distribusi | Pengembang menerapkan aplikasi pada hosting atau server. Pengguna mengaksesnya melalui URL sehingga pembaruan di server dapat tersedia tanpa instalasi ulang di setiap komputer. | Aplikasi dapat dibagikan melalui installer, paket distribusi, toko aplikasi, atau sistem internal. Kompatibilitas sistem operasi perlu diperhatikan. | Aplikasi dapat dipublikasikan melalui Play Store atau App Store. Distribusi juga harus mempertimbangkan persyaratan toko, penandatanganan aplikasi, dan kompatibilitas perangkat. |
| Keunggulan | Cocok untuk sistem informasi yang digunakan banyak orang dari lokasi berbeda. Pemeliharaan terpusat mempermudah penerapan pembaruan dan pengelolaan layanan. | Cocok untuk pekerjaan yang membutuhkan integrasi sistem operasi, penggunaan perangkat keras tertentu, atau pemrosesan lokal yang intensif. | Mendukung penggunaan saat bepergian dan integrasi dengan fitur seperti kamera, GPS, sensor gerak, serta notifikasi. |
| Keterbatasan | Perbedaan browser dapat memengaruhi tampilan atau perilaku aplikasi. Fitur tertentu membutuhkan izin browser, dan layanan berbasis server bergantung pada konektivitas jaringan. | Pengembang dapat menghadapi perbedaan sistem operasi, kebutuhan instalasi, serta proses pembaruan pada perangkat pengguna. | Fragmentasi ukuran layar dan kemampuan perangkat menambah kebutuhan pengujian. Penggunaan GPS, kamera, dan proses latar belakang juga harus memperhatikan izin serta konsumsi baterai. |
| Contoh aplikasi | Sistem informasi akademik berbasis browser, dashboard pemantauan jaringan, dan layanan kolaborasi berbasis web. | Visual Studio Code, perangkat lunak desain seperti Blender, dan aplikasi pengelolaan basis data desktop. | Aplikasi navigasi, aplikasi pemantauan kebugaran, dan aplikasi perbankan digital. |
 |

Sumber Referensi

1. MDN Web Docs. Introduction to the Web. https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website
2. Microsoft Learn. Windows app development documentation. https://learn.microsoft.com/en-us/windows/apps/
3. Android Developers. Application fundamentals. https://developer.android.com/guide/components/fundamentals
4. Apple Developer. App Store distribution. https://developer.apple.com/app-store/


## 2. Refleksi
Setelah mempelajari perbedaan platform Web, Desktop, dan Mobile, saya tertarik untuk mendalami pengembangan aplikasi Web. Menurut saya, platform Web memiliki keunggulan dalam hal aksesibilitas karena pengguna dapat mengakses aplikasi melalui browser tanpa harus memasang program secara terpisah. Selain itu, pembaruan aplikasi dapat dilakukan melalui server sehingga pengembang lebih mudah melakukan pemeliharaan. Saya juga tertarik mempelajari bagaimana frontend, backend, dan basis data saling terhubung untuk membangun sebuah sistem informasi yang bermanfaat.

Tantangan terbesar yang saya perkirakan selama melakukan setup environment adalah memastikan seluruh perangkat pengembangan, seperti Git, Node.js, NPM, Visual Studio Code, dan Java JDK, terpasang serta dapat dijalankan dengan benar. Masalah seperti konfigurasi PATH atau versi perangkat lunak yang tidak sesuai dapat menghambat proses pengembangan jika tidak dipahami dengan baik.

Untuk mengatasi tantangan tersebut, saya akan memeriksa hasil instalasi melalui terminal, mempelajari dokumentasi resmi, dan mencari solusi secara bertahap apabila terjadi kesalahan. Saya juga akan membiasakan diri menggunakan Git dan GitHub untuk menyimpan serta mengelola perubahan kode. Dengan proses belajar dan latihan yang konsisten, saya berharap dapat membangun fondasi yang kuat untuk mengembangkan aplikasi secara mandiri maupun dalam tim.