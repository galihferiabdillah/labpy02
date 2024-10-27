# labpy02
# biodata
# NAMA:MUHAMMAD GALIH FERI ABDILLAH 
# KELAS TI.24.A4
# NIM:312410299
# MATKUL:BAHASA PEMEGROMAN

## LATIHAN 1
### MEMBUAT PROGRAM MENENTUKAN NILAI AKHIR

## DESKRIPSI
Program ini dirancang untuk menghitung nilai akhir mahasiswa berdasarkan beberapa komponen penilaian, seperti nilai UTS (Ujian Tengah Semester), UAS (Ujian Akhir Semester), dan tugas. Program akan menampilkan nilai akhir dan memberikan keterangan mengenai status kelulusan.
- 20% untuk nilai tugas
- 40% untuk nilai UTS
- 40% untuk nilau UAS

Program ini juga menampilkan nilai huruf berdasarkan nilai akhir, serta menentukan apakah siswa "LULUS" atau "TIDAK LULUS" berdasarkan kriteria nilai akhir.

## CARA KERJA PROGRAM

1. Program meminta input dari pengguna untuk nama, nilai UTS, nilai UAS, dan nilai tugas.

2. Program kemudian menghitung nilai akhir dengan rumus:

akhir (nilai_tugas 0.2) + (nilai_uts 0.4) + (nilai_uas 0.4)

3. Setelah nilai akhir dihitung, program menentukan keterangan "LULUS" atau "TIDAK LULUS" dengan syarat

* LULUS jika nilai akhir lebih dari 60.
* TIDAK LULUS jika nilai akhir kurang dari atau sama dengan 60.

4. Program juga mengonversi nilai akhir menjadi nilai huruf dengan kriteria:

* A jika nilai akhir lebih dari 80
* B jika nilai akhir lebih dari 70
* C jika nilai akhir lebih dari 50
* D jika nilai akhir lebih dari 40
* E jika nilai akhir lebih dari atau sama dengan 40

5. Program Kemudian Mencetak hasilnya ke layar

## STRUKTUR PROGRAM

Input:
- Nama siswa
- Nilai UTS (float)
- Nilai UAS (float)
- Nilai Tugas (float)

Output :
- Nama siswa
- Nilai UTS
- Nilai UAS
- Nilai Tugas
- Nilai Akhir
- Nilai Huruf
- Keterangan ("LULUS" atau "TIDAK LULUS")

## BERIKUT HASIL VISUAL CODE
![b](https://github.com/user-attachments/assets/dff50917-c965-4919-a099-b00ace622b60)


## LATIHAAN 2

### MEMBUAT PROGRAM MENAMPILKAN STATUS GAJI KARYAWAN
## DESKRIPSI
Tujuan Program: Program ini dirancang untuk menerima input gaji dari pengguna (karyawan) dan menampilkan status gaji berdasarkan kategori tertentu. Program ini dapat membantu karyawan memahami posisi gaji mereka, apakah termasuk kategori rendah, menengah, atau tinggi.

## CARA KERJA PROGRAM
Program meminta input dari pengguna untuk gaji.

1. Program meminta pengguna untuk memasukkan nama, gaji pokok, dan tunjangan.
2. Jika gaji lebih dari 3.000.000, program akan mencetak "Gaji sudah di atas UMR". Jika tidak, akan mencetak "Gaji belum UMR".
3. Jika pengguna sudah berkeluarga, program akan mencetak "Wajib ikutan asuransi dan menabung untuk pensiun", namun jika belum berkeluarga, akan mencetak "Tidak perlu ikutan asuransi"

## STRUKTUR PROGRAM
- Input
    - Gaji (int)
    - Status berkeluarga (Y/T)
    - Status Kepememilikan (Y/T)
- Output
    - Apakah gaji sudah di atas UMR atau belum
    - Kewajiban mengikuti asuransi jika sudah berkeluarga
    - Kewajiban membayar pajak rumah jika punya rumah

## BERIKUT HASIL VISUAL CODE
![c](https://github.com/user-attachments/assets/6d4d2929-a329-4696-8520-f6f622cd57ef)


## LATIHAAN 3

### PENGGUNAAN KONDISI OR PROGRAM MEMBANDINGKAN 3 INPUT BILANGAN
## DESKRIPSI
Kondisi OR adalah operator logika yang digunakan untuk mengevaluasi dua atau lebih ekspresi kondisi. Dalam bahasa pemrograman Python, operator ini memungkinkan kita untuk memeriksa beberapa kondisi sekaligus. Jika salah satu atau lebih dari kondisi tersebut bernilai True, maka keseluruhan pernyataan akan dianggap True. Sebaliknya, jika semua kondisi bernilai False, maka hasilnya adalah False.Penggunaan kondisi OR sangat berguna dalam berbagai situasi di mana beberapa kondisi perlu dievaluasi. Operator ini memudahkan pengambilan keputusan dalam logika program, sehingga membuat kode menjadi lebih ringkas dan efisien

## CARA KERJA PROGRAM
1. Meminta pengguna untuk memasukkan tiga bilangan: a, b, dan c. Program kemudian memeriksa apakah salah satu dari bilangan tersebut negatif atau sama dengan nol. Jika salah satu dari kondisi ini terpenuhi, program akan memberi tahu pengguna bahwa setidaknya satu bilangan bukan bilangan positif.
2. Memeriksa apakah a, b, atau c negatif.
3. Memeriksa apakah a, b, atau c sama dengan nol. Semua kondisi ini dihubungkan dengan operator or, sehingga jika salah satu kondisi bernilai true, blok kode dalam if akan dijalankan.

## STRUKTUR PROGRAM
Input :
- Masukkan bilangan A
- Masukan bilangan B 
- Masukan bilangan C

Output :
- Benar
- Salah

  ## BERIKUT HASIL VISUAL CODE
  ![d](https://github.com/user-attachments/assets/ea32dac8-04e5-4e64-97f0-93d8f634fd39)

#Latihan 3: Buat program python
 #KASUS 1 PEMESANAN TIKET BIOSKOP
![WhatsApp Image 2024-10-27 at 13 09 13](https://github.com/user-attachments/assets/00e6849a-e746-4139-8f37-36e3c7a4d884)

# KASUS 2 PROGRAM KALKULATOR 
![WhatsApp Image 2024-10-27 at 13 16 47](https://github.com/user-attachments/assets/1daac884-60c4-4320-adad-cd5557067ea9)
