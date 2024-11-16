# praktikum-6
# Penjelasan Program
## Fungsi `hitung_nilai_akhir`
- Fungsi ini menerima tiga parameter: `nilai_tugas`, `nilai_uts`, dan `nilai_uas`.
- Nilai akhir dihitung dengan rumus: 
- Fungsi mengembalikan nilai akhir yang telah dihitung.

## Inisialisasi Data Mahasiswa
- Sebuah list kosong `data_mahasiswa` dibuat untuk menyimpan data mahasiswa yang dimasukkan.

## Loop Input Data
- Program memasuki loop yang terus meminta input dari pengguna hingga pengguna memutuskan untuk berhenti.
- Di dalam loop:
  - Pengguna diminta untuk memasukkan nama, NIM, dan nilai untuk tugas, UTS, dan UAS.
  - Nilai akhir dihitung menggunakan fungsi `hitung_nilai_akhir`.
  - Data mahasiswa disimpan dalam bentuk dictionary dan ditambahkan ke list `data_mahasiswa`.
  - Program menanyakan kepada pengguna apakah ingin menambah data mahasiswa lagi.

## Menampilkan Daftar Mahasiswa
- Setelah pengguna memilih untuk tidak menambah data, program menampilkan daftar semua mahasiswa yang telah dimasukkan.
- Tabel ditampilkan dengan format yang rapi, menunjukkan nomor urut, nama, NIM, nilai tugas, nilai UTS, nilai UAS, dan nilai akhir.

# Flowchart Program

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

## Flowchart Visual

Berikut adalah representasi flowchart dalam teks:


