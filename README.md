# Google-Earth-Engine
Muhammad Faisal Anshory / 15118015

[<img src="https://geospatialmedia.s3.amazonaws.com/wp-content/uploads/2020/07/google-earth-engine.jpg" alt="gee logo" width="500">](https://earthengine.google.com/)

  Google Earth Engine adalah layanan pemrosesan geospasial. Dengan Earth Engine, Anda dapat melakukan pemrosesan geospasial dalam skala besar, diberdayakan oleh Google Cloud Platform. Tujuan Earth Engine adalah untuk:

 - Menyediakan platform interaktif untuk pengembangan algoritme geospasial dalam skala besar
 - Aktifkan sains berdampak tinggi dan berbasis data
 - Membuat kemajuan substantif dalam tantangan global yang melibatkan kumpulan data geospasial yang besar

Adapun Komponen utama Earth Engine adalah :

1. Dataset : Anda tidak perlu repot-repot mencari sumber citra skala menengah yang tersedia secara publik lagi melalui platform USGS maupun ESA, Google Earth Engine telah mengumpulkannya menjadi satu di platformnya. Google Earth Engine memiliki arsip citra penginderaan jauh berukuran petabyte yang siap Anda gunakan. Sangat praktis untuk analis Geografi.

2. Kemampuan komputasi yang lebih dari perangkat Anda : Saat Anda menggunakan Google Earth Engine, sejatinya Anda tidak menggunakan perangkat Anda sendiri sebagai ‘pemikir’ dari proses yang akan dilakukan. Dengan ukuran data sebesar ini, sangat mungkin perangkat Anda tidak dapat memproses dengan baik. Infrastruktur Google sebagai cloud yang akan Anda gunakan untuk Google Earth Engine merupakan tawaran yang sangat menarik (mumpung belum berbayar), ditambah dengan library data yang begitu lengkap (Gorelick et al., 2017).

3. APIs : Google Earth Engine juga menawarkan API untuk Anda dengan menggunakan JavaScript dan Python yang dihostkan ke Github, membuatnya mudah untuk melakukan request ke server Google Earth Engine. Menurut saya pribadi, documentation dan forum yang telah ada cenderung mengarah kepada kemudahan dalam menggunakan Javascript daripada Python. Namun jangan khawatir. Apabila Anda lebih familier dengan Python maka mari bersama membangun komunitas ini.

4. Code Editor : Google Earth Engine juga menawarkan IDE (Integrated Development Environment) daring untuk kecepatan dalam membuat prototype serta visualisasi data spasial yang kompleks dengan analisis yang kompleks pula menggunakan Javascript API.

Kenapa Google Earth Engine ini penting?

  Apabila kita ingin melakukan analisis lingkungan berskala besar, maka kita memelurkan data peta/foto udara/satelit berskala besar pula. Selain itu, untuk melakukan pemprosesan terhadap data yang berskala besar itu, kita memerlukan kemampuan komputasi yang besar pula. Contohnya jika kita mengunduh data dari Earth Explorer USGS (foto satelit dari GPS)  untuk cakupan suatu kota itu bisa sampai 1 GB. Artinya untuk memproses data ini, kita perlu komputer yang tangguh. Itu baru satu area, bagaimana kalau kita mau menganalisis satu Pulau Jawa misal, Satu Indonesia, atau bahkan satu dunia?

Nah Google Earth Engine ini jawabannya. 

[![Google Earth Engine](https://img.youtube.com/vi/gKGOeTFHnKY/0.jpg)](https://www.youtube.com/watch?v=YgKGOeTFHnKY)

  Google punya akses ke hampir semua data-data satelit yang bisa kita akses gratis. Saking besarnya data yang mereka punya, unit datanya bukan lagi Giga atau Tera, tapi Petabyte, 1 PB = 1000 TB = 1000.000 GB. Earth Engine tidak hanya menyediakan data saja, tapi mereka juga memberi kita peluang untuk menggunakan komputer super Google untuk menganalisis data yang kita inginkan.

Kuncinya cuma satu: kemampuan membuat skrip Python atau Java. Kita bisa membuat skrip ini untuk memerintahkan komputer Google menganalisis data-data yang kita mau.

  Misal studi Tutupan Hutan Global yang dipimpin oleh Matt Hansen dari Universitas Maryland. Mereka menggunakan Google Earth Engine untuk mengetahui perkembangan tutupan hutan di seluruh dunia, baik daerah yang kehilangan tutupan hutan atau daerah yang tutupan hutannya justru bertambah. Studi ini dipublikasikan di Jurnal Science, dan sangat mengagumkan karena bisa menganalisis semua benua, kecuali Antartika dan beberapa pulau di Kutub Utara. Studi ini mencakup area seluas 128.8 juta km2, yang setara dengan 143 miliar piksel data dengan resolusi spasial 30 meter. Ini tidak mungkin bisa dilakukan jika menggunakan komputer biasa. 

![Tutupan Hutan Global](https://1.bp.blogspot.com/-qoiqlcoTnVM/WlO0mk2mnII/AAAAAAAACSw/xXJJv0QBfAw6s9lbYbDvwh-iP-veFsl-QCLcBGAs/s1600/image2.gif)

Peta Perubahan Lanskap Hutan Karya Matt Hansen dkk. <a href="https://ai.googleblog.com/2013/11/the-first-detailed-maps-of-global.html" target="_blank">Sumber</a>

Sumber:
 
 https://developers.google.com/earth-engine
 
 http://www.malikarrahiem.com/google-earth-engine-salah-satu-piranti-lunak-yang-harus-dikuasai-ahli-kebumian/
 
 https://medium.com/@azzadivasawungrana/apa-itu-google-earth-engine-dan-bagaimana-cara-mendaftarnya-gee001-3d248d2194e9
