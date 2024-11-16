# Salsabila NIM : 352310495
# LAPORAN PRAKTIKUM 6


## Fungsi `hitung_nilai_akhir`
- Fungsi ini menerima tiga parameter: `nilai_tugas`, `nilai_uts`, dan `nilai_uas`. Berikut perintah programnya :

![fungsi nilai akhir](https://github.com/user-attachments/assets/a587b4c4-84cc-42f8-adf8-c773412a2c68)

- Nilai akhir dihitung dengan rumus:
  
![rumus tugas akhir](https://github.com/user-attachments/assets/c6a616f8-2325-4924-b27b-828b0de83d08)


- Fungsi mengembalikan nilai akhir yang telah dihitung.
  

## Inisialisasi Data Mahasiswa
- Sebuah list kosong `data_mahasiswa` dibuat untuk menyimpan data mahasiswa yang dimasukkan.

![daftar nama siswa](https://github.com/user-attachments/assets/e8d77908-cd3f-4bec-a6f6-bff18052611b)

## Loop Input Data
- Program memasuki loop yang terus meminta input dari pengguna hingga pengguna memutuskan untuk berhenti.
- Di dalam loop:
  - Pengguna diminta untuk memasukkan nama, NIM, dan nilai untuk tugas, UTS, dan UAS. Berikut perintah programnya :
    
    ![meminta input pengguna](https://github.com/user-attachments/assets/5745dd61-61b0-44ba-af49-58bde1f93309)
  - Nilai akhir dihitung menggunakan fungsi `hitung_nilai_akhir`. Berikut perintah programnya :

    ![hitung nilai akhir](https://github.com/user-attachments/assets/b648a135-e95d-41a1-b46b-769f323c0d1d)

  - Data mahasiswa disimpan dalam bentuk dictionary dan ditambahkan ke list `data_mahasiswa`. Seperti ini perintah programannya :

    ![simpan data ke list](https://github.com/user-attachments/assets/469ff434-0f3e-4175-bced-fdbd0d27008e)
  - Program menanyakan kepada pengguna apakah ingin menambah data mahasiswa lagi. Maka, perintah programnya seperti ini :

    ![opsi y or no](https://github.com/user-attachments/assets/1e7b4492-f902-494c-843c-5e715e6c14bf)


## Menampilkan Daftar Mahasiswa
- Setelah pengguna memilih untuk tidak menambah data, program menampilkan daftar semua mahasiswa yang telah dimasukkan.

  ![tampilan daftar tabel](https://github.com/user-attachments/assets/cb920b95-c545-4021-9422-7db085ef43af)

- Tabel ditampilkan dengan format yang rapi, menunjukkan nomor urut, nama, NIM, nilai tugas, nilai UTS, nilai UAS, dan nilai akhir.

  
![tampilan akhir tabel](https://github.com/user-attachments/assets/5b26eabc-9e4a-47cc-b479-2d63ba279006)

## Flowchart Program

Berikut adalah gambar flowchartnya : 

![program phyton](https://github.com/user-attachments/assets/58ce83e4-6b86-4c25-a3c7-ed5d6cb21f42)


Berikut adalah deskripsi flowchart program:

1. **Start**
2. **Inisialisasi list `data_mahasiswa`**
3. **Input Data Mahasiswa** (Nama, NIM, Nilai Tugas, Nilai UTS, Nilai UAS)
4. **Hitung Nilai Akhir** menggunakan fungsi `hitung_nilai_akhir`
5. **Simpan Data** ke dalam list `data_mahasiswa`
6. **Tanya Pengguna**: "Tambah data (y/t)?"
   - Jika **y**: Kembali ke langkah 3
   - Jika **t**: Lanjut ke langkah 7
7. **Tampilkan Daftar Mahasiswa**
8. **End**



