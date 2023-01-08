## Nama: Rini Ariza
## Nim: 312210337
## Kelas:  TI.22.A3
# UAS
# PACKAGE & MODULE
**saya di beri tugas UAS ini  dengan struktur seperti sebagai berikut:**

![soal uas](https://user-images.githubusercontent.com/93035757/149618916-d7707552-7229-4def-930f-5a706dd00ac1.png)
 
* ``daftar_nilai.py`` berisi modul untuk  :
    * tambah_data
    * ubah_data
    * hapus_data
    * cari_data 
* ``view_nilai.py`` berisi modul untuk : 
    * cetak_daftar_nilai 
    * cetak_hasil_pencarian
* ``input_nilai.py`` berisi modul untuk :
    * input_data (yang meminta pengguna memasukkan data).
* ``main.py`` berisi program utama (menu pilihan yang memanggil semua menu yang ada).

* hasil package yang saya buat sebagai berikut :

<img width="232" alt="m6" src="https://user-images.githubusercontent.com/115542704/210501105-4bef13cb-9371-4df1-9482-431a33f11b31.png">

* pertama saya telah menyantumkan beberapa syntax yang nantinya akan menghasilkan semua modul dari package Daftar_Nilai yang diantaranya adalah (Tambah Data, Ubah Data, Hapus Data, Dan Cari Data)

```py

from view.input_nilai import *
data={}
class daftarnilai():
    def tambah_data(self):
        tambah_nama = nama()
        tambah_nim = nim()
        tambah_tugas = tugas()
        tambah_uts = uts()
        tambah_uas = uas()
        tambah_akhir = akhir()
        data[tambah_nama]= tambah_nim,tambah_tugas,tambah_uts,tambah_uas,tambah_akhir

    def ubah_data(self):
        ubah_nama = nama()
        if ubah_nama in data.keys():
           
            tambah_nim = nim()
            tambah_tugas = tugas()
            tambah_uts = uts()
            tambah_uas = uas()
            tambah_akhir = akhir()
            data[ubah_nama]= tambah_nim,tambah_tugas,tambah_uts,tambah_uas,tambah_akhir
        else:
            print('data tidak ditemukan !!!')

    def hapus_data(self):
        hapus_nama = nama()
        if hapus_nama in data.keys():
            del data[hapus_nama]
            print('data berhasil di hapus')
        else:
            print('data tidak ditemukan !!!')

    def keluar(self):
    
```

* **Output tambah_data**
  
<img width="203" alt="m1" src="https://user-images.githubusercontent.com/115542704/210501852-6c0de477-7e6e-4afe-9dd4-8a14c46984ce.png">

* **Output daftar_nilai**

<img width="425" alt="m5(3)" src="https://user-images.githubusercontent.com/115542704/210504987-76f5cec4-07fc-4be3-beec-7649eb398e40.png">

* **Output ubah_data**

<img width="209" alt="m2" src="https://user-images.githubusercontent.com/115542704/210503236-9e4b13d2-f2d0-4a5c-aa58-0733ba466a51.png">

<img width="417" alt="m5(1)" src="https://user-images.githubusercontent.com/115542704/210503309-f5e46aea-bb09-48f4-82c6-d5a5272500a5.png">

* **Output Cari_data**

<img width="383" alt="m3" src="https://user-images.githubusercontent.com/115542704/210503527-1fffb18e-086e-4038-ad18-96a1c27c74a5.png">

* **Output Hapus_data**

<img width="176" alt="m4" src="https://user-images.githubusercontent.com/115542704/210504125-0daa09f3-695e-49f4-b739-428bdf0a973e.png">

<img width="416" alt="m5(2)" src="https://user-images.githubusercontent.com/115542704/210504161-8b409cec-37b7-42bc-916f-731194d264e9.png">

# SELESAI
