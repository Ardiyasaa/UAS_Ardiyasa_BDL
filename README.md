# UAS_Ardiyasa_BDL

## Database ABsensi Karyawan

1. entity relationship diargram 

  ## penjelasan struktur Table
  
  Komponen Entity Diagram

Entity diagram terdiri dari tiga komponen utama:

Entitas: Entitas adalah objek atau konsep yang ingin disimpan informasinya. Entitas digambarkan dengan persegi panjang.
Atribut: Atribut adalah properti atau karakteristik dari suatu entitas. Atribut digambarkan dengan lingkaran kecil yang terhubung dengan entitas.
Hubungan: Hubungan adalah hubungan antara dua entitas. Hubungan digambarkan dengan garis yang menghubungkan dua entitas.
Penjelasan Entity Diagram pada Gambar

Entity diagram pada gambar menunjukkan hubungan antara tiga entitas:

Karyawan: Entitas ini menyimpan informasi tentang karyawan, seperti nama, NIK, jabatan, dan ID karyawan.
Absensi: Entitas ini menyimpan informasi tentang absensi karyawan, seperti tanggal, jam masuk, jam pulang, dan status absensi.
Gaji: Entitas ini menyimpan informasi tentang gaji karyawan, seperti ID gaji, ID karyawan, gaji pokok, tunjangan, potongan, dan total gaji.
Hubungan antar Entitas

Karyawan-Absensi: Hubungan ini menunjukkan bahwa satu karyawan dapat memiliki banyak absensi. Hubungan ini digambarkan dengan garis yang menghubungkan entitas Karyawan dan Absensi.
Karyawan-Gaji: Hubungan ini menunjukkan bahwa satu karyawan dapat memiliki satu gaji. Hubungan ini digambarkan dengan garis yang menghubungkan entitas Karyawan dan Gaji.
Penjelasan Atribut

ID karyawan: Atribut ini adalah kunci utama dari entitas Karyawan. Atribut ini adalah nilai unik yang digunakan untuk mengidentifikasi setiap karyawan.
Nama: Atribut ini menyimpan nama karyawan.
NIK: Atribut ini menyimpan nomor induk kepegawaian karyawan.
Jabatan: Atribut ini menyimpan jabatan karyawan.
Tanggal: Atribut ini menyimpan tanggal absensi atau tanggal gaji.
Jam masuk: Atribut ini menyimpan jam masuk karyawan.
Jam pulang: Atribut ini menyimpan jam pulang karyawan.
Status absensi: Atribut ini menyimpan status absensi karyawan, seperti "hadir", "sakit", "izin", atau "tanpa keterangan".
Gaji pokok: Atribut ini menyimpan gaji pokok karyawan.
Tunjangan: Atribut ini menyimpan tunjangan karyawan.
Potongan: Atribut ini menyimpan potongan gaji karyawan, seperti pajak penghasilan, BPJS Kesehatan, dan BPJS Ketenagakerjaan.
Total gaji: Atribut ini menyimpan total gaji karyawan yang dihitung dari gaji pokok, tunjangan, dan potongan.
![image](https://github.com/Ardiyasaa/UAS_Ardiyasa_BDL/assets/174011308/76035ef9-77d4-4d10-8027-ab52dbe15085)


2.deskripsi projek dan mekanisme

Karyawan: Entitas ini menyimpan informasi tentang karyawan, seperti nama, NIK, jabatan, dan ID karyawan.
Absensi: Entitas ini menyimpan informasi tentang absensi karyawan, seperti tanggal, jam masuk, jam pulang, dan status absensi.
Gaji: Entitas ini menyimpan informasi tentang gaji karyawan, seperti ID gaji, ID karyawan, gaji pokok, tunjangan, potongan, dan total gaji.
Hubungan antar Entitas

Karyawan-Absensi: Hubungan ini menunjukkan bahwa satu karyawan dapat memiliki banyak absensi. Hubungan ini digambarkan dengan garis yang menghubungkan entitas Karyawan dan Absensi.
Karyawan-Gaji: Hubungan ini menunjukkan bahwa satu karyawan dapat memiliki satu gaji. Hubungan ini digambarkan dengan garis yang menghubungkan entitas Karyawan dan Gaji.

penjelasan trigger dan view

![image](https://github.com/Ardiyasaa/UAS_Ardiyasa_BDL/assets/174011308/df919b94-f096-4fb9-bd02-5551f2db245d)

Entitas:

Karyawan: Entitas ini menyimpan informasi tentang karyawan, seperti nama, NIK, jabatan, dan ID karyawan.
Absensi: Entitas ini menyimpan informasi tentang absensi karyawan, seperti tanggal, jam masuk, jam pulang, dan status absensi.
Hubungan:

Karyawan-Absensi: Hubungan ini menunjukkan bahwa satu karyawan dapat memiliki banyak absensi. Hubungan ini digambarkan dengan garis yang menghubungkan entitas Karyawan dan Absensi.
Atribut:

Entitas Karyawan:

ID karyawan: Kunci utama dari entitas Karyawan.
Nama: Nama karyawan.
NIK: Nomor induk kepegawaian karyawan.
Jabatan: Jabatan karyawan.
Entitas Absensi:

ID absensi: Kunci utama dari entitas Absensi.
ID karyawan: Kunci asing yang merujuk ke entitas Karyawan.
Tanggal: Tanggal absensi.
Jam masuk: Jam masuk karyawan.
Jam pulang: Jam pulang karyawan.
Status absensi: Status absensi karyawan, seperti "hadir", "sakit", "izin", atau "tanpa keterangan".

penjelasan view
![image](https://github.com/Ardiyasaa/UAS_Ardiyasa_BDL/assets/174011308/604fcac3-3df0-4ddf-9430-b709624c903e)

Entitas:

Karyawan: Entitas ini menyimpan informasi tentang karyawan, seperti nama, NIK, jabatan, dan ID karyawan.
Absensi: Entitas ini menyimpan informasi tentang absensi karyawan, seperti tanggal, jam masuk, jam pulang, dan status absensi.
Gaji: Entitas ini menyimpan informasi tentang gaji karyawan, seperti ID gaji, ID karyawan, gaji pokok, tunjangan, potongan, dan total gaji.
Hubungan:

Karyawan-Absensi: Hubungan ini menunjukkan bahwa satu karyawan dapat memiliki banyak absensi. Hubungan ini digambarkan dengan garis yang menghubungkan entitas Karyawan dan Absensi.
Karyawan-Gaji: Hubungan ini menunjukkan bahwa satu karyawan dapat memiliki satu gaji. Hubungan ini digambarkan dengan garis yang menghubungkan entitas Karyawan dan Gaji.
Atribut:

Entitas Karyawan:

ID karyawan: Kunci utama dari entitas Karyawan.
Nama: Nama karyawan.
NIK: Nomor induk kepegawaian karyawan.
Jabatan: Jabatan karyawan.
Entitas Absensi:

ID absensi: Kunci utama dari entitas Absensi.
ID karyawan: Kunci asing yang merujuk ke entitas Karyawan.
Tanggal: Tanggal absensi.
Jam masuk: Jam masuk karyawan.
Jam pulang: Jam pulang karyawan.
Status absensi: Status absensi karyawan, seperti "hadir", "sakit", "izin", atau "tanpa keterangan".
Entitas Gaji:

ID gaji: Kunci utama dari entitas Gaji.
ID karyawan: Kunci asing yang merujuk ke entitas Karyawan.
Gaji pokok: Gaji pokok karyawan.
Tunjangan: Tunjangan karyawan.
Potongan: Potongan gaji karyawan, seperti pajak penghasilan, BPJS Kesehatan, dan BPJS Ketenagakerjaan.
Total gaji: Total gaji karyawan yang dihitung dari gaji pokok, tunjangan, dan potongan.
Penjelasan Lebih Lanjut:

Normalisasi: Diagram entitas ini telah dinormalisasi menjadi tiga tabel: Karyawan, Absensi, dan Gaji. Normalisasi membantu untuk meningkatkan integritas data dan mengurangi redundansi data.
Kunci asing: Diagram entitas ini menggunakan kunci asing untuk menghubungkan entitas Karyawan dan Absensi, serta entitas Karyawan dan Gaji. Kunci asing membantu untuk menegakkan hubungan antara tabel dan memastikan integritas data.
Indeks: Diagram entitas ini tidak menunjukkan indeks. Indeks adalah struktur data yang membantu untuk mempercepat pencarian data dalam database.
Rekomendasi:

Tambahkan atribut lain yang mungkin diperlukan, seperti jenis absensi (sakit, izin, dinas luar, dll.).
Tambahkan catatan tentang aturan bisnis yang terkait dengan absensi dan gaji, seperti kebijakan cuti dan izin, serta perhitungan gaji.


