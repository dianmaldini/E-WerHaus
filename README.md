E-WerHaus

E-WerHaus adalah solusi perangkat lunak desktop yang dirancang untuk memodernisasi dan menyederhanakan proses manajemen stok gudang. Aplikasi ini dikembangkan menggunakan bahasa pemrograman Python, menawarkan antarmuka pengguna (GUI) yang estetis dan intuitif tanpa mengorbankan fungsionalitas.

Keunggulan utama E-WerHaus terletak pada integrasi basis datanya. Aplikasi ini meniadakan kebutuhan akan server SQL yang kompleks dengan menggunakan Microsoft Excel (.xlsx) sebagai media penyimpanan data utama. Pendekatan ini memastikan data tetap mudah diakses, portabel, dan kompatibel dengan format laporan standar industri.

Fitur Utama

Manajemen Inventaris End-to-End: Mendukung siklus penuh pengelolaan data barang, termasuk penambahan stok baru, pemantauan daftar barang, pembaruan informasi (Edit), dan penghapusan data (Delete).

Integrasi Excel Otomatis: Seluruh input data disimpan dan disinkronisasi secara otomatis ke dalam file Excel lokal. Jika file database belum tersedia, sistem akan membuatnya secara otomatis.

Pencarian Cerdas: Dilengkapi dengan fitur pencarian responsif untuk memfilter dan menemukan item spesifik berdasarkan nama barang di dalam database yang besar.

Antarmuka Pengguna Modern: Dibangun menggunakan pustaka CustomTkinter untuk menghadirkan pengalaman visual yang bersih, profesional, dan nyaman di mata dengan dukungan mode gelap (Dark Mode).

Validasi & Keamanan Data: Menyertakan mekanisme konfirmasi sebelum penghapusan data dan validasi input untuk mencegah kesalahan pencatatan.

Teknologi yang Digunakan

Bahasa Pemrograman: Python 3.x

Antarmuka Pengguna (GUI): CustomTkinter, Tkinter (Treeview)

Manajemen Data: OpenPyXL

Instalasi dan Penggunaan

Pastikan Python telah terinstal di perangkat Anda. Instal dependensi yang diperlukan melalui terminal:

pip install customtkinter openpyxl

Jalankan aplikasi dengan perintah:

python inventory.py

Hak Cipta

Copyright (c) Albani Computer. Seluruh hak cipta dilindungi undang-undang.