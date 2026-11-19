# Proposal-Proyek-TAXSTNK-DKI
1. Analisis Sistem
Sistem Penghitungan Pajak dan Tunggakan Kendaraan Bermotor Berbasis Aplikasi merupakan aplikasi yang membantu pemilik kendaraan mengetahui perkiraan jumlah pajak kendaraan yang harus dibayar, termasuk tunggakan dan denda apabila terjadi keterlambatan pembayaran. Sistem juga menyediakan fitur pengelolaan data dan aturan perhitungan oleh admin.
2. Tujuan Sistem
•	Memudahkan pemilik kendaraan memasukkan dan memeriksa data kendaraannya.
•	Menghitung pajak kendaraan berdasarkan data dan tarif yang tersedia.
•	Menghitung tunggakan serta denda keterlambatan sesuai aturan yang dimasukkan ke sistem.
•	Menampilkan dan mencetak hasil perhitungan sebagai informasi bagi pengguna.
•	Membantu admin mengelola data kendaraan, tarif pajak, aturan denda, pengguna, dan laporan.



TUGAS 1: PROPOSAL PROYEK TAXSTNK-DKI
1. Nama Proyek
TaxSTNK-DKI - Aplikasi Kalkulator & Estimasi Denda Pajak Kendaraan Bermotor Wilayah DKI Jakarta Berbasis OCR Scan STNK.
2. Latar Belakang
Setiap pemilik kendaraan bermotor di wilayah DKI Jakarta memiliki kewajiban membayar Pajak Kendaraan Bermotor (PKB) dan Sumbangan Wajib Dana Kecelakaan Lalu Lintas Jalan (SWDKLLJ) setiap tahunnya. Namun, banyak pemilik kendaraan yang terlambat membayar pajak karena tidak menyadari batas masa berlaku STNK, kehilangan rincian perhitungan, atau kebingungan menghitung berapa besar denda keterlambatan yang harus dibayar saat terlambat beberapa bulan hingga tahun.
Saat ini, masyarakat harus menghitung secara manual atau melakukan simulasi rumit berdasarkan variabel PKB, NJKB, tarif progresif, denda PKB (1% per bulan sesuai Perda DKI No. 1 Tahun 2024), denda SWDKLLJ (sesuai Peraturan PMK No. 16/PMK.010/2017), serta biaya administrasi TNKB/STNK jika memasuki siklus ganti plat 5 tahunan.
Pengguna kerap kali kesulitan membaca lembar Pajak STNK yang memuat angka-angka kecil dan istilah teknis (PKB, SWDKLLJ, BBN-KB). Oleh karena itu, diperlukan sistem berbasis Optical Character Recognition (OCR) yang mampu mengekstrak data dari foto STNK secara otomatis, menganalisis status jatuh tempo, serta menghitung estimasi tagihan pajak berjalan beserta denda keterlambatannya secara akurat khusus untuk wilayah DKI Jakarta.
3. Permasalahan
1.	Pemilik kendaraan kesulitan menghitung secara pasti akumulasi denda keterlambatan pajak (PKB & SWDKLLJ) ketika masa berlaku STNK sudah terlewat, sehingga sering mengalami ketidakpastian besaran biaya yang harus disiapkan saat hendak membayar di SAMSAT/SAMSAT Online.
2.	Proses input data kendaraan secara manual (memasukkan Nilai Jual / PKB / Tanggal Jatuh Tempo) rentan terjadi kesalahan (human error) dan memakan waktu.
3.	Ketidakpahaman masyarakat mengenai komponen denda terpisah, yaitu denda keterlambatan PKB (sanksi administratif 1% per bulan) dan sanksi denda SWDKLLJ (Sumbangan Wajib Jasa Raharja), serta biaya administrasi tambahan (Penerimaan Negara Bukan Pajak / PNBP) jika memasuki periode perpanjangan STNK 5 tahunan.
4. Tujuan Sistem
1.	Menyediakan fitur pemindaian foto STNK berbasis OCR yang dapat mengekstrak data penting secara otomatis (seperti Nopol, PKB pokok, SWDKLLJ pokok, dan Tanggal Jatuh Tempo Pajak).
2.	Membangun mesin kalkulator pajak otomatis khusus tarif wilayah DKI Jakarta yang secara akurat menghitung:
o	Pokok PKB & SWDKLLJ berjalan.
o	Denda Keterlambatan PKB (1% per bulan keterlambatan, maksimal 24 bulan).
o	Denda Keterlambatan SWDKLLJ (Sanksi denda bertingkat/maksimal Rp100.000 untuk mobil dan Rp32.000 untuk motor sesuai ketentuan Jasa Raharja).
o	Estimasi tambahan biaya PNBP (STNK & TNKB) jika jatuh tempo bertepatan dengan periode 5 tahunan.
3.	Memberikan ringkasan/rincian transparan mengenai akumulasi total tagihan yang harus dibayar beserta status keterlambatan (jumlah hari/bulan terlambat).
4.	Menyediakan fitur pencetakan/ekspor laporan simulasi perhitungan pajak dalam bentuk PDF agar pengguna dapat menyimpannya sebagai rujukan sebelum melakukan pembayaran.
