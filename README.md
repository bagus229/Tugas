# Tugas Praktikum
## Kode Progrsm Nilai Akhir Dan Flowchartnya

## Kode Program Nilai Akhir

### Langkah 1
Analisis data mahasiswa yang berisi nama mahasiswa, nilai tugas, nilai UTS, nilai UAS, dan nilai akhir. lalu simpan pada list:
![Gambar 1](screenshot/pol1.png)

### Langkah 2
Menggunakan while untuk mengulang input data mahasiswa sampai pengguna memilih untuk berhenti.
~nama: untuk input nama mahasiswa.
~nim: program akan menginput nim mahasiswa.
~tugas: program menginput nilai tugas mahasiswa.
~uts: input nilai UTS mahasiswa yang nanti diubah dalam bentuk float.
~uas: input untuk nilai UAS diubah dalam bentuk float.:
![Gambar 1](screenshot/pol2.png)

### Langkah 3
Kemudian setelah menginput nilai tugas,UTS,dan UAS. program akan menghitung nilai akhir dengan keetentuan sebaagi berikut;
~30% untuk tugas.
~35% untuk UTS.
~35% untuk UAS.:
![Gambar 1](screenshot/pol3.png)

### Langkah 4
Data mahasiswa yang tadi diinput, akan disimpan dalam bentuk dictionary yang berisi: 'nama', 'tugas', 'uts', 'uas', dan 'nilai_akhir'. lalu akan ditambahkan kedalam list data_mahasiswa:
![Gambar 1](screenshot/pol4.png)

### Langkah 5
Setelah data dimasukkan, program akan menanyakan apakah pengguna ingin menambah data lagi dengan memberikan dua pilihan "y" untuk ya dan "t" untuk tidak. Jika pengguna memilih "t", maka program akan berhenti dan melanjutkan ke bagian berikutnya:
![Gambar 1](screenshot/pol5.png)

### Langkah 6
Program akan mencetak dan menampilkan data mahasiswa yang telah diinput. tampilan berisi nama,nim,tugas,UTS,UAS,dan nilai akhir:
![Gambar 1](screenshot/pol6.png)

### Langkah 7
program melakukan loop melalui setiap data mahasiswa yang ada di dalam data_mahasiswa. Setiap item mhs adalah dictionary yang berisi informasi tentang mahasiswa. Data ditampilkan:nama,nim,tugas,UTS,UAS,dan nilai akhir. lalu print:
![Gambar 1](screenshot/pol7.png)

### Hasil Program
![Gambar 1](screenshot/pol8.png)
![Gambar 1](screenshot/pol9.png)

## Flowchart

### Langkah 1
Start: Program dimulai:
![Gambar 1](screenshot/pol10.png)

### Langkah 2
Inisialisasi Data Mahasiswa, Program menginisialisasi struktur data (misalnya list data_mahasiswa kosong) untuk menyimpan data mahasiswa yang akan diinput:
![Gambar 1](screenshot/pol11.png)

### Langkah 3
Input Data Mahasiswa, User diminta memasukkan data mahasiswa, yaitu nama, nim, tugas, uts, dan uas:
![Gambar 1](screenshot/pol12.png)

### Langkah 4
if menambahkan data (y/t)?, Program meminta kepada user apakah ingin menambah data mahasiswa lagi. Jika user menjawab "Ya", program kembali ke langkah Input Data Mahasiswa untuk memasukkan data baru. Jika user menjawab "Tidak", program melanjutkan ke langkah berikutnya:
![Gambar 1](screenshot/pol13.png)

### Langkah 5
Hitung Nilai Akhir, Program menghitung nilai_akhir dengan ketentuan; tugas 30%, UTS 35%, UAS 35%:
![Gambar 1](screenshot/pol14.png)

### Langkah 6
Output nilai akhir, Program menampilkan nilai akhir dari data mahasiswa yang telah diinput:
![Gambar 1](screenshot/pol15.png)

### Langkah 7
Finish: program selesa:
![Gambar 1](screenshot/pol16.png)