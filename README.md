# TP4DPBO2025C1

## Janji
Saya Jihan Aqilah Hartono dengan NIM 2306827 mengerjakan Tugas Praktikum 4 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Desain
![tp4 drawio](https://github.com/user-attachments/assets/2eaf0d0b-eb1f-4858-b308-8a3f873ce034)

## Alur Program
### Tampilan Awal (Form Input dan Tabel Data)
Aplikasi ini memiliki antarmuka utama yang berjudul "Data Mahasiswa", yang terdiri dari form input dan tabel data. Form input berisi beberapa field seperti NIM, Nama, Jenis Kelamin, dan Status Mahasiswa. Pengguna dapat mengisi data melalui form ini sebelum disimpan ke dalam daftar mahasiswa. Sementara itu, tabel di bawahnya digunakan untuk menampilkan daftar mahasiswa yang telah tersimpan dalam sistem.

### Proses Menambah Data
Untuk menambahkan data mahasiswa, pengguna harus mengisi NIM, Nama, memilih Jenis Kelamin dari JComboBox, dan menentukan Status Mahasiswa (Aktif atau Non-Aktif) menggunakan JRadioButton. Setelah semua informasi diisi, pengguna menekan tombol "Add". Ketika tombol ditekan, program akan membuat objek baru dari kelas Mahasiswa, menambahkan objek tersebut ke dalam listMahasiswa, lalu memperbarui tampilan tabel (JTable) agar data terbaru muncul dalam daftar.

### Proses Menghapus Data
Jika pengguna ingin menghapus data mahasiswa, mereka dapat memilih salah satu baris pada tabel, lalu menekan tombol "Delete" (yang kemungkinan ada di versi lain dari GUI ini). Setelah tombol ditekan, program akan mengambil indeks data yang dipilih (selectedIndex), menghapus data dari listMahasiswa, dan memperbarui tabel agar data yang telah dihapus tidak lagi muncul dalam daftar.

### Proses Memperbarui Data
Untuk memperbarui data yang sudah ada, pengguna harus memilih salah satu baris dari tabel. Setelah dipilih, data mahasiswa tersebut akan otomatis terisi di form input (JTextField dan JComboBox). Pengguna kemudian dapat mengedit informasi sesuai kebutuhan, lalu menekan tombol "Add" atau "Update". Program akan memperbarui data pada listMahasiswa berdasarkan indeks yang dipilih (selectedIndex) dan memperbarui tabel agar perubahan terlihat secara langsung.

### Proses Membatalkan Input (Cancel)
Jika pengguna ingin menghapus input yang sedang diketik tanpa menyimpannya, mereka dapat menekan tombol "Cancel". Saat tombol ini ditekan, program akan menjalankan metode clearForm(), yang bertugas mengosongkan semua field input sehingga pengguna dapat memasukkan data baru dari awal tanpa terganggu oleh data sebelumnya.

## Dokumentasi
![image](https://github.com/user-attachments/assets/45e3fa19-3ab1-4644-a9a0-411a015bd840)
![image](https://github.com/user-attachments/assets/aefad404-be2c-4130-aea5-357274cc996c)
![image](https://github.com/user-attachments/assets/96eb902a-194f-4053-8239-42c52f08faa1)
![image](https://github.com/user-attachments/assets/4a5851ba-e842-468b-85eb-16b8d003a855)
![image](https://github.com/user-attachments/assets/3b4d60a0-a0c3-4a56-9ff9-97f5982908c8)
![image](https://github.com/user-attachments/assets/f6515254-a185-488e-81a6-690d5c5cca71)



