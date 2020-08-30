PENGADAAN PERANGKAT LUNAK ELECTRONIC CORRESPONDENCE DAN MAINTENANCE PT.
PERTAMINA EP CEPU (PEPC) SELAMA 36 (TIGA PULUH ENAM) BULAN

  **User Manual**
  -----------------
  Version \# 1.0

Disiapkan untuk:

![Lowongan Kerja di PT Pertamina EP Cepu - Maret 2020 \|
Urbanhire](.//media/image1.jpg){width="1.75625in"
height="0.8520833333333333in"}

**PT. PERTAMINA EP CEPU (PEPC)**

Disiapkan oleh:

![PT SIGMA CIPTA UTAMA (\@SIGMA_SCU) \|
Twitter](.//media/image2.jpg){width="1.3736111111111111in"
height="1.3736111111111111in"}

**PT. SIGMA CIPTA UTAMA**

GRAHA ELNUSA

Jl. TB. Simatupang KAV 1B, 2nd floor, Jakarta\
Phone (62-21) 7883 0859\| Fax. (62-21) 7883 0857

DAFTAR ISI
==========

[DAFTAR ISI i](#daftar-isi)

[Kontrol Dokumen ii](#section)

[Riwayat Dokumen ii](#riwayat-dokumen)

[Distribusi Dokumen ii](#distribusi-dokumen)

[Persetujuan Dokumen](#persetujuan-dokumen)

[1. Pendahuluan 1](#pendahuluan)

[1.1. Tujuan Pembuatan Dokumen 1](#tujuan-pembuatan-dokumen)

[1.2. Deskripsi Umum Sistem 3](#deskripsi-umum-sistem)

[2. Sumber Daya Yang Dibutuhkan 3](#sumber-daya-yang-dibutuhkan)

[2.1. Perangkat Lunak 3](#perangkat-lunak)

[2.2. Perangkat Keras 4](#perangkat-keras)

[2.3. Sumber Daya Manusia 4](#sumber-daya-manusia)

[3. Menu dan Cara Penggunaan 5](#menu-dan-cara-penggunaan)

[3.1. Struktur Menu 5](#struktur-menu)

[3.2. Penggunaan 7](#penggunaan)

[3.2.1. Login 7](#login)

[3.2.2. Surat Masuk 8](#surat-masuk)

[3.2.3. Surat Keluar 32](#surat-keluar)

[3.2.4. Memorandum 59](#memorandum)

[3.2.5. Fax Masuk 101](#fax-masuk)

[3.2.6. Fax Keluar 126](#fax-keluar)

[3.2.7. SP3S 151](#sp3s)

[3.2.8. SPPTH 175](#sppth)

[3.2.9. Archive 198](#archive)

[3.2.10. Agenda Kendali 202](#_Toc40777479)

Kontrol Dokumen
===============

Riwayat Dokumen
---------------

  Penulis              Tanggal       Versi   Referensi Perubahan
  -------------------- ------------- ------- ---------------------
  Tri Widia Rosalina   5 Mei 2020    V 1.0   \-
  Tri Widia Rosalina   2 Juni 2020   V 2.0   \-
  Tri Widia Rosalina   1 Juli 2020   V 3.0   

Distribusi Dokumen
------------------

  \#of Copy   Deskripsi   Lokasi
  ----------- ----------- --------
                          
                          
                          
                          
                          

Persetujuan Dokumen
-------------------

PT. Pertamina EP Cepu (PEPC)

  Nama           Peran Projek   Tanggal   Tanda Tangan
  -------------- -------------- --------- --------------
  Ellen Tanida                            
                                          
                                          
                                          
                                          

PT. Sigma Cipta Utama

  Nama                  Peran Projek              Tanggal   Tanda Tangan
  --------------------- ------------------------- --------- --------------------------------------------------------------------------------------
  Rusmin                Instalasi & Konfigurasi             ![](.//media/image3.png){width="1.1527777777777777in" height="0.5506944444444445in"}
  Mega Putri Islamiah   Sistem Analis                       ![](.//media/image4.png){width="0.6057917760279965in" height="0.7630643044619423in"}
                                                            
                                                            
                                                            

1.  Pendahuluan
    ===========

    1.  Tujuan Pembuatan Dokumen
        ------------------------

> Pada bagian ini akan dijelaskan mengenai tujuan pembuatan dokumen
> *user* manual aplikasi E-Correspondence antara lain sebagai berikut:

1.  Tujuan utama pengadaan perangkat lunak:

```{=html}
<!-- -->
```
a.  Dalam kegiatan surat menyurat PT. Pertamina EP Cepu saat ini masih
    dilakukan secara manual dan menggunakan media kertas. Kegiatan
    end-to-end surat menyurat organisasi mulai dari proses pembuatan,
    pengiriman, penerimaan, disposisi dan penyimpanan memo/surat resmi
    organisasi dilakukan secara manual sehingga kegiatan surat menyurat
    membutuhkan waktu yang relatif lama, tingkat keamanan data yang
    kurang terjamin dan proses pengelolaan berkas memo/surat keluar
    maupun masuk membutuhkan waktu lama, membutuhkan ruang penyimpanan
    fisik surat dan tidak sejalan dengan program Go Green dalam
    penggunaan kertas

b.  Adanya kebutuhan perangkat lunak korespondensi sebagai perangkat
    lunak utama dalam melakukan kegiatan surat-menyurat internal
    organisasi, manajemen data historis surat organisasi, dan integrasi
    data pengguna dengan data struktur organisasi. Hal ini sangat
    mendukung kegiatan surat menyurat resmi secara efektif dan efisien
    serta mendukung program Go Green PT. Pertamina EP Cepu dengan
    mengurangi penggunaan kertas untuk kegiatan surat menyurat internal
    organisasi.

c.  Adanya kebutuhan perangkat lunak untuk meningkatkan keamanan data
    yang bersifat rahasia dalam kegiatan surat menyurat organisasi dan
    kemudahaan dalam melakukan proses disposisi surat kepada subordinat
    masing-masing atau kepada pekerja yang bersesuaian.

d.  Adanya kebutuhan perangkat lunak untuk melakukan pembuatan Surat
    Penunjukan Pejabat Pengganti Sementara (SP3S) dan Surat Penunjukan
    Pelaksana Tugas Harian (SPPTH) secara *online* sehingga memudahkan
    dalam pengelolaan dan intergrasi dengan surat-menyurat organisasi.

```{=html}
<!-- -->
```
2.  Selain itu aplikasi E-Correspodence diharapkan dapat memudahkan
    *user* yang terlibat dalam melakukan kegiatan surat menyurat
    organisasi mulai dari proses pembuatan, pengiriman, penerimaan,
    disposisi dan penyimpanan surat secara digital.

> Pihak -- pihak yang berkepentingan dan berhak menggunakan dokumen ini
> yaitu:

a.  Sekretaris

Sekretaris adalah seorang pekerja yang diberi wewenang untuk mengelola
surat masuk dan fax masuk kemudian sekretaris menginputkan surat yang
diterima dalam bentuk fisik ke dalam aplikasi yang kemudian dikirimkan
ke pejabat tujuan. Sekretaris dapat mengelola SP3S dan SPPTH jika diberi
wewenang untuk mengelolanya. Sekretaris juga dapat mengelola menu
Document Control (Agenda Kendali) yang didalamnya dapat melakukan
pengajuann nomor offline, pengembalian nomor offline, mengelola dokumen
masuk, dokumen keluar dan dokumen disposisi milik atasan pejabatnya

b.  Konseptor

Konseptor adalah staff atau pejabat yang diberi wewenang untuk membuat
surat keluar, memorandum dan fax keluar yang kemudian dikirimkan ke
reviewer. Konseptor diberi kewenangan dalam menjalankan perintah
disposisi dari atasan pejabat

c.  Reviewer

Reviewer adalah pejabat yang diberi kewenangan dalam melakukan review
surat keluar, memorandum dan fax keluar yang dikirimkan oleh konseptor
kemudian reviewer mengirimkan surat yang sudah direview kepada approver
atau atasan pejabatnya

d.  Approver

Approver/pemilik KBO adalah pejabat yang diberi kewenangan untuk
melakukan approval surat keluar, memorandum dan fax keluar. Nomor surat
atau memo yang sudah disetujui akan otomatis tergenerate berdasarkan
format surat dan nomor KBO

e.  Admin E-Corr

Admin E-Corr atau suatu fungsi yang memiliki kewenangan dalam
pengelolaan tindak lanjut pengajuann nomor offline

f.  Administator Sistem

Administrator sistem adalah *user* yang dapat mengelola menu master yang
digunakan pada form input surat serta melakukan mapping sekretaris
kepada atasan pejabatnya. Administrator sistem juga dapat mengelola menu
konfigurasi yang mengelola informasi *user*, jabatan dan unit kerja
serta dapat mengelola notifikasi email kepada *user*

Deskripsi Umum Sistem
---------------------

> Electronic Correspondence (E-Corr) merupakan sistem korespondensi yang
> mampu mengotomatiskan proses surat menyurat mencakup surat masuk,
> memorandum, surat keluar, fax masuk, fax keluar, SP3S, SPPTH dan
> pengelolaan dokumen serta melakukan distribusi surat kepada tujuan
> secara tepat. Selain itu aplikasi E-Correspodence diharapkan dapat
> memudahkan mulai dari proses pembuatan, pengiriman, penerimaan,
> disposisi dan penyimpanan surat secara digital.

2.  Sumber Daya Yang Dibutuhkan
    ===========================

    1.  Perangkat Lunak
        ---------------

> Pada bagian ini akan ditampilkan tabel yang mencantumkan perangkat
> lunak yang dianjurkan ketika menjalankan aplikasi P-Office antara lain
> sebagai berikut:

+------------------+------------------------------------------+
|                  | Contoh                                   |
+==================+==========================================+
| Operating System | -   Windows 10 (versi 64-bit dan 32-bit) |
|                  |                                          |
|                  | -   Mac OS Intel 10.12 -- 10.15          |
+------------------+------------------------------------------+
| Browser          | -   Chrome Version 81.0.4044.129         |
|                  |                                          |
|                  | -   Microsoft Edge Version 81.0.416.68   |
|                  |                                          |
|                  | -   Mozilla Firefox 76.0 (64-bit)        |
|                  |                                          |
|                  | -   Opera Version: 68.0.3618.63          |
+------------------+------------------------------------------+
| Editor           | -   Microsoft Office 2019                |
|                  |                                          |
|                  | -   Adobe Reader                         |
+------------------+------------------------------------------+

Perangkat Keras
---------------

> Pada bagian ini akan ditampilkan tabel yang mencantumkan perangkat
> keras yang dianjurkan ketika menjalankan aplikasi P-Office antara lain
> sebagai berikut:

              Contoh
  ----------- --------------------------------------
  Processor   x86 atau x64-bit
  Memori      2 GB RAM atau lebih
  Tampilan    Super VGA dengan resolusi 1024 x 768

Sumber Daya Manusia
-------------------

> Pada bagian ini akan ditampilkan tabel yang mencantumkan actor dan
> role siapa saja yang terlibat dalam workflow aplikasi P-Office antara
> lain sebagai berikut:

  Actor                                Role
  ------------------------------------ ------------------------------------------------------------------------------------------------------------------
  Admin P-Office/Unit Kerja Tertentu   Melakukan tindak lanjut pengajuann *request* nomor offline
  Administrator Sistem                 Mengelola menu Konfigurasi dan Master pada aplikasi
  Sekretaris                           Membuat konsep surat masuk, fax masuk, SP3S dan SPPTH serta melakukan pengelolaan terhadap menu Document Control
  Konseptor                            Membuat konsep surat masuk, memorandum, surat keluar, fax masuk, fax keluar, SP3S dan SPPTH
  Reviewer                             Memeriksa konsep surat dan melakukan *update* terhadap surat
  Approver                             Menyetujui konsep yang sudah direview dan mengirimkan kepejabat tujuan

3.  Menu dan Cara Penggunaan
    ========================

    1.  Struktur Menu
        -------------

> Pada bagian ini akan dijelaskan mengenai menu apa saja yang terdapat
> pada aplikasi P-Office. Menu yang terdapat pada aplikasi P-Office
> adalah sebagai berikut:

1.  Inbox

> Merupakan lokasi penyimpanan surat masuk, memorandum, fax, SP3S dan
> SPPTH yang diterima oleh *user* sebagai tujuan langsung maupun berupa
> tembusan baik surat yang bernomor maupun belum bernomor.

2.  Draft

> Merupakan lokasi penyimpanan surat masuk, memorandum, fax, SP3S dan
> SPPTH yang disimpan sehingga masih dapat diubah dan ditindak lanjuti.
> Jenis surat yang dapat disimpan sebagai template juga tersimpan di
> menu Draft dengan terdapat *label* Template pada *list* surat

3.  Outbox

> Merupakan lokasi penyimpanan surat masuk, memorandum, disposisi fax,
> SP3S dan SPPTH yang sudah selesai disetujui atau dikirim ke pejabat
> yang dituju

4.  Disposisi

> Merupakan lokasi penyimpanan disposisi surat masuk, memorandum dan fax
> keluar yang diterima oleh pejabat yang dikirimkan disposisi untuk
> dilakukan tindak lanjut. Tindak lanjut yang dapat dilakukan oleh
> pejabat penerima disposisi adalah mendisposisikan kepejabat tujuan,
> menyelesaikan disposisi dan mengirimkan tanggapan disposisi

5.  Rejected

> Merupakan lokasi penyimpanan surat yang dikembalikan ke konseptor atau
> reviewer sebelumnya. Surat yang sudah dikembalikan akan dapat diedit
> kembali dan dikirimkan ke pejabat tujuan

6.  Archive

> Merupakan lokasi penyimpanan surat yang sudah lewat masa retensi
> dokumennya

7.  Document Control

> Merupakan menu yang ditujuan untuk *user* sekretaris dalam memudahkan
> mengelola pengajuann nomor offline. Pada menu ini sekretaris juga
> dapat melakukan pengelolaan dokumen yang masuk pada atasan pejabatnya.
> Dokumen yang dapat dikelola antara lain yaitu dokumen masuk, dokumen
> keluar dan dokumen disposisi.

8.  History

> Merupakan menu yang dapat menampilkan riwayat (*history*) SP3S atau
> pejabat yang sedang menjabat Pjs baik dalam status aktif maupun
> non-aktif

9.  Master

> Merupakan menu yang digunakan untuk mengelola data master sebagai
> acuan untuk melakukan proses pengelolaan jenis surat. Data master yang
> dikelola antara lain: klasifikasi surat, prioritas surat, kode simpan,
> mapping sekretaris dengan atasan pejabatnya dan template surat

10. Konfigurasi

> Merupakan menu yang digunakan dalam mengelola konfigurasi seperti data
> *user*, jabatan dan unit kerja serta menampilkan informasi aplikasi
> dan dapat mengelola notifikasi email ketujuan terkait perubahan yang
> terjadi pada aplikasi P-Office.

Penggunaan
----------

Pada bagian ini akan dijelaskan mengenai cara penggunaan aplikasi
P-Office.

###  Login

> Pada bagian ini akan dijelaskan cara login pada aplikasi P-Office.
> Langkah-langkah untuk masuk aplikasi adalah sebagai berikut:

1.  Bukalah aplikasi P-Office melalui web browser (Google Chrome,
    Mozilla Firefox atau lainnya) dengan alamat url sebagai berikut:
    [https://P-Office.pepc.oficioo.id](https://ecorr.pepc.oficioo.id)

2.  Masukkan email *user* kemudian klik **Next**

> ![](.//media/image5.png){width="5.510416666666667in"
> height="2.6404330708661417in"}

3.  Masukkan password kemudian klik **Login**

> ![](.//media/image6.png){width="5.510416666666667in"
> height="2.6404330708661417in"}

4.  Sistem akan menampilkan halaman utama aplikasi P-Office jika
    berhasil login

    1.  ### Surat Masuk

> Pada modul ini mendukung proses input surat masuk oleh
> sekretaris berdasarkan berkas fisik yang
> diterima dan kemudian dikirimkan ke pejabat penerima surat. Pejabat
> tersebut dapat meneruskan surat dengan mendisposisikan surat kepada
> pejabat tujuan lainnya ataupun pejabat yang ada di bawahnya

#### Melihat Daftar Surat Masuk

**Role yang sesuai**

-   Semua *user*

> *User* dapat melihat daftar surat masuk yang ditujukan pada sekretaris
> tersebut. Langkah-langkah untuk melihat daftar surat masuk adalah
> sebagai berikut:

1.  Klik menu **Inbox** dan pilih tab **Surat Masuk**. Sistem akan
    > menampilkan daftar surat masuk yang ditujukan pada suatu *user*

> ![](.//media/image7.png){width="5.457333770778653in"
> height="2.6458333333333335in"}

#### Menambah Surat Masuk

**Role yang sesuai**

-   Sekretaris

> Sekretaris dapat menambah surat masuk pada aplikasi P-Office.
> Langkah-langkah untuk menambah surat masuk adalah sebagai berikut.

1.  Klik menu **New Correspondence**

> ![](.//media/image8.png){width="5.451388888888889in"
> height="2.6429516622922136in"}

2.  Pilih jenis surat "**Surat Masuk**"

> ![](.//media/image9.png){width="5.451388888888889in"
> height="2.6429516622922136in"}

3.  Isi form tambah surat masuk. Klik **Save** untuk menyimpan form
    > surat dan surat akan tersimpan di menu "**Draft -- Surat Masuk**".
    > Klik **Send** untuk mengirim surat masuk dan surat masuk akan
    > tersimpan di menu "**Outbox -- Surat Masuk**"

> ![](.//media/image10.png){width="5.458333333333333in"
> height="2.646318897637795in"}
>
> ![](.//media/image11.png){width="5.457334864391951in"
> height="2.6458333333333335in"}

4.  Sistem berhasil menyimpan perubahan

    1.  #### Melakukan Drafting Surat Masuk

**Role yang sesuai**

-   Sekretaris

Sekretaris dapat melakukan *drafting* surat masuk pada aplikasi
P-Office. *Drafting* surat masuk dilakukan jika sekretaris akan
meneruskan dan melakukan perubahan pada surat masuk yang sudah disimpan
pada menu **Draft.** Langkah-langkah untuk melakukan *drafting* surat
masuk adalah sebagai berikut.

1.  Klik menu **Draft** dan pilih tab **Surat Masuk**

> ![](.//media/image12.png){width="5.457333770778653in"
> height="2.6458333333333335in"}

2.  Pilih surat masuk yang akan diubah. Pilih tab **Detail** kemudian
    > klik **Edit**

> ![](.//media/image13.png){width="5.458333333333333in"
> height="2.646317804024497in"}

3.  Sistem akan menampilkan *form* **Edit Correspondence**

> ![](.//media/image14.png){width="5.458333333333333in"
> height="2.646317804024497in"}
>
> ![](.//media/image15.png){width="5.458333333333333in"
> height="2.646317804024497in"}

4.  Lakukan perubahan pada *form*. Klik **Send** untuk mengirim surat
    > masuk ke pejabat tujuan. Surat yang terkirim akan tersimpan di
    > menu "**Outbox -- Surat Masuk"**

    1.  #### Melihat Informasi Lengkap Surat Masuk

**Role yang sesuai**

-   Semua *user*

> *User* dapat melihat informasi lengkap surat masuk termasuk *preview*
> surat masuk, detail surat masuk, *tracking* surat masuk dan *history*
> surat masuk. Langkah-langkah untuk melihat informasi surat masuk
> adalah sebagai berikut.

1.  Klik menu **Inbox/Draft/Outbox** dan pilih tab **Surat Masuk.**
    > Pilih salah satu surat masuk yang akan dilihat informasinya

> ![](.//media/image16.png){width="5.457335958005249in"
> height="2.6458333333333335in"}

##### Preview Surat Masuk

> Pada *button* **Preview Surat Masuk**, ditampilkan *preview* surat
> masuk yang merupakan hasil unggahan yang diinputkan oleh
> sekretaris/konseptor.
>
> ![](.//media/image17.png){width="5.263963254593176in"
> height="2.5520833333333335in"}
>
> ![](.//media/image18.png){width="5.263963254593176in"
> height="2.5520833333333335in"}

##### Detail Surat Masuk

> Pada tab **Detail Surat Masuk**, terdapat informasi asal surat,
> perihal, file lampiran, kategori surat, resume, rekomendasi, nomor
> surat, klasifikasi surat, tanggal surat dan tujuan.
>
> ![](.//media/image19.png){width="5.263963254593176in"
> height="2.5520833333333335in"}

##### Tracking Surat Masuk

> Pada tab **Tracking Surat Masuk**, ditampilkan informasi *tracking*
> surat masuk dalam bentuk *chart*
>
> ![](.//media/image20.png){width="5.239583333333333in"
> height="2.5402635608048993in"}

##### History Surat Masuk

> Pada tab **History Surat Masuk**, ditampilkan riwayat surat masuk yang
> terdapat informasi jabatan, tanggal, tindakan dan komentar
>
> ![](.//media/image21.png){width="5.242477034120735in"
> height="2.5416666666666665in"}

#### Menolak Surat Masuk

**Role yang sesuai**

-   Approver *user* (Pemilik KBO)

Langkah-langkah untuk menolak surat masuk adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Surat Masuk**

> ![](.//media/image22.png){width="5.450694444444444in"
> height="2.6426148293963254in"}

2.  Pilih surat masuk yang akan ditolak kemudian pilih tab **Detail**

> ![](.//media/image23.png){width="5.457331583552056in"
> height="2.6458333333333335in"}

3.  Klik tombol **Reject** dan pilih **Send.** Isikan komentar jika
    > diperlukan

> ![](.//media/image24.png){width="5.46875in"
> height="2.6513681102362203in"}

4.  Sistem menampilkan *pop up* konfirmasi dan *user* harus mengisi
    > keterangan tolak disposisi surat masuk kemudian klik **Save**.

> ![](.//media/image25.png){width="5.456944444444445in"
> height="2.6456430446194226in"}

5.  Sistem menyimpan perubahan dan informasi tolak surat masuk. Surat
    > masuk yang sudah ditolak akan otomatis terhapus secara *soft
    > delete.*

    1.  #### Menyelesaikan Surat Masuk

**Role yang sesuai**

-   *Approver User* (Pemilik KBO)

> *User* dapat menyelesaikan surat masuk jika *user* tidak akan
> melanjutkan untuk mendisposisikan surat masuk ke pejabat lain atau
> surat masuk selesai pada *user* tersebut. Langkah-langkah untuk
> menyelesaikan surat masuk adalah sebagai berikut:

1.  Klik menu **Inbox** dan pilih tab **Surat masuk**

> ![](.//media/image26.png){width="5.457333770778653in"
> height="2.6458333333333335in"}

2.  Pilih surat masuk yang akan diselesaikan kemudian pilih tab
    > **Detail**

> ![](.//media/image27.png){width="5.456944444444445in"
> height="2.6456452318460193in"}

3.  Pilih tombol **Finish** kemudian klik **Send**

> ![](.//media/image28.png){width="5.4527777777777775in"
> height="2.6436242344706913in"}

4.  Sistem menampilkan *pop up* konfirmasi dan *user* harus mengisi
    > keterangan selesaikan disposisi kemudian klik **Save**.

> ![](.//media/image29.png){width="5.4527777777777775in"
> height="2.6436242344706913in"}

5.  Sistem menyimpan perubahan dan informasi selesai disposisi akan
    > tersimpan di detail disposisi.

    1.  #### Melihat Daftar Disposisi Surat Masuk

**Role yang sesuai**

-   *Approver User* (Pemilik KBO)

-   *Reviewer User*

-   *Member User (*Pekerja*)*

> *User* dapat melihat daftar disposisi surat masuk pada pada menu
> **Disposisi**. Langkah -- langkah untuk melihat daftar disposisi surat
> masuk adalah sebagai berikut

1.  Klik menu **Disposition** dan pilih tab **Surat Masuk**

> ![](.//media/image30.png){width="5.447916666666667in"
> height="2.6358366141732286in"}

#### Mendisposisikan Surat Masuk

**Role yang sesuai**

-   *Approver User* (Pemilik KBO)

-   *Reviewer User*

> *User* menerima surat masuk baru di menu "**Inbox - Surat Masuk**"
> atau menu "**Disposisi -- Surat Masuk**". Surat masuk dapat
> didisposisikan kepada pejabat yang dipilih atau pejabat yang ada
> dibawahnya. Disposisi surat masuk dapat dilakukan dengan dua cara
> yaitu melalui menu **Inbox** jika surat masuk yang diterima merupakan
> surat masuk yang ditujukan langsung dari sekretaris ke pejabat pemilik
> KBOnya atau melalui menu **Disposisi** jika surat masuk sudah
> dilakukan tindak lanjut oleh pejabat pemilik KBO dan pemilik KBO akan
> mendisposisikan ke pejabat selanjutnya atau pejabat yang ada
> dibawahnya. Langkah-langkah untuk mendisposisikan surat masuk adalah
> sebagai berikut:

##### Disposisi melalui Menu Inbox

1.  Klik menu **Inbox** dan pilih tab **Surat Masuk**

> ![](.//media/image31.png){width="5.450793963254593in"
> height="2.6354166666666665in"}

2.  Pilih surat masuk yang akan didisposisikan kemudian pilih tab
    > **Detail**

> ![](.//media/image32.png){width="5.450694444444444in"
> height="2.6353674540682417in"}

3.  Klik tombol **Disposisi** dan pilih **Send**

> ![](.//media/image33.png){width="5.450694444444444in"
> height="2.6353674540682417in"}

4.  Sistem menampilkan form disposisi. Isikan informasi disposisi dan
    > perintah untuk masing-masing penerima disposisi.

> ![](.//media/image34.png){width="5.464583333333334in"
> height="2.6420844269466315in"}

5.  Klik **Simpan** untuk menyimpan draft disposisi surat masuk dan
    > surat masuk akan tersimpan di menu "**Draft -- Surat masuk**".
    > Klik **Send** untuk mengirim disposisi ketujuan dan disposisi
    > surat masuk akan tersimpan di menu "**Outbox -- Disposisi**".

##### Disposisi melalui Menu Disposisi

1.  Klik menu **Disposisi** dan pilih tab **Surat Masuk**

> ![](.//media/image30.png){width="5.447050524934383in"
> height="2.6354166666666665in"}

2.  Pilih surat masuk yang akan didisposisikan kemudian pilih tab
    > **Detail**

> ![](.//media/image35.png){width="5.447049431321084in"
> height="2.6354166666666665in"}

3.  Klik tombol **Disposition** dan pilih **Send**

> ![](.//media/image36.png){width="5.468580489938757in"
> height="2.6458333333333335in"}

4.  Sistem menampilkan form disposisi. Isikan informasi disposisi dan
    > perintah untuk masing-masing penerima disposisi.

> ![](.//media/image37.png){width="5.468055555555556in"
> height="2.6419444444444444in"}

5.  Klik **Simpan** untuk menyimpan draft disposisi surat masuk dan
    > surat masuk akan tersimpan di menu "**Draft -- Surat masuk**".
    > Klik **Send** untuk mengirim disposisi ketujuan dan disposisi
    > surat masuk akan tersimpan di menu "**Outbox -- Disposisi**".

    1.  ####  Melakukan Custom Disposisi

**Role yang sesuai**

-   *Approver User*

-   *Reviewer User*

> *User* dapat melakukan *custom* penerima disposisi terhadap pejabat
> penerima yang akan menerima perintah disposisi. Secara *default*
> pejabat yang akan menerima disposisi adalah pejabat yang ada
> dibawahnya. Tetapi terdapat *case* jika *user* membutuhkan *custom*
> penerima disposisi sehingga disediakan fitur untuk memilih pejabat
> selain pejabat yang ada dibawahnya. Langkah-langkah untuk melakukan
> *custom* disposisi surat masuk adalah sebagai berikut:

1.  Klik menu **Inbox** dan pilih tab **Surat masuk**

> ![](.//media/image38.png){width="5.447916666666667in"
> height="2.63583552055993in"}

2.  Pilih surat masuk yang akan didisposisikan kemudian pilih tab
    > **Detail**

> ![](.//media/image39.png){width="5.458333333333333in"
> height="2.6408759842519687in"}

3.  Klik tombol **Disposition** dan pilih **Send**

> ![](.//media/image40.png){width="5.458333333333333in"
> height="2.64087489063867in"}

4.  Sistem menampilkan form disposisi. Klik icon "+" pada field
    > **Forward To.** Isikan informasi disposisi dan perintah untuk
    > masing-masing penerima disposisi.

> ![](.//media/image41.png){width="5.4534722222222225in"
> height="2.638523622047244in"}

5.  Sistem menampilkan daftar pejabat yang dapat dipilih untuk
    > didisposikan

> ![](.//media/image42.png){width="5.4527777777777775in"
> height="2.642415791776028in"}

6.  Isikan perintah dan keterangan pada masing-masing penerima
    > disposisi. Tambahkan lampiran disposisi jika diperlukan. Fitur
    > **Same All Comment Untuk Semua** dapat digunakan *user* untuk
    > memberikan komentar yang sama untuk masing-masing pejabat penerima
    > disposisi. Klik **Save** untuk menyimpan perubahan dan klik
    > **Send** untuk mengirim disposisi.

> ![](.//media/image43.png){width="5.468581583552056in"
> height="2.6458333333333335in"}

#### Melihat Informasi Lengkap Disposisi Surat Masuk

**Role yang sesuai**

-   *Approver User* (Pemilik KBO)

-   *Reviewer User*

-   *Member User (*Pekerja*)*

> *User* dapat melihat informasi lengkap disposisi surat masuk pada
> detail disposisi. Langkah-langkah untuk melihat informasi disposisi
> surat masuk adalah sebagai berikut.

1.  Klik menu **Disposition** dan pilih tab **Surat Masuk.** Pilih salah
    satu disposisi surat masuk yang akan dilihat informasinya

> ![](.//media/image44.png){width="5.4631944444444445in"
> height="2.639595363079615in"}

##### Preview Disposisi Surat Masuk

> Pada *button* **Mail,** ditampilkan surat masuk fisik yang sudah
> diunggah oleh sekretaris / konseptor.
>
> ![](.//media/image45.png){width="5.239583333333333in"
> height="2.5315562117235344in"}
>
> ![](.//media/image46.png){width="5.2389501312335955in"
> height="2.53125in"}

##### Preview Lembar Penerus

> Pada *button* **Preview,** ditampilkan informasi lembar penerus
> disposisi yang berisi informasi daftar nama pejabat dan perintah
> disposisi yang harus dilakukan oleh pejabat penerima disposisi
>
> ![](.//media/image47.png){width="5.238888888888889in"
> height="2.5312193788276467in"}
>
> ![](.//media/image48.png){width="5.238888888888889in"
> height="2.531220472440945in"}

##### Detail Disposisi Surat Masuk

> Pada tab **Detail**, terdapat informasi asal surat, perihal, file
> lampiran, kategori surat, resume, rekomendasi serta informasi
> disposisi yang mencakup lampiran disposisi, tujuan, tindak lanjut dan
> disposisi permasing-masing pejabat penerima disposisi
>
> ![](.//media/image49.png){width="5.239583333333333in"
> height="2.5315562117235344in"}

##### Tracking Disposisi Surat Masuk

> Pada tab ***Tracking***, ditampilkan informasi *tracking* disposisi
> surat masuk dalam bentuk *chart*
>
> ![](.//media/image50.png){width="5.260511811023622in"
> height="2.5416666666666665in"}

##### History Disposisi Surat Masuk

> Pada tab ***History***, ditampilkan riwayat surat masuk yang terdapat
> informasi jabatan, tanggal, tindakan dan komentar.
>
> ![](.//media/image51.png){width="5.229166666666667in"
> height="2.5265234033245845in"}

#### Melakukan Recall Disposisi Surat Masuk

**Role yang sesuai**

-   *Approver User* (Pemilik KBO)

-   *Reviewer User*

-   *Member User (*Pekerja*)*

> *User* dapat melakukan *recall* / tarik disposisi surat masuk yang
> sudah dikirim kepada pejabat penerima disposisi. Surat masuk yang
> sudah dikirim ke pejabat penerima disposisi akan tersimpan di menu
> "**Outbox -- Disposisi**" Langkah-langkah untuk melakukan *recall*
> disposisi surat masuk adalah sebagai berikut:

1.  Klik menu **Outbox** dan pilih tab **Disposisi**

> ![](.//media/image52.png){width="5.458333333333333in"
> height="2.6372462817147855in"}

2.  Pilih surat masuk yang akan di-*recall* kemudian klik tab **Detail**
    > kemudian klik **Recall**

> ![](.//media/image53.png){width="5.447916666666667in"
> height="2.6322145669291337in"}

3.  Surat masuk yang sudah di-*recall* akan tersimpan di menu "**Draft -
    > Disposisi**" penerima fax masuk / pendisposisi.

    1.  #### Menyelesaikan Disposisi Surat Masuk

**Role yang sesuai**

-   *Approver User* (Pemilik KBO)

-   *Reviewer User*

-   *Member User (*Pekerja*)*

> *User* dapat menyelesaikan disposisi surat masuk jika *user* tidak
> akan melanjutkan untuk mendisposisikan surat masuk ke pejabat lain.
> Langkah-langkah untuk menyelesaikan surat masuk adalah sebagai berikut

1.  Klik menu **Disposisi** dan pilih tab **Surat Masuk**

> ![](.//media/image54.png){width="5.464583333333334in"
> height="2.6402668416447943in"}

2.  Pilih disposisi yang akan diselesaikan kemudian pilih tab **Detail**

> ![](.//media/image55.png){width="5.447916666666667in"
> height="2.6322145669291337in"}

3.  Pilih tombol **Finished** kemudian klik **Send**

> ![](.//media/image56.png){width="5.454545056867891in"
> height="2.6354166666666665in"}

4.  Sistem menampilkan pop up konfirmasi dan *user* harus mengisi
    > keterangan selesaikan disposisi kemudian klik **Save**.

> ![](.//media/image57.png){width="5.454547244094488in"
> height="2.6354166666666665in"}

5.  Sistem menyimpan perubahan dan informasi selesai disposisi akan
    > tersimpan di detail disposisi.

    1.  #### Mengirim Tanggapan Disposisi Surat Masuk

**Role yang sesuai**

-   *Reviewer User*

-   *Member User (*Pekerja*)*

> *User* dapat mengirim tanggapan disposisi surat masuk yang ditujukan
> untuk pejabat pengirim disposisi. Langkah-langkah untuk mengirim
> tanggapan disposisi surat masuk adalah sebagai berikut

1.  Klik menu **Disposisi** dan pilih tab **Surat Masuk**

> ![](.//media/image58.png){width="5.447916666666667in"
> height="2.6322145669291337in"}

2.  Pilih disposisi yang akan dikirim tanggapan kemudian pilih tab
    > **Detail**

> ![](.//media/image59.png){width="5.458333333333333in"
> height="2.637247375328084in"}

3.  Pilih tombol **Send Response** kemudian klik **Send**

> ![](.//media/image60.png){width="5.458333333333333in"
> height="2.637247375328084in"}

4.  Sistem menampilkan pop up konfirmasi dan *user* harus mengisi
    > keterangan kirim tanggapan disposisi kemudian klik **Save**.

> ![](.//media/image61.png){width="5.454545056867891in"
> height="2.6354166666666665in"}

5.  Sistem menyimpan perubahan dan informasi tanggapan disposisi akan
    > tersimpan di detail disposisi.

    1.  ### Surat Keluar

> Pada modul ini mendukung proses pembuatan konsep surat keluar yang
> ditujukan untuk eksternal Pertamina. Pembuat konsep surat keluar atau
> disebut sebagai konseptor surat akan mengirimkan draf surat keluar
> untuk dicek oleh *reviewer* dan disetujui oleh *approver*. Setelah
> surat sudah disetujui maka akan diberikan nomor surat keluar secara
> otomatis melalui sistem.

#### Melihat Daftar Surat Keluar

**Role yang sesuai**

-   *Approver User* (Pemilik KBO)

-   *Reviewer User*

-   *Member User (*Pekerja*)*

> *User* dapat melihat daftar surat keluar pada pada menu **Inbox, Draft
> atau Outbox** pada masing-masing akun. Langkah -- langkah untuk
> melihat daftar surat keluar adalah sebagai berikut

1.  Klik menu **Inbox / Draft / Outbox** dan pilih tab **Surat Keluar**

![](.//media/image62.png){width="5.760416666666667in"
height="2.7832010061242345in"}

#### Menambah Surat Keluar

**Ditujukan kepada**

-   *Approver User* (Pemilik KBO)

-   *Reviewer User*

**Role yang sesuai**

-   *Member User (*Pekerja*)*

> Konseptor dapat menambah surat keluar pada aplikasi P-Office.
> Langkah-langkah untuk menambah surat keluar adalah sebagai berikut.

1.  Klik menu **New Correspondence**

> ![](.//media/image63.png){width="5.454543963254594in"
> height="2.6354166666666665in"}

2.  Pilih jenis surat "**Surat Keluar**"

> ![](.//media/image64.png){width="5.454166666666667in"
> height="2.6352340332458444in"}

3.  Isi *form* tambah surat keluar. Terdapat bebarapa aksi untuk
    > menindaklanjuti surat keluar yang sudah diisi *form*nya yaitu
    > **Save Surat Keluar**, **Cancel Surat Keluar** dan **Save Template
    > Surat Keluar.**

> ![](.//media/image65.png){width="5.4527777777777775in"
> height="2.634562554680665in"}
>
> ![](.//media/image66.png){width="5.46875in"
> height="2.642280183727034in"}

##### Simpan Surat Keluar

> Langkah -- langkah untuk menyimpan surat keluar adalah sebagai
> berikut.

1.  Isi *form* surat keluar kemudian klik **Save**

> ![](.//media/image67.png){width="5.458333333333333in"
> height="2.637247375328084in"}

2.  Sistem akan menampilkan tampilan *preview* surat keluar dalam bentuk
    > Word yang dapat di edit. Untuk melakukan *editing* terhadap isi
    > surat klik **Edit Content** kemudian sistem akan menampilkan *pop
    > up* konfirmasi **Ubah Word Desktop** atau **Ubah *Online***

> ![](.//media/image68.png){width="5.447916666666667in"
> height="2.6322156605424323in"}
>
> ![](.//media/image69.png){width="5.447916666666667in"
> height="2.631855861767279in"}

##### \[Edit\] Word Desktop

> Langkah -- langkah untuk mengubah isi surat keluar melalui Word
> Desktop adalah sebagai berikut.

1.  Klik **Ubah di Word** untuk mengubah melalui aplikasi Microsoft Word

> ![](.//media/image70.png){width="5.47959208223972in"
> height="2.64715769903762in"}

2.  Lakukan perubahan pada isi surat. Klik **Close** pada aplikasi Isi
    > surat akan otomatis tersimpan

> ![](.//media/image71.png){width="5.4846937882764655in"
> height="2.9314326334208225in"}

##### \[Edit\] Ubah *Online*

> Langkah -- langkah untuk mengubah isi surat keluar secara *online*
> adalah sebagai berikut:

1.  Ketika *Klik button Edit Content* maka secara otomatis akan membuka
    > dokumen dan bisa mengubah isi surat secara *online*

> ![](.//media/image69.png){width="5.447916666666667in"
> height="2.631855861767279in"}

2.  Lakukan perubahan pada isi surat.

> ![](.//media/image69.png){width="5.447916666666667in"
> height="2.631855861767279in"}

3.  Isi surat akan otomatis tersimpan. Jika surat akan disimpan sebagai
    > draft, maka klik **Close.**

> ![](.//media/image72.png){width="5.474490376202975in"
> height="2.6410629921259843in"}

4.  Surat yang sudah selesai diubah maka akan tersimpan di menu "**Draft
    > -- Surat Keluar"**

##### Kirim Surat Keluar

> Langkah -- langkah untuk mengirim surat keluar adalah sebagai berikut.

1.  Pada tampilan *preview* surat keluar, klik **Kirim** untuk mengirim
    > surat ke pejabat tujuan

> ![](.//media/image73.png){width="5.499359142607174in"
> height="2.653061023622047in"}

2.  Sistem menyimpan perubahan dan surat keluar akan tersimpan di menu
    > "**Outbox - Surat Keluar**"

    1.  #### Save as Template Surat Keluar

**Ditujukan kepada**

-   *Reviewer*

-   *Approver*

**Role yang sesuai**

-   *Member User (*Pekerja*)*

> *User* dapat menyimpan surat sebagai *template*. *Template* ini
> digunakan jika sewaktu-waktu *user* akan melanjutkan surat keluar yang
> sudah dibuat dan diubah kembali kemudian dikirimkan kepejabat tujuan
> tanpa harus mengisi *form* surat keluar. Langkah -- langkah untuk
> menyimpan surat keluar sebagai *template* adalah sebagai berikut.

1.  Isi *form* surat keluar dan klik **Save as Template**

> ![](.//media/image74.png){width="5.46134842519685in"
> height="2.65625in"}

2.  Surat keluar yang disimpan menjadi *template* akan tersimpan di menu
    > "**Draft -- Surat Keluar".** Untuk melanjutkan *template* yang
    > sudah dibuat *user* dapat memilih menu "**Draft -- Surat Keluar**"
    > kemudian pilih *template* yang akan digunakan

> ![](.//media/image75.png){width="5.439930008748906in"
> height="2.6458333333333335in"}

3.  Pilih tombol ***User* Template** untuk melanjutkan edit surat

> ![](.//media/image76.png){width="5.4827668416447946in"
> height="2.6666666666666665in"}

4.  Sistem akan menampilkan form **Edit Correspondence,** klik **Save**
    > untuk menyimpan perubahan

> ![](.//media/image77.png){width="5.46875in"
> height="2.6598501749781276in"}

5.  Lakukan perubahan pada surat, klik **Save** untuk menyimpan
    > perubahan dan surat akan tersimpan di menu **"Draft -- Surat
    > Keluar"** sebagai draft atau klik **Send** untuk mengirimkan ke
    > pejabat tujuan dan tersimpan di menu **"Outbox -- Surat Keluar".**

    1.  #### Melakukan Drafting Surat Keluar

**Role yang sesuai**

-   *Member User (*Pekerja*)*

-   *Approver*

-   *Reviewer*

> *User* dapat melakukan *drafting* surat keluar pada aplikasi P-Office.
> *Drafting* surat keluar dilakukan jika *user* akan meneruskan dan
> melakukan perubahan pada surat keluar yang sudah disimpan pada menu
> **Draft.**

Langkah-langkah untuk melakukan *drafting* surat keluar adalah sebagai
berikut.

1.  Klik menu **Draft** dan pilih tab **Surat Keluar**

> ![](.//media/image78.png){width="5.441666666666666in"
> height="2.64667760279965in"}

2.  Pilih surat keluar yang akan diubah. Pilih tab **Detail** kemudian
    > klik **Edit**

> ![](.//media/image79.png){width="5.427083333333333in"
> height="2.63958552055993in"}

3.  Sistem akan menampilkan *form* **Edit Correspondence**

> ![](.//media/image80.png){width="5.46875in"
> height="2.659851268591426in"}

4.  Lakukan perubahan pada *form*. Klik **Save** untuk menyimpan
    > perubahan pada *form* surat keluar. Surat yang disimpan akan
    > tersimpan di menu "**Draft -- Surat keluar"**

> ![](.//media/image81.png){width="5.482765748031496in"
> height="2.6666666666666665in"}

5.  Klik **Edit Content** untuk mengubah isi surat keluar

> ![](.//media/image82.png){width="5.441666666666666in"
> height="2.64667760279965in"}

6.  Sistem menampilkan tampilan *preview* surat keluar dalam bentuk Word
    > yang dapat di edit. Untuk melakukan *editing* terhadap isi surat
    > klik **Edit Content** kemudian sistem akan menampilkan *pop up*
    > konfirmasi **Ubah Word Desktop** atau **Ubah *Online***

> ![](.//media/image69.png){width="5.447916666666667in"
> height="2.631855861767279in"}

##### \[Edit\] Word Desktop

> Langkah -- langkah untuk mengubah isi surat keluar melalui Word
> Desktop adalah sebagai berikut.

1.  Klik **Ubah di Word** untuk mengubah melalui aplikasi Microsoft Word

> ![](.//media/image70.png){width="5.47959208223972in"
> height="2.64715769903762in"}

2.  Lakukan perubahan pada isi surat. Klik **Close** pada aplikasi dan
    > isi surat akan otomatis tersimpan

> ![](.//media/image71.png){width="5.4846937882764655in"
> height="2.9314326334208225in"}

##### \[Edit\] Ubah *Online*

> Langkah -- langkah untuk mengubah isi surat keluar secara *online*
> adalah sebagai berikut.

1.  Ketika *Klik button Edit Content* maka secara otomatis akan membuka
    > dokumen dan bisa mengubah isi surat secara *online*

> ![](.//media/image69.png){width="5.447916666666667in"
> height="2.631855861767279in"}

2.  Lakukan perubahan pada isi surat.

> ![](.//media/image69.png){width="5.447916666666667in"
> height="2.631855861767279in"}

3.  Isi surat akan otomatis tersimpan. Jika surat akan disimpan sebagai
    > draft, maka klik **Close.**

> ![](.//media/image72.png){width="5.474490376202975in"
> height="2.6410629921259843in"}

4.  Surat yang sudah selesai diubah maka akan tersimpan di menu "**Draft
    > -- Surat Keluar"**

##### Kirim Surat Keluar

Langkah -- langkah untuk mengirim surat keluar adalah sebagai berikut.

1.  Pada tampilan *preview* surat keluar, klik **Kirim** untuk mengirim
    > surat ke pejabat tujuan

> ![](.//media/image73.png){width="5.499359142607174in"
> height="2.653061023622047in"}

2.  Sistem menyimpan perubahan dan surat keluar akan tersimpan di menu
    > "**Outbox - Surat Keluar**"

    1.  #### Melihat Informasi Lengkap Surat Keluar

**Role yang sesuai**

-   *Member User (*Pekerja*)*

-   *Approver*

-   *Reviewer*

> *User* dapat melihat informasi lengkap surat keluar termasuk *preview*
> surat keluar, detail surat keluar, *tracking* surat keluar dan
> *history* surat keluar. Langkah-langkah untuk melihat informasi surat
> keluar adalah sebagai berikut.

1.  Klik menu **Inbox/Draft/Outbox** dan pilih tab **Surat Keluar.**
    > Pilih salah satu surat keluar yang akan dilihat informasinya

> ![](.//media/image83.png){width="5.439930008748906in"
> height="2.6458333333333335in"}

##### Preview Surat Keluar

> Pada *button Preview* surat keluar, ditampilkan *preview* surat keluar
> yang sudah dibuat. *Preview* surat keluar disesuaikan dengan template
> berdasarkan jenis surat.
>
> ![](.//media/image84.png){width="5.239583333333333in"
> height="2.5483891076115484in"}
>
> ![](.//media/image85.png){width="5.239583333333333in"
> height="2.5277373140857393in"}

##### Detail Surat Keluar

> Pada tab Detail surat keluar, terdapat informasi asal surat, perihal,
> file lampiran, nomor surat, klasifikasi surat, tanggal surat, tujuan
> surat dan *reviewer*
>
> ![](.//media/image86.png){width="5.239583333333333in"
> height="2.548391294838145in"}

##### Tracking Surat Keluar

> Pada tab *tracking* surat keluar, ditampilkan informasi *tracking*
> surat keluar dalam bentuk *chart*
>
> ![](.//media/image87.png){width="5.25in"
> height="2.5534558180227473in"}

##### History Surat Keluar

> Pada tab *History* surat keluar, ditampilkan riwayat surat keluar yang
> terdapat informasi jabatan, tanggal, tindakan dan komentar
>
> ![](.//media/image88.png){width="5.239583333333333in"
> height="2.548390201224847in"}

#### Menyetujui Surat Keluar

**Role yang sesuai**

-   *Reviewer*

-   *Approver*

*User* dapat menyetujui surat keluar yang sudah dilakukan review dan
surat keluar akan dikirimkan ke *reviewer* selanjutnya atau *approver*.
Langkah-langkah untuk menyetujui surat keluar adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Surat Keluar**

> ![](.//media/image89.png){width="5.458333333333333in"
> height="2.6547845581802276in"}

2.  Pilih surat keluar yang akan ditindak lanjuti kemudian pilih tab
    > **Detail**

> ![](.//media/image90.png){width="5.461345144356955in"
> height="2.65625in"}

3.  Klik tombol **Approve** dan pilih **Send.** Isikan komentar jika
    > diperlukan

> ![](.//media/image91.png){width="5.461111111111111in"
> height="2.638229440069991in"}

4.  Sistem berhasil menyimpan perubahan. Surat keluar yang sudah di
    > kirim akan tersimpan di menu **Outbox- Surat Keluar**

    1.  #### Kembalikan Surat keluar ke Sebelumnya

**Role yang sesuai**

-   *Reviewer*

-   *Approver*

> *User* dapat mengembalikan surat keluar ke sebelumnya jika hasil
> review belum / tidak sesuai. Surat akan dikembalikan ke satu level
> *reviewer* sebelumnya atau ke konseptor (apabila hanya ada satu
> *reviewer*). Langkah-langkah untuk mengembalikan surat keluar ke
> sebelumnya adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Surat Keluar**

> ![](.//media/image92.png){width="5.4342169728783905in"
> height="2.6430555555555557in"}

2.  Pilih surat keluar yang akan ditindak lanjuti kemudian pilih tab
    > **Detail**

> ![](.//media/image93.png){width="5.447916666666667in"
> height="2.649717847769029in"}

3.  Klik tombol **Return Previus** dan pilih **Send.** Isikan komentar
    > jika diperlukan

> ![](.//media/image94.png){width="5.439930008748906in"
> height="2.6458333333333335in"}

4.  Sistem berhasil menyimpan perubahan. Surat keluar yang sudah di
    > kirim akan tersimpan di menu **Outbox- Surat keluar** dan penerima
    > pengembalian surat keluar akan menerima surat keluar di menu
    > **Draft - Surat keluar**

    1.  #### Kembalikan Surat keluar ke Konseptor

**Role yang sesuai**

-   *Reviewer*

-   *Approver*

> *User* dapat mengembalikan surat keluar ke konseptor jika hasil review
> belum / tidak sesuai. Langkah-langkah untuk mengembalikan surat keluar
> ke konseptor adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Surat keluar**

> ![](.//media/image92.png){width="5.4342169728783905in"
> height="2.6430555555555557in"}

2.  Pilih surat keluar yang akan ditindak lanjuti kemudian pilih tab
    > **Detail**

> ![](.//media/image93.png){width="5.447916666666667in"
> height="2.649717847769029in"}

3.  Klik tombol **Return Conceptor** dan pilih **Send.** Isikan komentar
    > jika diperlukan

> ![](.//media/image95.png){width="5.4827635608049in"
> height="2.6666666666666665in"}

4.  Sistem berhasil menyimpan perubahan. Surat keluar yang sudah di
    > kirim akan tersimpan di menu **Outbox- Surat Keluar** dan
    > konseptor akan menerima surat keluar di menu **Draft -- Surat
    > Keluar**

    1.  #### Menolak Surat Keluar

**Role yang sesuai**

-   *Reviewer*

-   *Approver*

> *User* dapat menolak surat keluar yang akan dikemnbalikan ke konseptor
> jika hasil review surat keluar belum / tidak sesuai. Langkah-langkah
> untuk menolak surat keluar adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Surat Keluar**

> ![](.//media/image92.png){width="5.458333333333333in"
> height="2.6547845581802276in"}

2.  Pilih surat keluar yang akan ditindak lanjuti kemudian pilih tab
    > **Detail**

> ![](.//media/image93.png){width="5.447916666666667in"
> height="2.649717847769029in"}

3.  Klik tombol **Reject** dan pilih **Send.** Isikan komentar jika
    > diperlukan

> ![](.//media/image96.png){width="5.458333333333333in"
> height="2.6547845581802276in"}

4.  Sistem berhasil menyimpan perubahan. Surat keluar yang sudah ditolak
    > akan otomatis terhapus secara *soft delete.*

    1.  #### Menambah Reviewer Baru Surat Keluar

**Role yang sesuai**

-   *Approver*

> *User* dapat menambahkan reviewer kemudian surat keluar akan
> diteruskan ke reviewer baru. Langkah-langkah untuk menambah reviewer
> surat keluar adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Surat Keluar**

> ![](.//media/image92.png){width="5.458333333333333in"
> height="2.6547845581802276in"}

2.  Pilih surat keluar yang akan ditindak lanjuti kemudian pilih tab
    > **Detail**

> ![](.//media/image93.png){width="5.447916666666667in"
> height="2.649717847769029in"}

3.  Klik tombol **Add Reviewer** dan pilih pejabat yang akan melakukan
    > review dengan meng-klik tombol "+" pada field **Add Reviewer**

> ![](.//media/image97.png){width="5.447916666666667in"
> height="2.649717847769029in"}

4.  Sistem akan menampilkan pejabat untuk dijadikan reviewer baru

> ![](.//media/image98.png){width="5.439928915135608in"
> height="2.6458333333333335in"}

5.  Pilih **Send** untuk mengirimkan kepada pejabat/reviewer yang dituju
    > dan surat keluar akan tersimpan di menu "**Outbox - Surat
    > Keluar**". Untuk pejabat/reviewer baru akan menerima surat keluar
    > di menu "**Inbox -- Surat Keluar**"

> ![](.//media/image99.png){width="5.46875in"
> height="2.6598501749781276in"}

#### Mengesahkan Nomor Surat Keluar

**Role yang sesuai**

-   *Approver*

> *User* dapat mengesahkan surat keluar yang sudah dikirim dan direview
> oleh reviewer. Keluaran untuk tindak lanjut ini adalah untuk
> men-*generate* nomor surat keluar kemudian surat keluar dapat
> dikirimkan ke pejabat tujuan. Langkah-langkah untuk menambah reviewer
> surat keluar adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Surat Keluar**

> ![](.//media/image100.png){width="5.464583333333334in"
> height="2.657823709536308in"}

2.  Pilih surat keluar yang akan ditindak lanjuti kemudian pilih tab
    > **Detail.** Pada tab **Detail** terdapat informasi nomor surat
    > yang masih bersifat sementara. Nomor inilah yang akan
    > ter-*generate* jika *user* menyetujui surat keluar.

> ![](.//media/image101.png){width="5.464583333333334in"
> height="2.657823709536308in"}

3.  Klik **Approve** kemudian pilih **Send**

> ![](.//media/image102.png){width="5.46875in"
> height="2.6598501749781276in"}

4.  Sistem menyimpan perubahan dan nomor surat keluar akan
    > ter-*generate* sesuai dengan nomor sementara pada detail. Surat
    > keluar yang sudah diseyujui akan tersimpan di menu "**Outbox -
    > Surat Keluar**" pengirim sedangkan surat keluar akan tersimpan di
    > menu "**Inbox - Surat Keluar**" penerima.

    1.  ### Memorandum

> Pada modul ini mendukung proses pembuatan konsep memorandum yang akan
> disetujui oleh *reviewer*/*approver*. Setelah memorandum disetujui
> maka akan diberikan nomor memorandum secara otomatis dan dikirimkan ke
> pejabat pemilik Kode Bagian Organisasi (KBO). Pemilik KBO tersebut
> akan mendapatkan memorandum masuk pada menu "I**nbox**" dan dapat
> mendisposisikan memorandum kepada pejabat yang dipilih atau pejabat
> yang ada di bawahnya sampai dengan level staf. 

#### Melihat Daftar Memorandum

**Role yang sesuai**

-   *Member User (*Pekerja*)*

-   *Reviewer*

-   *Approver*

> *User* dapat melihat daftar memorandum pada pada menu **Inbox, Draft
> atau Outbox** pada masing-masing akun. Langkah -- langkah untuk
> melihat daftar memorandum adalah sebagai berikut

1.  Klik menu **Inbox / Draft / Outbox** dan pilih tab **Memorandum**

> ![](.//media/image103.png){width="5.46134842519685in"
> height="2.65625in"}

#### Menambah Memorandum

**Ditujukan kepada**

-   *Reviewer*

-   *Approver*

**Role yang sesuai**

-   *Member User (*Pekerja*)*

> Konseptor dapat menambah memorandum pada aplikasi P-Office.
> Langkah-langkah untuk menambah memorandum adalah sebagai berikut.

1.  Klik menu **New Correspondence**

> ![](.//media/image104.png){width="5.461346237970254in"
> height="2.65625in"}

2.  Pilih jenis surat "**Memorandum**"

> ![](.//media/image105.png){width="5.458333333333333in"
> height="2.654783464566929in"}

3.  Isi *form* tambah memorandum. Terdapat bebarapa aksi untuk
    > menindaklanjuti memorandum yang sudah diisi *form*nya yaitu **Save
    > Mail Memorandum**, **Cancel Memorandum** dan **Save as Template
    > Memorandum.**

> ![](.//media/image106.png){width="5.461347331583552in"
> height="2.65625in"}
>
> ![](.//media/image107.png){width="5.439928915135608in"
> height="2.6458333333333335in"}

##### Simpan Memorandum

> Langkah -- langkah untuk menyimpan memorandum adalah sebagai berikut.

1.  Isi *form* memorandum kemudian klik **Save Mail**

> ![](.//media/image108.png){width="5.458333333333333in"
> height="2.6547845581802276in"}

2.  Sistem akan menampilkan tampilan *preview* memorandum dalam bentuk
    > Word yang dapat di edit. Untuk melakukan *editing* terhadap isi
    > surat klik **Edit Content** kemudian sistem akan menampilkan *pop
    > up* konfirmasi **Ubah Word Desktop** atau **Ubah *Online***

> ![](.//media/image109.png){width="5.47959208223972in"
> height="2.6435247156605426in"}

##### \[Edit\] Word Desktop

> Langkah -- langkah untuk mengubah isi memorandum melalui Word Desktop
> adalah sebagai berikut.

1.  Klik **Open in Dekstop App** untuk mengubah melalui aplikasi
    > Microsoft Word

> ![](.//media/image110.png){width="5.47959208223972in"
> height="2.6435247156605426in"}

2.  Lakukan perubahan pada isi surat. Klik **Close** pada aplikasi dan
    > isi surat akan otomatis tersimpan

> ![](.//media/image111.png){width="5.5in"
> height="2.9396128608923884in"}

##### \[Edit\] Ubah *Online*

> Langkah -- langkah untuk mengubah isi memorandum secara *online*
> adalah sebagai berikut.

1.  Ketika *Klik button Edit Content* maka secara otomatis akan membuka
    > dokumen dan bisa mengubah isi surat secara *online*

> ![](.//media/image112.png){width="5.486805555555556in"
> height="2.6506419510061243in"}

2.  Lakukan perubahan pada isi surat.

> ![](.//media/image112.png){width="5.486805555555556in"
> height="2.6506419510061243in"}

3.  Isi surat akan otomatis tersimpan. Jika surat akan disimpan sebagai
    > draft, maka klik **Close.**

> ![](.//media/image113.png){width="5.486805555555556in"
> height="2.6506419510061243in"}

4.  Surat yang sudah selesai diubah maka akan tersimpan di menu "**Draft
    > -- Memorandum"**

##### Kirim Memorandum

> Langkah -- langkah untuk mengirim memorandum adalah sebagai berikut.

1.  Pada tampilan *preview* memorandum, klik **Kirim** untuk mengirim
    > surat ke pejabat tujuan

> ![](.//media/image114.png){width="5.47959208223972in"
> height="2.64715769903762in"}

2.  Sistem menyimpan perubahan dan memorandum akan tersimpan di menu
    > "**Outbox - Memorandum**"

    1.  #### Save as Template Memorandum

**Ditujukan kepada**

-   *Reviewer*

-   *Approver*

**Role yang sesuai**

-   *Member User (*Pekerja*)*

*User* dapat menyimpan memorandum sebagai *template*. *Template* ini
digunakan jika sewaktu-waktu *user* akan melanjutkan memorandum yang
sudah dibuat dan diubah kembali kemudian dikirimkan kepejabat tujuan
tanpa harus mengisi *form* memorandum. Langkah -- langkah untuk
menyimpan memorandum sebagai *template* adalah sebagai berikut.

1.  Isi *form* memorandum dan Klik **Save as Template**

> ![](.//media/image115.png){width="5.447916666666667in"
> height="2.649717847769029in"}

2.  Memorandum yang disimpan menjadi template akan tersimpan di menu
    > "**Draft -- Memorandum".** Untuk melanjutkan *template* yang sudah
    > dibuat *user* dapat memilih menu "**Draft -- Memorandum**"
    > kemudian pilih *template* yang akan digunakan

> ![](.//media/image116.png){width="5.46875in"
> height="2.6598501749781276in"}

3.  Pilih tombol ***User* Template** untuk melanjutkan edit memorandum

> ![](.//media/image117.png){width="5.447916666666667in"
> height="2.649717847769029in"}

4.  Sistem akan menampilkan form **Edit Correspondence,** klik **Save**
    > untuk menyimpan perubahan

> ![](.//media/image118.png){width="5.447916666666667in"
> height="2.649717847769029in"}

5.  Lakukan perubahan pada surat, klik **Simpan** untuk menyimpan
    > perubahan dan memorandum akan tersimpan di menu **"Draft --
    > Memorandum"** sebagai draft atau klik **Send** untuk mengirimkan
    > ke pejabat tujuan dan tersimpan di menu **"Outbox --
    > Memorandum".**

    1.  #### Melakukan Drafting Memorandum

**Role yang sesuai**

-   Konseptor

-   *Approver*

-   *Reviewer*

> *User* dapat melakukan *drafting* memorandum pada aplikasi P-Office.
> *Drafting* memorandum dilakukan jika *user* akan meneruskan dan
> melakukan perubahan pada memorandum yang sudah disimpan pada menu
> **Draft.** Langkah-langkah untuk melakukan *drafting* memorandum
> adalah sebagai berikut:

1.  Klik menu **Draft** dan pilih tab **Memorandum**

> ![](.//media/image119.png){width="5.482764654418197in"
> height="2.6666666666666665in"}

2.  Pilih memorandum yang akan diubah. Pilih tab **Detail** kemudian
    > klik **Edit**

> ![](.//media/image120.png){width="5.46875in"
> height="2.659851268591426in"}

3.  Sistem akan menampilkan *form* **Edit Correspondence**

> ![](.//media/image121.png){width="5.4375in"
> height="2.644650043744532in"}

4.  Lakukan perubahan pada *form*. Klik **Save** untuk menyimpan
    > perubahan pada *form* memorandum. Surat yang disimpan akan
    > tersimpan di menu "**Draft -- Memorandum"**

> ![](.//media/image122.png){width="5.439930008748906in"
> height="2.6458333333333335in"}

5.  Klik **Edit Content** untuk mengubah isi memorandum

> ![](.//media/image123.png){width="5.458333333333333in"
> height="2.6547845581802276in"}

6.  Sistem menampilkan tampilan *preview* memorandum dalam bentuk Word
    > yang dapat di edit. Untuk melakukan *editing* terhadap isi surat
    > klik **Edit Content** kemudian sistem akan menampilkan *pop up*
    > konfirmasi **Ubah Word Desktop** atau **Ubah *Online***

> ![](.//media/image109.png){width="5.47959208223972in"
> height="2.6435247156605426in"}

##### \[Edit\] Word Desktop

> Langkah -- langkah untuk mengubah isi memorandum melalui Word Desktop
> adalah sebagai berikut.

1.  Klik **Open in Dekstop App** untuk mengubah melalui aplikasi
    > Microsoft Word

> ![](.//media/image110.png){width="5.47959208223972in"
> height="2.6435247156605426in"}

2.  Lakukan perubahan pada isi surat. Klik **Close** pada aplikasi dan
    > isi surat akan otomatis tersimpan

> ![](.//media/image111.png){width="5.5in"
> height="2.9396128608923884in"}

##### \[Edit\] Ubah *Online*

> Langkah -- langkah untuk mengubah isi memorandum secara *online*
> adalah sebagai berikut.

1.  Ketika *Klik button Edit Content* maka secara otomatis akan membuka
    > dokumen dan bisa mengubah isi surat secara *online*

> ![](.//media/image112.png){width="5.486805555555556in"
> height="2.6506419510061243in"}

2.  Lakukan perubahan pada isi surat.

> ![](.//media/image112.png){width="5.486805555555556in"
> height="2.6506419510061243in"}

3.  Isi surat akan otomatis tersimpan. Jika surat akan disimpan sebagai
    > draft, maka klik **Close.**

> ![](.//media/image113.png){width="5.486805555555556in"
> height="2.6506419510061243in"}

4.  Surat yang sudah selesai diubah maka akan tersimpan di menu "**Draft
    > -- Memorandum"**

##### Kirim Memorandum

> Langkah -- langkah untuk mengirim memorandum adalah sebagai berikut.

1.  Pada tampilan *preview* memorandum, klik **Kirim** untuk mengirim
    > surat ke pejabat tujuan

> ![](.//media/image114.png){width="5.47959208223972in"
> height="2.64715769903762in"}

2.  Sistem menyimpan perubahan dan memorandum akan tersimpan di menu
    > "**Outbox - Memorandum**"

    1.  #### Melihat Informasi Lengkap Memorandum

**Role yang sesuai**

-   *Member User (*Pekerja*)*

-   *Approver*

-   *Reviewer*

> *User* dapat melihat informasi lengkap memorandum termasuk *preview*
> memorandum, detail memorandum, *tracking* memorandum dan *history*
> memorandum. Langkah-langkah untuk melihat informasi memorandum adalah
> sebagai berikut.

1.  Klik menu **Inbox/Draft/Outbox** dan pilih tab **Memorandum.** Pilih
    > salah satu memorandum yang akan dilihat informasinya

> ![](.//media/image124.png){width="5.4375in"
> height="2.64465113735783in"}

##### Preview Memorandum

> Pada *button* *Preview* memorandum, ditampilkan *preview* memorandum
> yang sudah dibuat. *Preview* memorandum disesuaikan dengan template
> berdasarkan jenis surat
>
> ![](.//media/image125.png){width="5.25in"
> height="2.5534569116360455in"}
>
> ![](.//media/image126.png){width="5.2653062117235345in"
> height="2.543637357830271in"}

##### Detail Memorandum

> Pada tab Detail memorandum, terdapat informasi asal surat, perihal,
> file lampiran, nomor surat, klasifikasi surat, tanggal surat, tujuan
> surat dan *reviewer*
>
> ![](.//media/image127.png){width="5.229166666666667in"
> height="2.5433245844269465in"}

##### Tracking Memorandum

> Pada tab *tracking* memorandum, ditampilkan informasi *tracking*
> memorandum dalam bentuk *chart*
>
> ![](.//media/image128.png){width="5.270833333333333in"
> height="2.5635892388451444in"}

##### History Memorandum

> Pada tab *History* memorandum, ditampilkan riwayat memorandum yang
> terdapat informasi jabatan, tanggal, tindakan dan komentar
>
> ![](.//media/image129.png){width="5.2555555555555555in"
> height="2.556159230096238in"}

#### Menyetujui Memorandum

**Role yang sesuai**

-   *Reviewer*

-   *Approver*

*User* dapat menyetujui memorandum yang sudah dilakukan review dan
memorandum akan dikirimkan ke *reviewer* selanjutnya atau *approver*.
Langkah-langkah untuk menyetujui memorandum adalah sebagai berikut:

1.  Klik menu **Inbox** dan pilih tab **Memorandum**

> ![](.//media/image130.png){width="5.459550524934383in"
> height="2.6354166666666665in"}

2.  Pilih memorandum yang akan ditindak lanjuti kemudian pilih tab
    > **Detail**

> ![](.//media/image131.png){width="5.459553805774278in"
> height="2.6354166666666665in"}

3.  Klik tombol **Setujui** dan pilih **Send.** Isikan komentar jika
    > diperlukan

> ![](.//media/image132.png){width="5.480073272090989in"
> height="2.65625in"}

4.  Sistem berhasil menyimpan perubahan. Memorandum yang sudah di kirim
    > akan tersimpan di menu **Outbox- Memorandum**

    1.  #### Kembalikan Memorandum ke Sebelumnya

**Role yang sesuai**

-   *Reviewer*

-   *Approver*

> *User* dapat mengembalikan memorandum ke sebelumnya jika hasil review
> belum / tidak sesuai. Surat akan dikembalikan ke satu level *reviewer*
> sebelumnya atau ke konseptor (apabila hanya ada satu *reviewer*).
> Langkah-langkah untuk mengembalikan memorandum ke sebelumnya adalah
> sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Memorandum**

> ![](.//media/image130.png){width="5.459550524934383in"
> height="2.6354166666666665in"}

2.  Pilih memorandum yang akan ditindak lanjuti kemudian pilih tab
    > **Detail**

> ![](.//media/image131.png){width="5.459553805774278in"
> height="2.6354166666666665in"}

3.  Klik tombol **Return Previus** dan pilih **Send.** Isikan komentar
    > jika diperlukan

> ![](.//media/image133.png){width="5.459027777777778in"
> height="2.6514938757655293in"}

4.  Sistem berhasil menyimpan perubahan. Memorandum yang sudah di kirim
    > akan tersimpan di menu **Outbox- Memorandum** dan penerima
    > pengembalian memorandum akan menerima memorandum di menu
    > **Rejected - Memorandum**

    1.  #### Kembalikan Memorandum ke Konseptor

**Role yang sesuai**

-   *Reviewer*

-   *Approver*

> *User* dapat mengembalikan memorandum ke konseptor jika hasil review
> belum/tidak sesuai. Langkah-langkah untuk mengembalikan memorandum ke
> konseptor adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Memorandum**

> ![](.//media/image130.png){width="5.459550524934383in"
> height="2.6354166666666665in"}

2.  Pilih memorandum yang akan ditindak lanjuti kemudian pilih tab
    > **Detail**

> ![](.//media/image131.png){width="5.459553805774278in"
> height="2.6354166666666665in"}

3.  Klik tombol **Return Conceptor** dan pilih **Send.** Isikan komentar
    > jika diperlukan

> ![](.//media/image134.png){width="5.458333333333333in"
> height="2.6360378390201227in"}

4.  Sistem berhasil menyimpan perubahan. Memorandum yang sudah di kirim
    > akan tersimpan di menu **Outbox- Memorandum** dan konseptor akan
    > menerima memorandum di menu **Rejected -- Memorandum**

    1.  #### Menolak Memorandum

**Role yang sesuai**

-   *Reviewer*

-   *Approver*

> *User* dapat menolak memorandum yang akan dikemnbalikan ke konseptor
> jika hasil review memorandum belum / tidak sesuai. Langkah-langkah
> untuk menolak memorandum adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Memorandum**

> ![](.//media/image130.png){width="5.459550524934383in"
> height="2.6354166666666665in"}

2.  Pilih memorandum yang akan ditindak lanjuti kemudian pilih tab
    > **Detail**

> ![](.//media/image131.png){width="5.459553805774278in"
> height="2.6354166666666665in"}

3.  Klik tombol **Reject** dan pilih **Send.** Isikan komentar jika
    > diperlukan

> ![](.//media/image135.png){width="5.459027777777778in"
> height="2.646654636920385in"}

4.  Sistem berhasil menyimpan perubahan. Memorandum yang sudah di tolak
    > akan terhapus dari aplikasi secara *soft delete.*

    1.  #### Menambah Reviewer Baru Memorandum

**Role yang sesuai**

-   *Approver*

> *User* dapat menambahkan reviewer kemudian memorandum akan diteruskan
> ke reviewer baru. Langkah-langkah untuk menambah reviewer memorandum
> adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Memorandum**

> ![](.//media/image130.png){width="5.459550524934383in"
> height="2.6354166666666665in"}

2.  Pilih memorandum yang akan ditindak lanjuti kemudian pilih tab
    > **Detail**

> ![](.//media/image131.png){width="5.459553805774278in"
> height="2.6354166666666665in"}

3.  Klik tombol **Add Reviewer** dan pilih pejabat yang akan melakukan
    > review dengan meng-klik tombol "+" pada field **Add Reviewer**

> ![](.//media/image136.png){width="5.4527777777777775in"
> height="2.6309383202099736in"}

4.  Sistem akan menampilkan pejabat untuk dijadikan reviewer baru

> ![](.//media/image137.png){width="5.4375in"
> height="2.6283858267716536in"}

5.  Pilih **Send** untuk mengirimkan kepada pejabat/reviewer yang dituju
    > dan memorandum akan tersimpan di menu "**Outbox - Memorandum**".
    > Untuk pejabat/reviewer baru akan menerima memorandum di menu
    > "**Inbox -- Memorandum**"

> ![](.//media/image138.png){width="5.4534722222222225in"
> height="2.630668197725284in"}

#### Mengesahkan Nomor Memorandum

**Role yang sesuai**

-   *Approver (*Pemilik KBO*)*

> *User* dapat mengesahkan memorandum yang sudah dikirim dan direview
> oleh reviewer. Keluaran untuk tindak lanjut ini adalah untuk
> men-*generate* nomor memorandum kemudian memorandum dapat dikirimkan
> ke pejabat tujuan. Langkah-langkah untuk menambah reviewer memorandum
> adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Memorandum**

> ![](.//media/image130.png){width="5.459550524934383in"
> height="2.6354166666666665in"}

2.  Pilih memorandum yang akan ditindak lanjuti kemudian pilih tab
    > **Detail.** Pada tab **Detail** terdapat informasi nomor surat
    > yang masih bersifat sementara. Nomor inilah yang akan
    > ter-*generate* jika *user* menyetujui memorandum.

> ![](.//media/image139.png){width="5.4534722222222225in"
> height="2.6524201662292213in"}

3.  Klik **Approve** kemudian pilih **Send**

> ![](.//media/image132.png){width="5.480073272090989in"
> height="2.65625in"}

4.  Sistem menyimpan perubahan dan nomor memorandum akan ter-*generate*
    > sesuai dengan nomor sementara pada detail. Memorandum yang sudah
    > diseyujui akan tersimpan di menu "**Outbox - Memorandum**"
    > pengirim sedangkan memorandum akan tersimpan di menu "**Inbox -
    > Memorandum**" penerima

    1.  #### Mendisposisikan Memorandum

**Role yang sesuai**

-   *Approver User* (Pemilik KBO)

-   *Reviewer User*

> *User* menerima memorandum yang sudah dikirimkan pejabat internal
> Pertamina pada menu "**Inbox - Memorandum**". Memorandum dapat
> didisposisikan kepada pejabat yang dipilih atau pejabat yang ada
> dibawahnya. Disposisi memorandum dapat dilakukan dengan dua cara yaitu
> melalui menu **Inbox** jika memorandum yang diterima merupakan
> memorandum yang ditujukan kepada tujuan pejabat internal Pertamina dan
> telah disetujui atau ditanda tangani oleh pejabat pengirim atau
> melalui menu **Disposisi** jika memorandum sudah dilakukan tindak
> lanjut oleh pejabat pemilik KBO dan pemilik KBO akan mendisposisikan
> ke pejabat selanjutnya atau pejabat yang ada dibawahnya.
> Langkah-langkah untuk mendisposisikan memorandum adalah sebagai
> berikut:

##### Disposisi melalui Menu Inbox

1.  Klik menu **Inbox** dan pilih tab **Memorandum**

> ![](.//media/image130.png){width="5.459550524934383in"
> height="2.6354166666666665in"}

2.  Pilih memorandum yang akan didisposisikan kemudian pilih tab
    > **Detail**

> ![](.//media/image131.png){width="5.459553805774278in"
> height="2.6354166666666665in"}

3.  Klik tombol **Disposition** dan pilih **Send**

> ![](.//media/image140.png){width="5.459027777777778in"
> height="2.6569367891513562in"}

4.  Sistem menampilkan form disposisi. Isikan informasi disposisi dan
    > perintah untuk masing-masing penerima disposisi.

> ![](.//media/image141.png){width="5.459027777777778in"
> height="2.627299868766404in"}

5.  Klik **Save** untuk menyimpan draft disposisi memorandum dan
    > memorandum akan tersimpan di menu "**Draft -- Memorandum**". Klik
    > **Send** untuk mengirim disposisi ketujuan dan disposisi
    > memorandum akan tersimpan di menu "**Outbox -- Disposisi**".

##### Disposisi melalui Menu Inbox

1.  Klik menu **Disposisi** dan pilih tab **Memorandum**

> ![](.//media/image130.png){width="5.459550524934383in"
> height="2.6354166666666665in"}

2.  Pilih memorandum yang akan didisposisikan kemudian pilih tab
    **Detail**

> ![](.//media/image131.png){width="5.459553805774278in"
> height="2.6354166666666665in"}

3.  Klik tombol **Disposisi** dan pilih **Send**

> ![](.//media/image140.png){width="5.459027777777778in"
> height="2.6569367891513562in"}

4.  Sistem menampilkan form disposisi. Isikan informasi disposisi dan
    perintah untuk masing-masing penerima disposisi.

> ![](.//media/image141.png){width="5.459027777777778in"
> height="2.627299868766404in"}

5.  Klik **Save** untuk menyimpan draft disposisi memorandum dan
    memorandum akan tersimpan di menu "**Draft -- Memorandum**". Klik
    **Send** untuk mengirim disposisi ketujuan dan disposisi memorandum
    akan tersimpan di menu "**Outbox -- Disposisi**".

    1.  #### Melakukan Custom Disposisi Memorandum

**Role yang sesuai**

-   *Approver User*

-   *Reviewer User*

> *User* dapat melakukan *custom* penerima disposisi terhadap pejabat
> penerima yang akan menerima perintah disposisi. Secara *default*
> pejabat yang akan menerima disposisi adalah pejabat yang ada
> dibawahnya. Tetapi terdapat *case* jika *user* membutuhkan *custom*
> penerima disposisi sehingga disediakan fitur untuk memilih pejabat
> selain pejabat yang ada dibawahnya. Langkah-langkah untuk melakukan
> *custom* disposisi memorandum adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Memorandum**

> ![](.//media/image130.png){width="5.459550524934383in"
> height="2.6354166666666665in"}

2.  Pilih memorandum yang akan didisposisikan kemudian pilih tab
    > **Detail**

> ![](.//media/image131.png){width="5.459553805774278in"
> height="2.6354166666666665in"}

3.  Klik tombol **Disposisi** dan pilih **Send**

> ![](.//media/image140.png){width="5.459027777777778in"
> height="2.6569367891513562in"}

4.  Sistem menampilkan form disposisi. Klik icon "+" pada field
    > **Forward To.** Isikan informasi disposisi dan perintah untuk
    > masing-masing penerima disposisi.

> ![](.//media/image142.png){width="5.447916666666667in"
> height="2.6219542869641295in"}

5.  Sistem menampilkan daftar pejabat yang dapat dipilih untuk
    > didisposikan

> ![](.//media/image143.png){width="5.475891294838145in"
> height="2.6354166666666665in"}

6.  Isikan perintah dan keterangan pada masing-masing penerima
    > disposisi. Tambahkan lampiran disposisi jika diperlukan. Fitur
    > **Komentar Sama Untuk Semua** dapat digunakan *user* untuk
    > memberikan komentar yang sama untuk masing-masing pejabat penerima
    > disposisi. Klik **Simpan** untuk menyimpan perubahan dan klik
    > **Send** untuk mengirim disposisi.

> ![](.//media/image144.png){width="5.454248687664042in"
> height="2.625in"}

#### Melihat Informasi Lengkap Disposisi Memorandum

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat melihat informasi lengkap disposisi memorandum pada
> detail disposisi. Langkah-langkah untuk melihat informasi disposisi
> memorandum adalah sebagai berikut.

1.  Klik menu **Disposisi** dan pilih tab **Memorandum.** Pilih salah
    > satu disposisi memorandum yang akan dilihat informasinya

> ![](.//media/image145.png){width="5.440972222222222in"
> height="2.618611111111111in"}

##### Preview Memorandum

> Pada button **Mail** memorandum, ditampilkan preview memorandum yang
> sudah dibuat. Preview memorandum disesuaikan dengan template
> berdasarkan jenis surat
>
> ![](.//media/image146.png){width="5.28125in"
> height="2.5417399387576554in"}

##### Preview Lembar Penerus

> Pada tab **Preview Lembar Penerus,** ditampilkan informasi lembar
> penerus disposisi yang berisi informasi daftar nama pejabat dan
> perintah disposisi yang harus dilakukan oleh pejabat penerima
> disposisi
>
> ![](.//media/image147.png){width="5.291666666666667in"
> height="2.6224442257217846in"}

##### Detail Memorandum

> Pada tab **Detail Memorandum**, terdapat informasi asal surat,
> perihal, file lampiran, nomor surat, klasifikasi surat, tanggal surat
> dan tujuan surat serta informasi disposisi yang mencakup lampiran
> disposisi, tujuan, tindak lanjut dan disposisi permasing-masing
> pejabat penerima disposisi
>
> ![](.//media/image148.png){width="5.270833333333333in"
> height="2.544317585301837in"}

##### Tracking Memorandum

> Pada tab *Tracking* memorandum, ditampilkan informasi *tracking*
> memorandum dalam bentuk *chart*
>
> ![](.//media/image149.png){width="5.278472222222222in"
> height="2.5480063429571302in"}

##### History Memorandum

> Pada tab *History* memorandum, ditampilkan riwayat memorandum yang
> terdapat informasi jabatan, tanggal, tindakan dan komentar
>
> ![](.//media/image150.png){width="5.278472222222222in"
> height="2.5482491251093613in"}

#### Menolak Disposisi Memorandum

**Role yang sesuai**

-   *Approver User*

-   *Reviewer User*

> Langkah-langkah untuk menolak memorandum adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Memorandum**

> ![](.//media/image151.png){width="5.511111111111111in"
> height="2.660557742782152in"}

2.  Pilih memorandum yang akan ditolak kemudian pilih tab **Detail**

> ![](.//media/image152.png){width="5.458333333333333in"
> height="2.6350787401574802in"}

3.  Klik tombol **Reject** dan pilih **Send.** Isikan komentar jika
    > diperlukan

> ![](.//media/image153.png){width="5.489583333333333in"
> height="2.669575678040245in"}

4.  Sistem menampilkan pop up konfirmasi dan *user* harus mengisi
    > keterangan tolak disposisi memorandum kemudian klik **Save**.

> ![](.//media/image154.png){width="5.47337489063867in"
> height="2.65625in"}

5.  Sistem menyimpan perubahan dan disposisi memorandum yang sudah
    > ditolak akan otomatis terhapus secara *soft delete.*

    1.  #### Melakukan Recall Disposisi Memorandum

**Role yang sesuai**

-   *Approver User*

-   *Reviewer User*

> *User* dapat melakukan *recall* / tarik disposisi memorandum yang
> sudah dikirim kepada pejabat penerima disposisi. Memorandum yang sudah
> dikirim ke pejabat penerima disposisi akan tersimpan di menu "**Outbox
> Disposisi**". Langkah-langkah untuk melakukan *recall* disposisi
> memorandum adalah sebagai berikut

1.  Klik menu **Outbox** dan pilih tab **Disposisi**

> ![](.//media/image155.png){width="5.488194444444445in"
> height="2.643429571303587in"}

2.  Pilih memorandum yang akan di-*recall* kemudian klik tab **Detail**
    > kemudian klik ***Recall*.** Memorandum yang sudah di-*recall* akan
    > tersimpan di menu "**Draft - Disposisi**"

> ![](.//media/image156.png){width="5.493186789151356in"
> height="2.6458333333333335in"}

#### Menyelesaikan Disposisi Memorandum

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat menyelesaikan disposisi memorandum jika *user* tidak akan
> melanjutkan untuk mendisposisikan memorandum ke pejabat lain atau
> memorandum selesai pada *user* tersebut. Langkah-langkah untuk
> menyelesaikan memorandum adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Memorandum**

> ![](.//media/image157.png){width="5.479166666666667in"
> height="2.6390813648293965in"}

2.  Pilih memorandum yang akan diselesaikan kemudian pilih tab
    > **Detail**

> ![](.//media/image158.png){width="5.489583333333333in"
> height="2.6440988626421698in"}

3.  Pilih tombol **Finish** kemudian klik **Send**

> ![](.//media/image159.png){width="5.479166666666667in"
> height="2.6566382327209097in"}

4.  Sistem menampilkan pop up konfirmasi dan *user* harus mengisi
    > keterangan selesaikan disposisi kemudian klik **Save**.

> ![](.//media/image160.png){width="5.489583333333333in"
> height="2.6538035870516183in"}

5.  Sistem menyimpan perubahan dan informasi selesai disposisi akan
    > tersimpan di detail disposisi.

    1.  #### Mengirim Tanggapan Disposisi Memorandum

**Role yang sesuai**

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat mengirim tanggapan disposisi memorandum yang ditujukan
> untuk pejabat pengirim disposisi. Langkah-langkah untuk mengirim
> tanggapan disposisi memorandum adalah sebagai berikut

1.  Klik menu **Disposisi** dan pilih tab **Memorandum**

> ![](.//media/image161.png){width="5.479166666666667in"
> height="2.6415048118985127in"}

2.  Pilih memorandum yang akan diselesaikan kemudian pilih tab
    > **Detail**

> ![](.//media/image162.png){width="5.488145231846019in"
> height="2.6458333333333335in"}

3.  Pilih tombol **Send Response** kemudian klik **Send**

> ![](.//media/image163.png){width="5.4875in"
> height="2.645521653543307in"}
>
> ![](.//media/image164.png){width="5.510416666666667in"
> height="2.6565693350831148in"}

4.  Sistem menampilkan pop up konfirmasi dan *user* harus mengisi
    > keterangan kirim tanggapan disposisi kemudian klik **Save**.

> ![](.//media/image165.png){width="5.5in" height="2.651547462817148in"}

5.  Sistem menyimpan perubahan dan informasi tanggapan disposisi akan
    > tersimpan di detail disposisi.

    1.  ### Fax Masuk

> Pada modul ini mendukung proses penambahan fax masuk oleh sekretaris
> atau pekerja yang ditunjuk dari pejabat yang bersangkutan. Fax masuk
> yang sudah diinputkan akan dikirimkan kepada pejabat pemilik KBO dan
> dapat dilakukan disposisi kepada pejabat yang ada di bawahnya.

#### Melihat Daftar Fax Masuk

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat melihat daftar fax masuk yang ditujukan pada sekretaris
> tersebut. Langkah-langkah untuk melihat daftar fax masuk adalah
> sebagai berikut.

1.  Klik menu **Inbox/Draft/Outbox** dan pilih tab **Fax Masuk**. Sistem
    > akan menampilkan daftar fax masuk yang ditujukan pada sekretaris

> ![](.//media/image166.png){width="5.479166666666667in"
> height="2.641503718285214in"}

#### Menambah Fax Masuk

**Role yang sesuai**

-   Sekretaris

> Sekretaris dapat menambah fax masuk pada aplikasi P-Office.
> Langkah-langkah untuk menambah fax masuk adalah sebagai berikut

1.  Klik menu **New Correspondence**

> ![](.//media/image167.png){width="5.479166666666667in"
> height="2.641503718285214in"}

2.  Pilih jenis surat "**Fax Masuk**"

> ![](.//media/image168.png){width="5.486805555555556in"
> height="2.6451870078740156in"}

3.  Isi form tambah fax masuk. Klik **Save** untuk menyimpan form surat
    > dan surat akan tersimpan di menu "**Draft -- Fax Masuk**". Klik
    > **Save** untuk mengirim fax masuk dan fax masuk akan tersimpan di
    > menu "**Outbox -- Fax Masuk**"

> ![](.//media/image169.png){width="5.458333333333333in"
> height="2.6314599737532807in"}
>
> ![](.//media/image170.png){width="5.46875in"
> height="2.6364818460192474in"}

4.  Sistem berhasil menyimpan perubahan

    1.  #### Melakukan Drafting Fax Masuk

**Role yang sesuai**

-   Sekretaris

> Sekretaris dapat melakukan *drafting* fax masuk pada aplikasi
> P-Office. *Drafting* fax masuk dilakukan jika *user* akan meneruskan
> dan melakukan perubahan pada fax masuk yang sudah disimpan pada menu
> **Draft.**

Langkah-langkah untuk melakukan *drafting* fax masuk adalah sebagai
berikut.

1.  Klik menu **Draft** dan pilih tab **Fax Masuk**

> ![](.//media/image171.png){width="5.479166666666667in"
> height="2.641503718285214in"}

2.  Pilih fax masuk yang akan diubah. Pilih tab **Detail** kemudian klik
    > **Edit**

> ![](.//media/image172.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

3.  Sistem akan menampilkan *form* **Edit Correspondence**

> ![](.//media/image173.png){width="5.466541994750656in"
> height="2.6354166666666665in"}
>
> ![](.//media/image174.png){width="5.5in" height="2.651547462817148in"}

4.  Lakukan perubahan pada *form*.Klik **Save** untuk menyimpan surat
    > dan Klik **Send** untuk mengirim fax masuk ke pejabat tujuan.
    > Surat yang tersimpan akan ada di "**Draf -- Fax Masuk"** dan surat
    > yang terkirim akan tersimpan di menu "**Outbox -- Fax masuk"**

    1.  #### Melihat Informasi Lengkap Fax Masuk

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat melihat informasi lengkap fax masuk termasuk *preview*
> fax masuk, detail fax masuk, *tracking* fax masuk dan *history* fax
> masuk. Langkah-langkah untuk melihat informasi fax masuk adalah
> sebagai berikut.

1.  Klik menu **Inbox/Draft/Outbox** dan pilih tab **Fax masuk.** Pilih
    > salah satu fax masuk yang akan dilihat informasinya

> ![](.//media/image171.png){width="5.479166666666667in"
> height="2.641503718285214in"}

##### Preview Fax Masuk

> Pada *button* **Preview Fax Masuk**, ditampilkan *preview* fax masuk
> yang merupakan hasil unggahan yang diinputkan oleh
> sekretaris/konseptor.
>
> ![](.//media/image175.png){width="5.270833333333333in"
> height="2.541066272965879in"}

##### Detail Fax Masuk

> Pada tab **Detail Fax Masuk**, terdapat informasi asal surat, perihal,
> file lampiran, kategori surat, resume, rekomendasi, nomor surat,
> klasifikasi surat, tanggal surat dan tujuan.
>
> ![](.//media/image176.png){width="5.270833333333333in"
> height="2.541066272965879in"}

##### Tracking Fax Masuk

> Pada tab **Tracking Fax Masuk**, ditampilkan informasi *tracking* fax
> masuk dalam bentuk *chart*
>
> ![](.//media/image177.png){width="5.260416666666667in"
> height="2.5360444006999123in"}

##### History Fax Masuk

> Pada tab **History Fax Masuk**, ditampilkan riwayat fax masuk yang
> terdapat informasi jabatan, tanggal, tindakan dan komentar
>
> ![](.//media/image178.png){width="5.28125in"
> height="2.5460892388451444in"}

#### Menolak Fax Masuk

**Role yang sesuai**

-   *Approver (*Pemilik KBO*)*

> Langkah-langkah untuk menolak fax masuk adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Fax Masuk**

> ![](.//media/image179.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

2.  Pilih fax masuk yang akan ditolak kemudian pilih tab **Detail**

> ![](.//media/image180.png){width="5.5in" height="2.651547462817148in"}

3.  Klik tombol **Reject** dan pilih **Send.** Isikan komentar jika
    > diperlukan

> ![](.//media/image181.png){width="5.479166666666667in"
> height="2.641505905511811in"}

4.  Sistem menampilkan *pop up* konfirmasi dan *user* harus mengisi
    > keterangan tolak fax masuk kemudian klik **Reject Fax**.

> ![](.//media/image182.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

5.  Sistem menyimpan perubahan dan informasi tolak fax masuk. Fax masuk
    > yang sudah ditolak akan akan terhapus dari aplikasi secara *soft
    > delete.*

    1.  #### Menyelesaikan Fax Masuk

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat menyelesaikan fax masuk jika *user* tidak akan
> melanjutkan untuk mendisposisikan fax masuk ke pejabat lain atau fax
> masuk selesai pada *user* tersebut. Langkah-langkah untuk
> menyelesaikan fax masuk adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Fax Masuk**

> ![](.//media/image179.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

2.  Pilih fax masuk yang akan diselesaikan kemudian pilih tab **Detail**

> ![](.//media/image180.png){width="5.5in" height="2.651547462817148in"}

3.  Pilih tombol **Finish** kemudian klik **Send**

> ![](.//media/image183.png){width="5.489583333333333in"
> height="2.6465244969378827in"}

4.  Sistem menampilkan *pop up* konfirmasi dan *user* harus mengisi
    > keterangan selesaikan disposisi kemudian klik **Save**.

> ![](.//media/image184.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

5.  Sistem menyimpan perubahan dan informasi selesai disposisi akan
    > tersimpan di detail disposisi.

    1.  #### Melihat Daftar Disposisi Fax Masuk

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat melihat daftar fax masuk pada pada menu **Disposisi**
> pada masing-masing akun. Langkah -- langkah untuk melihat daftar fax
> masuk adalah sebagai berikut

1.  Klik menu **Disposisi** dan pilih tab **Fax Masuk**

> ![](.//media/image185.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

#### Mendisposisikan Fax Masuk

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

> *User* menerima fax masuk baru di menu "**Inbox - Fax Masuk**". Fax
> masuk dapat didisposisikan kepada pejabat yang dipilih atau pejabat
> yang ada dibawahnya. Disposisi fax masuk dapat dilakukan dengan dua
> cara yaitu melalui menu **Inbox** jika fax masuk yang diterima
> merupakan surat masuk yang ditujukan langsung dari sekretaris ke
> pejabat pemilik KBOnya atau melalui menu **Disposisi** jika fax masuk
> sudah dilakukan tindak lanjut oleh pejabat pemilik KBO dan pemilik KBO
> akan mendisposisikan ke pejabat selanjutnya atau pejabat yang ada
> dibawahnya. Langkah-langkah untuk mendisposisikan fax masuk adalah
> sebagai berikut:

##### Disposisi melalui Menu Inbox

1.  Klik menu **Inbox** dan pilih tab **Fax Masuk**

> ![](.//media/image186.png){width="5.458333333333333in"
> height="2.6314610673665793in"}

2.  Pilih fax masuk yang akan didisposisikan kemudian pilih tab
    > **Detail**

> ![](.//media/image187.png){width="5.479166666666667in"
> height="2.641503718285214in"}

3.  Klik tombol **Disposition** dan pilih **Send**

> ![](.//media/image188.png){width="5.479166666666667in"
> height="2.641503718285214in"}

4.  Sistem menampilkan form disposisi. Isikan informasi disposisi dan
    > perintah untuk masing-masing penerima disposisi.

> ![](.//media/image189.png){width="5.479166666666667in"
> height="2.641503718285214in"}

5.  Klik **Save** untuk menyimpan draft disposisi surat masuk dan surat
    > masuk akan tersimpan di menu "**Draft -- Surat masuk**". Klik
    > **Send** untuk mengirim disposisi ketujuan dan disposisi surat
    > masuk akan tersimpan di menu "**Outbox -- Disposisi**".

##### Disposisi melalui Menu Disposisi

1.  Klik menu **Disposisi** dan pilih tab **Fax Masuk**

> ![](.//media/image190.png){width="5.476388888888889in"
> height="2.640165135608049in"}

2.  Pilih fax masuk yang akan didisposisikan kemudian pilih tab
    > **Detail**

> ![](.//media/image191.png){width="5.476388888888889in"
> height="2.6437959317585302in"}

3.  Klik tombol **Disposition** dan pilih **Send**

> ![](.//media/image192.png){width="5.5in" height="2.651547462817148in"}
>
> ![](.//media/image193.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

4.  Sistem menampilkan form disposisi. Isikan informasi disposisi dan
    > perintah untuk masing-masing penerima disposisi.

> ![](.//media/image194.png){width="5.5in" height="2.651547462817148in"}

5.  Klik **Save** untuk menyimpan draft disposisi fax masuk dan fax
    > masuk akan tersimpan di menu "**Draft -- Surat masuk**". Klik
    > **Send** untuk mengirim disposisi ketujuan dan disposisi surat
    > masuk akan tersimpan di menu "**Outbox -- Disposisi**".

    1.  #### Melakukan Custom Disposisi

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

> *User* dapat melakukan *custom* penerima disposisi terhadap pejabat
> penerima yang akan menerima perintah disposisi. Secara *default*
> pejabat yang akan menerima disposisi adalah pejabat yang ada
> dibawahnya. Tetapi terdapat *case* jika *user* membutuhkan *custom*
> penerima disposisi sehingga disediakan fitur untuk memilih pejabat
> selain pejabat yang ada dibawahnya. Langkah-langkah untuk melakukan
> *custom* disposisi fax masuk adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Fax Masuk**

> ![](.//media/image195.png){width="5.458333333333333in"
> height="2.6314599737532807in"}

2.  Pilih fax masuk yang akan didisposisikan kemudian pilih tab
    > **Detail**

> ![](.//media/image196.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

3.  Klik tombol **Disposition** dan pilih **Send**

> ![](.//media/image197.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

4.  Sistem menampilkan form disposisi. Klik icon "+" pada field
    > **Forward To.** Isikan informasi disposisi dan perintah untuk
    > masing-masing penerima disposisi.

> ![](.//media/image198.png){width="5.5in" height="2.651547462817148in"}

5.  Sistem menampilkan daftar pejabat yang dapat dipilih untuk
    > didisposikan

> ![](.//media/image199.png){width="5.46875in"
> height="2.6364818460192474in"}

6.  Isikan perintah dan keterangan pada masing-masing penerima
    > disposisi. Tambahkan lampiran disposisi jika diperlukan. Fitur
    > **Same All Comment** dapat digunakan *user* untuk memberikan
    > komentar yang sama untuk masing-masing pejabat penerima disposisi.
    > Klik **Save** untuk menyimpan perubahan dan klik **Send** untuk
    > mengirim disposisi.

> ![](.//media/image200.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

#### Melihat Informasi Lengkap Disposisi Fax Masuk

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat melihat informasi lengkap fax masuk termasuk *preview*
> fax masuk, lembar penerus disposisi, detail fax masuk, *tracking* fax
> masuk dan *history* fax masuk. Langkah-langkah untuk melihat informasi
> fax masuk adalah sebagai berikut.

1.  Klik menu **Disposisi** dan pilih tab **Fax Masuk.** Pilih salah
    > satu fax masuk yang akan dilihat informasinya

> ![](.//media/image201.png){width="5.46875in"
> height="2.6364807524059493in"}

##### Preview Fax Masuk

> Pada *button* **Mail** Fax Masuk, ditampilkan informasi fax masuk
> fisik yang sudah di *scan* dan kemudian diunggah oleh sekretaris /
> konseptor
>
> ![](.//media/image202.png){width="5.260416666666667in"
> height="2.5360444006999123in"}
>
> ![](.//media/image203.png){width="5.260416666666667in"
> height="2.5360444006999123in"}

##### Preview Lembar Penerus

> Pada tab **Preview Lembar Penerus,** ditampilkan informasi lembar
> penerus disposisi yang berisi informasi daftar nama pejabat dan
> perintah disposisi yang harus dilakukan oleh pejabat penerima
> disposisi
>
> ![](.//media/image204.png){width="5.260416666666667in"
> height="2.5360444006999123in"}
>
> ![](.//media/image205.png){width="5.28125in"
> height="2.5460881452318462in"}

##### Detail Fax Masuk

> Pada tab **Detail Fax Masuk**, terdapat informasi asal surat, perihal,
> file lampiran, nomor surat, klasifikasi surat, tanggal surat dan
> tujuan surat serta informasi disposisi yang mencakup lampiran
> disposisi, tujuan, tindak lanjut dan disposisi permasing-masing
> pejabat penerima disposisi
>
> ![](.//media/image206.png){width="5.291666666666667in"
> height="2.551110017497813in"}

##### Tracking Fax Masuk

> Pada tab *Tracking* fax masuk, ditampilkan informasi *tracking* fax
> masuk dalam bentuk *chart*
>
> ![](.//media/image207.png){width="5.270833333333333in"
> height="2.541066272965879in"}

##### History Fax Masuk

> Pada tab *History* fax masuk, ditampilkan riwayat fax masuk yang
> terdapat informasi jabatan, tanggal, tindakan dan komentar
>
> ![](.//media/image208.png){width="5.28125in"
> height="2.5460881452318462in"}

#### Melakukan Recall Disposisi Fax Masuk

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

> *User* dapat melakukan *recall* / tarik disposisi fax masuk yang sudah
> dikirim kepada pejabat penerima disposisi. Fax masuk yang sudah
> dikirim ke pejabat penerima disposisi akan tersimpan di menu "**Outbox
> - Disposisi**" Langkah-langkah untuk melakukan *recall* disposisi fax
> masuk adalah sebagai berikut

1.  Klik menu **Outbox** dan pilih tab **Disposisi**

> ![](.//media/image209.png){width="5.488145231846019in"
> height="2.6458333333333335in"}

2.  Pilih fax masuk yang akan di-*recall* kemudian klik tab **Detail**
    > kemudian klik **Recall.**

> ![](.//media/image210.png){width="5.458333333333333in"
> height="2.6314599737532807in"}

Fax masuk yang sudah di-*recall* akan tersimpan di menu "**Draft -
Disposisi**" penerima fax masuk / pendisposisi

#### Menyelesaikan Disposisi Fax Masuk

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat menyelesaikan disposisi fax masuk jika *user* tidak akan
> melanjutkan untuk mendisposisikan fax masuk ke pejabat lain.
> Langkah-langkah untuk menyelesaikan fax masuk adalah sebagai berikut

1.  Klik menu **Disposisi** dan pilih tab **Fax masuk**

> ![](.//media/image211.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

2.  Pilih disposisi yang akan diselesaikan kemudian pilih tab **Detail**

> ![](.//media/image212.png){width="5.46875in"
> height="2.6364818460192474in"}

3.  Pilih tombol **Finished** kemudian klik **Send**

> ![](.//media/image213.png){width="5.466543088363954in"
> height="2.6354166666666665in"}
>
> ![](.//media/image214.png){width="5.479166666666667in"
> height="2.641503718285214in"}

4.  Sistem menampilkan pop up konfirmasi dan *user* harus mengisi
    > keterangan selesaikan disposisi kemudian klik **Save**.

> ![](.//media/image215.png){width="5.488148512685914in"
> height="2.6458333333333335in"}

5.  Sistem menyimpan perubahan dan informasi selesai disposisi akan
    > tersimpan di detail disposisi.

    1.  #### Mengirim Tanggapan Disposisi Fax Masuk

**Role yang sesuai**

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat mengirim tanggapan disposisi fax masuk yang ditujukan
> untuk pejabat pengirim disposisi. Langkah-langkah untuk mengirim
> tanggapan disposisi fax masuk adalah sebagai berikut

1.  Klik menu **Disposisi** dan pilih tab **Fax Masuk**

> ![](.//media/image211.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

2.  Pilih disposisi yang akan dikirim tanggapan kemudian pilih tab
    > **Detail**

> ![](.//media/image212.png){width="5.46875in"
> height="2.6364818460192474in"}

3.  Pilih tombol **Send Response** kemudian klik **Send**

> ![](.//media/image216.png){width="5.479166666666667in"
> height="2.641503718285214in"}
>
> ![](.//media/image217.png){width="5.46875in"
> height="2.636482939632546in"}

4.  Sistem menampilkan pop up konfirmasi dan *user* harus mengisi
    > keterangan kirim tanggapan disposisi kemudian klik **Save**.

> ![](.//media/image218.png){width="5.479166666666667in"
> height="2.641503718285214in"}

5.  Sistem menyimpan perubahan dan informasi tanggapan disposisi akan
    > tersimpan di detail disposisi.

    1.  ### Fax Keluar

> Pada modul ini mendukung proses input fax keluar dengan tujuan
> eksternal Pertamina dan dapat ditujukan lebih dari satu tujuan.
> Pembuat konsep fax keluar atau disebut sebagai konseptor surat akan
> mengirimkan draf fax keluar untuk dicek oleh *reviewe*r dan disetujui
> oleh *approver*. Setelah fax sudah disetujui maka akan diberikan nomor
> fax keluar secara otomatis melalui sistem.

#### Melihat Daftar Fax Keluar

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat melihat daftar fax keluar pada pada menu **Inbox, Draft
> atau Outbox** pada masing-masing akun. Langkah -- langkah untuk
> melihat daftar fax keluar adalah sebagai berikut

1.  Klik menu **Inbox / Draft / Outbox** dan pilih tab **Fax Keluar**

> ![](.//media/image219.png){width="5.479166666666667in"
> height="2.641503718285214in"}

#### Menambah Fax Keluar

**Ditujukan kepada**

-   *Approver*

-   *Reviewer*

**Role yang sesuai**

-   *Member User (*Pekerja*)*

> Konseptor dapat menambah fax keluar pada aplikasi P-Office.
> Langkah-langkah untuk menambah fax keluar adalah sebagai berikut.

1.  Klik menu **New Correspondence**

> ![](.//media/image220.png){width="5.770833333333333in"
> height="2.7821139545056868in"}

2.  Pilih jenis surat "**Fax Keluar**"

![](.//media/image221.png){width="5.78125in"
height="2.787136920384952in"}

3.  Isi *form* tambah fax keluar. Terdapat bebarapa aksi untuk
    menindaklanjuti fax keluar yang sudah diisi *form*nya yaitu **Save
    Fax keluar**, **Send Fax keluar** dan **Save Template Fax keluar.**

![](.//media/image222.png){width="5.760416666666667in"
height="2.777093175853018in"}

![](.//media/image223.png){width="5.770833333333333in"
height="2.782115048118985in"}

##### Simpan Fax Keluar

Langkah -- langkah untuk menyimpan fax keluar adalah sebagai berikut.

1.  Isi *form* fax keluar kemudian klik **Save**

> ![](.//media/image224.png){width="5.458333333333333in"
> height="2.6314599737532807in"}

2.  Sistem akan menampilkan tampilan *preview* fax keluar dalam bentuk
    > Word yang dapat di edit. Untuk melakukan *editing* terhadap isi
    > surat klik **Edit Content** kemudian sistem akan menampilkan *pop
    > up* konfirmasi **Ubah Word Desktop** atau **Ubah *Online***

> ![](.//media/image225.png){width="5.46875in"
> height="2.6364818460192474in"}

##### \[Edit\] Word Desktop

> Langkah -- langkah untuk mengubah isi fax keluar melalui Word Desktop
> adalah sebagai berikut.

1.  Klik **Ubah di Word** untuk mengubah melalui aplikasi Microsoft Word

> ![](.//media/image225.png){width="5.458333333333333in"
> height="2.6314599737532807in"}

2.  Lakukan perubahan pada isi surat. Klik **Close** pada aplikasi dan
    > isi surat akan otomatis tersimpan

> ![](.//media/image226.png){width="5.46875in"
> height="2.90840769903762in"}

##### \[Edit\] Ubah *Online*

> Langkah -- langkah untuk mengubah isi fax keluar secara *online*
> adalah sebagai berikut.

1.  Ketika muncul surat hal tersebut untuk mengubah isi surat secara
    > *online*

> ![](.//media/image227.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

2.  Lakukan perubahan pada isi surat.

> ![](.//media/image228.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

3.  Isi surat akan otomatis tersimpan. Jika surat akan disimpan sebagai
    > draft, maka klik **Tutup.**

> ![](.//media/image229.png){width="5.520833333333333in"
> height="2.6615912073490815in"}

4.  Surat yang sudah selesai diubah maka akan tersimpan di menu "**Draft
    > -- Fax Keluar"**

##### Kirim Fax Keluar

> Langkah -- langkah untuk mengirim fax keluar adalah sebagai berikut.

1.  Pada tampilan *preview* fax keluar, klik **Kirim** untuk mengirim
    > surat ke pejabat tujuan

> ![](.//media/image230.png){width="5.458333333333333in"
> height="2.6314588801399825in"}

2.  Sistem menyimpan perubahan dan fax keluar akan tersimpan di menu
    > "**Outbox - Fax keluar**"

    1.  #### Save as Template Fax Keluar

**Ditujukan kepada**

-   *Approver*

-   *Reviewer*

**Role yang sesuai**

-   *Member User (*Pekerja*)*

*User* dapat menyimpan fax keluar sebagai *template*. *Template* ini
digunakan jika sewaktu-waktu *user* akan melanjutkan fax keluar yang
sudah dibuat dan diubah kembali kemudian dikirimkan kepejabat tujuan
tanpa harus mengisi *form* fax keluar. Langkah -- langkah untuk
menyimpan fax keluar sebagai *template* adalah sebagai berikut.

1.  Isi *form* fax keluar dan Klik **Save as Template**

> ![](.//media/image231.png){width="5.479166666666667in"
> height="2.641503718285214in"}

2.  Fax keluar yang disimpan menjadi *template* akan tersimpan di menu
    > "**Draft -- Fax Keluar".** Untuk melanjutkan *template* yang sudah
    > dibuat *user* dapat memilih menu "**Draft -- Fax Keluar**"
    > kemudian pilih *template* yang akan digunakan

> ![](.//media/image232.png){width="5.509758311461067in"
> height="2.65625in"}

3.  Pilih tombol ***User* Template** untuk melanjutkan edit fax keluar

> ![](.//media/image233.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

4.  Sistem akan menampilkan form **Edit Correspondence,** klik **Save**
    > untuk menyimpan perubahan

> ![](.//media/image234.png){width="5.46875in"
> height="2.6364818460192474in"}

5.  Lakukan perubahan pada fax, klik **Save** untuk menyimpan perubahan
    > dan fax keluar akan tersimpan di menu **"Draft -- Fax Keluar"**
    > sebagai draft atau klik **Send** untuk mengirimkan ke pejabat
    > tujuan dan tersimpan di menu **"Outbox -- Fax Keluar".**

    1.  #### Melakukan Drafting Fax Keluar

**Role yang sesuai**

-   Konseptor

-   *Approver*

-   *Reviewer*

> *User* dapat melakukan *drafting* fax keluar pada aplikasi P-Office.
> *Drafting* fax keluar dilakukan jika *user* akan meneruskan dan
> melakukan perubahan pada fax keluar yang sudah disimpan pada menu
> **Draft.** Langkah-langkah untuk melakukan *drafting* fax keluar
> adalah sebagai berikut.

1.  Klik menu **Draft** dan pilih tab **Fax Keluar**

> ![](.//media/image235.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

2.  Pilih fax keluar yang akan diubah. Pilih tab **Detail** kemudian
    > klik **Edit**

> ![](.//media/image236.png){width="5.46875in"
> height="2.636482939632546in"}

3.  Sistem akan menampilkan *form* **Edit Correspondence**

> ![](.//media/image237.png){width="5.46875in"
> height="2.6364818460192474in"}

4.  Lakukan perubahan pada *form*. Klik **Save** untuk menyimpan
    > perubahan pada *form* fax keluar. Surat yang disimpan akan
    > tersimpan di menu "**Draft -- Fax Keluar"**

> ![](.//media/image238.png){width="5.46875in"
> height="2.6364818460192474in"}

5.  Klik **Edit Content** untuk mengubah isi fax keluar

> ![](.//media/image239.png){width="5.46875in"
> height="2.636482939632546in"}

6.  Sistem menampilkan tampilan *preview* fax keluar dalam bentuk Word
    > yang dapat di edit. Untuk melakukan *editing* terhadap isi surat
    > klik **Edit Content** kemudian sistem akan menampilkan *pop up*
    > konfirmasi **Ubah Word Desktop** atau **Ubah *Online***

> ![](.//media/image225.png){width="5.46875in"
> height="2.6364818460192474in"}

##### \[Edit\] Word Desktop

> Langkah -- langkah untuk mengubah isi fax keluar melalui Word Desktop
> adalah sebagai berikut.

1.  Klik **Ubah di Word** untuk mengubah melalui aplikasi Microsoft Word

> ![](.//media/image225.png){width="5.458333333333333in"
> height="2.6314599737532807in"}

2.  Lakukan perubahan pada isi surat. Klik Close pada aplikasi dan isi
    > surat akan otomatis tersimpan

> ![](.//media/image226.png){width="5.46875in"
> height="2.90840769903762in"}

##### \[Edit\] Ubah *Online*

> Langkah -- langkah untuk mengubah isi fax keluar secara *online*
> adalah sebagai berikut.

1.  Ketika *Klik button Edit Content* maka secara otomatis akan membuka
    > dokumen dan bisa mengubah isi surat secara *online*

> ![](.//media/image227.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

2.  Lakukan perubahan pada isi surat.

> ![](.//media/image228.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

3.  Isi surat akan otomatis tersimpan. Jika surat akan disimpan sebagai
    > draft, maka klik **Tutup.**

> ![](.//media/image229.png){width="5.520833333333333in"
> height="2.6615912073490815in"}

4.  Surat yang sudah selesai diubah maka akan tersimpan di menu "**Draft
    > -- Fax keluar"**

##### Kirim Fax Keluar

Langkah -- langkah untuk mengirim fax keluar adalah sebagai berikut.

1.  Pada tampilan *preview* fax keluar, klik **Kirim** untuk mengirim
    > surat ke pejabat tujuan

> ![](.//media/image240.png){width="5.46875in"
> height="2.6364818460192474in"}

2.  Sistem menyimpan perubahan dan fax keluar akan tersimpan di menu
    > "**Outbox - Fax keluar**"

    1.  #### Melihat Informasi Lengkap Fax Keluar

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat melihat informasi lengkap fax keluar termasuk *preview*
> fax keluar, detail fax keluar, *tracking* fax keluar dan *history* fax
> keluar. Langkah-langkah untuk melihat informasi fax keluar adalah
> sebagai berikut.

1.  Klik menu **Inbox/Draft/Outbox** dan pilih tab **Fax Keluar.** Pilih
    > salah satu fax keluar yang akan dilihat informasinya

> ![](.//media/image241.png){width="5.488147419072616in"
> height="2.6458333333333335in"}

##### Preview Fax Keluar

> Pada *button* *Preview* fax keluar, ditampilkan *preview* fax keluar
> yang sudah dibuat. *Preview* fax keluar disesuaikan dengan template
> berdasarkan jenis surat.
>
> ![](.//media/image242.png){width="5.27207895888014in"
> height="2.5416666666666665in"}
>
> ![](.//media/image243.png){width="5.260416666666667in"
> height="2.5360444006999123in"}

##### Detail Fax Keluar

> Pada tab Detail fax keluar, terdapat informasi asal surat, perihal,
> file lampiran, nomor surat, klasifikasi surat, tanggal surat, tujuan
> surat dan *reviewer*
>
> ![](.//media/image244.png){width="5.260416666666667in"
> height="2.5360444006999123in"}

##### Tracking Fax Keluar

> Pada tab *tracking* fax keluar, ditampilkan informasi *tracking* fax
> keluar dalam bentuk *chart*
>
> ![](.//media/image245.png){width="5.270833333333333in"
> height="2.541066272965879in"}

##### History Fax Keluar

> Pada tab *History* fax keluar, ditampilkan riwayat fax keluar yang
> terdapat informasi jabatan, tanggal, tindakan dan komentar
>
> ![](.//media/image246.png){width="5.28125in"
> height="2.5460881452318462in"}

#### Menyetujui Fax Keluar

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

*User* dapat menyetujui fax keluar yang sudah dilakukan review dan fax
keluar akan dikirimkan ke *reviewer* selanjutnya atau *approver*.
Langkah-langkah untuk menyetujui fax keluar adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Fax Keluar**

> ![](.//media/image247.png){width="5.447916666666667in"
> height="2.626438101487314in"}

2.  Pilih fax keluar yang akan ditindak lanjuti kemudian pilih tab
    > **Detail**

> ![](.//media/image248.png){width="5.479166666666667in"
> height="2.641503718285214in"}

3.  Klik tombol **Approve** dan pilih **Send.** Isikan komentar jika
    > diperlukan

> ![](.//media/image249.png){width="5.46875in"
> height="2.638293963254593in"}

4.  Sistem berhasil menyimpan perubahan. Fax keluar yang sudah di kirim
    > akan tersimpan di menu **Outbox- Fax Keluar**

    1.  #### Kembalikan Fax Keluar ke Sebelumnya

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

> *User* dapat mengembalikan fax keluar ke sebelumnya jika hasil review
> belum / tidak sesuai. Surat akan dikembalikan ke satu level *reviewer*
> sebelumnya atau ke konseptor (apabila hanya ada satu *reviewer*).
> Langkah-langkah untuk mengembalikan fax keluar ke sebelumnya adalah
> sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Fax Keluar**

> ![](.//media/image250.png){width="5.4840277777777775in"
> height="2.6456660104986875in"}![](.//media/image251.png){width="5.484377734033246in"
> height="2.6458333333333335in"}

2.  Pilih fax keluar yang akan ditindak lanjuti kemudian pilih tab
    > **Detail**

> ![](.//media/image250.png){width="5.4840277777777775in"
> height="2.6456660104986875in"}

3.  Klik tombol **Return Previus** dan pilih **Send.** Isikan komentar
    > jika diperlukan

> ![](.//media/image252.png){width="6.284722222222222in"
> height="3.0319444444444446in"}

4.  Sistem berhasil menyimpan perubahan. Fax keluar yang sudah di kirim
    > akan tersimpan di menu **Outbox- Fax Keluar** dan penerima
    > pengembalian fax keluar akan menerima fax keluar di menu **Draft -
    > Fax Keluar**

    1.  #### Kembalikan Fax Keluar ke Konseptor

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

> *User* dapat mengembalikan fax keluar ke konseptor jika hasil review
> belum / tidak sesuai. Langkah-langkah untuk mengembalikan fax keluar
> ke konseptor adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Fax Keluar**

> ![](.//media/image251.png){width="5.484377734033246in"
> height="2.6458333333333335in"}

2.  Pilih fax keluar yang akan ditindak lanjuti kemudian pilih tab
    > **Detail**

> ![](.//media/image250.png){width="5.4840277777777775in"
> height="2.6456660104986875in"}

3.  Klik tombol **Return Conceptor** dan pilih **Send.** Isikan komentar
    > jika diperlukan

> ![](.//media/image253.png){width="5.484378827646545in"
> height="2.6458333333333335in"}

4.  Sistem berhasil menyimpan perubahan. Fax keluar yang sudah di kirim
    > akan tersimpan di menu **Outbox- Fax Keluar** dan konseptor akan
    > menerima fax keluar di menu **Draft -- Fax Keluar**

    1.  #### Menolak Fax Keluar

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

> *User* dapat menolak fax keluar yang akan dikemnbalikan ke konseptor
> jika hasil review fax keluar belum / tidak sesuai. Langkah-langkah
> untuk menolak fax keluar adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Fax Keluar**

> ![](.//media/image250.png){width="5.4840277777777775in"
> height="2.6456660104986875in"}

2.  Pilih fax keluar yang akan ditindak lanjuti kemudian pilih tab
    > **Detail**

> ![](.//media/image250.png){width="5.4840277777777775in"
> height="2.6456660104986875in"}

3.  Klik tombol **Reject** dan pilih **Send.** Isikan komentar jika
    > diperlukan

> ![](.//media/image254.png){width="5.46875in"
> height="2.6382950568678916in"}

4.  Sistem berhasil menyimpan perubahan. Fax keluar yang sudah di tolak
    > akan akan akan terhapus dari aplikasi secara *soft delete.*

    1.  #### Menambah Reviewer Baru Fax Keluar

**Role yang sesuai**

-   *Approver (*Pemilik KBO*)*

> *User* dapat menambahkan reviewer kemudian fax keluar akan diteruskan
> ke reviewer baru. Langkah-langkah untuk menambah reviewer fax keluar
> adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Fax Keluar**

> ![](.//media/image250.png){width="5.4840277777777775in"
> height="2.6456660104986875in"}

2.  Pilih fax keluar yang akan ditindak lanjuti kemudian pilih tab
    > **Detail**

> ![](.//media/image250.png){width="5.4840277777777775in"
> height="2.6456660104986875in"}

3.  Klik tombol **Add Reviewer** dan pilih pejabat yang akan melakukan
    > review dengan meng-klik tombol "+" pada field **Add Reviewer**

> ![](.//media/image255.png){width="5.4840277777777775in"
> height="2.6456649168853894in"}

4.  Sistem akan menampilkan pejabat untuk dijadikan reviewer baru

> ![](.//media/image256.png){width="6.284722222222222in"
> height="3.017361111111111in"}

5.  Pilih **Send** untuk mengirimkan kepada pejabat/reviewer yang dituju
    > dan fax keluar akan tersimpan di menu "**Outbox - Fax Keluar**".
    > Untuk pejabat/reviewer baru akan menerima fax keluar di menu
    > "**Inbox -- Fax Keluar**"

> ![](.//media/image257.png){width="5.510416666666667in"
> height="2.6510892388451444in"}

#### Mengesahkan Nomor Fax Keluar

**Role yang sesuai**

-   *Approver (*Pemilik KBO*)*

> *User* dapat mengesahkan fax keluar yang sudah dikirim dan direview
> oleh reviewer. Keluaran untuk tindak lanjut ini adalah untuk
> men-*generate* nomor fax keluar kemudian fax keluar dapat dikirimkan
> ke pejabat tujuan. Langkah-langkah untuk menambah reviewer fax keluar
> adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **Fax Keluar**

> ![](.//media/image250.png){width="5.4840277777777775in"
> height="2.6456660104986875in"}

2.  Pilih fax keluar yang akan ditindak lanjuti kemudian pilih tab
    > **Detail.** Pada tab **Detail** terdapat informasi nomor surat
    > yang masih bersifat sementara. Nomor inilah yang akan
    > ter-*generate* jika *user* menyetujui fax keluar.

> ![](.//media/image258.png){width="5.489583333333333in"
> height="2.648345363079615in"}

3.  Klik **Approve** kemudian pilih **Send**

> ![](.//media/image259.png){width="5.5in"
> height="2.6460772090988627in"}

4.  Sistem menyimpan perubahan dan nomor fax keluar akan ter-*generate*
    > sesuai dengan nomor sementara pada detail. Fax keluar yang sudah
    > diseyujui akan tersimpan di menu "**Outbox - Fax Keluar**"
    > pengirim sedangkan fax keluar akan tersimpan di menu "**Inbox -
    > Fax Keluar**" penerima.

    1.  ### SP3S

> Pada modul ini mendukung proses input Surat Penunjukan Pejabat
> Pengganti Sementara (SP3S) dan akan dikirimkan ke pejabat terkait.
> Pengguna yang dapat melakukan input SP3S adalah sekretaris, pekerja
> yang diperintahkan atau pejabat yang akan meninggalkan tempat (dinas,
> cuti).

#### Melihat Daftar SP3S

**Role yang sesuai**

-   *Approver*

-   *Member User (*Pekerja*)*

> *User* dapat melihat daftar SP3S pada pada menu **Inbox, Draft atau
> Outbox** pada masing-masing akun. Langkah -- langkah untuk melihat
> daftar SP3S adalah sebagai berikut

1.  Klik menu **Inbox / Draft / Outbox** dan pilih tab **SP3S**

> ![](.//media/image260.png){width="5.509757217847769in"
> height="2.65625in"}

#### Menambah Pengajuann SP3S

**Ditujukan kepada**

-   *Approver*

**Role yang sesuai**

-   *Member User (*Pekerja*)*

> Konseptor penambahan SP3S adalah sekretaris atau pekerja lain yang
> diperintahkan untuk membuat SP3S atau pejabat yang akan meninggalkan
> tempat (melimpahkan wewenang/tugas) tersebut. Konseptor mengirimkan
> SP3S kepada approver / atasan pejabat yang akan meninggalkan tempat,
> sehingga draft SP3S akan langsung dikirim kepada atasan pejabat yang
> akan meninggalkan tempat tanpa melalui *reviewer*. Langkah-langkah
> untuk menambah SP3S adalah sebagai berikut.

1.  Klik menu **New Correspondence**

> ![](.//media/image261.png){width="5.479166666666667in"
> height="2.641503718285214in"}

2.  Pilih jenis surat "**SP3S**"

> ![](.//media/image262.png){width="5.46875in"
> height="2.6364818460192474in"}

3.  Isi *form* tambah SP3S. Terdapat beberapa aksi untuk menindaklanjuti
    > SP3S yang sudah diisi *form*nya yaitu **Save SP3S** dan **Send
    > SP3S.**

> ![](.//media/image263.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

##### Simpan SP3S

Langkah -- langkah untuk menyimpan SP3S adalah sebagai berikut.

1.  Isi *form* SP3S kemudian klik **Save**

> ![](.//media/image264.png){width="5.489583333333333in"
> height="2.6465255905511813in"}
>
> ![](.//media/image265.png){width="5.5in" height="2.651547462817148in"}

2.  Sistem akan menampilkan tampilan *preview* SP3S dalam bentuk Word
    > yang dapat di edit. Untuk melakukan *editing* terhadap isi surat
    > klik **Edit Content** kemudian sistem akan menampilkan *pop up*
    > konfirmasi **Ubah Word Desktop** atau **Ubah *Online***

> ![](.//media/image266.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

##### \[Edit\] Word Desktop

> Langkah -- langkah untuk mengubah isi SP3S melalui Word Desktop adalah
> sebagai berikut.

1.  Klik **Ubah di Word** untuk mengubah melalui aplikasi Microsoft Word

> ![](.//media/image267.png){width="5.46875in"
> height="2.6364818460192474in"}

2.  Lakukan perubahan pada isi surat. Klik **Close** pada aplikasi dan
    > isi surat akan otomatis tersimpan

> ![](.//media/image268.png){width="5.5in" height="2.937182852143482in"}

##### \[Edit\] Ubah *Online*

> Langkah -- langkah untuk mengubah isi SP3S secara *online* adalah
> sebagai berikut.

1.  Ketika *Klik button Edit Content* maka secara otomatis akan membuka
    > dokumen dan bisa mengubah isi surat secara *online*

> ![](.//media/image269.png){width="5.489583333333333in"
> height="2.6501640419947505in"}

2.  Lakukan perubahan pada isi surat.

> ![](.//media/image269.png){width="5.489583333333333in"
> height="2.6501640419947505in"}

3.  Isi surat akan otomatis tersimpan. Jika surat akan disimpan sebagai
    > draft, maka klik **Close.**

> ![](.//media/image270.png){width="5.53125in"
> height="2.6702799650043745in"}

4.  Surat yang sudah selesai diubah maka akan tersimpan di menu "**Draft
    > -- SP3S"**

##### Kirim SP3S

> Langkah -- langkah untuk mengirim SP3S adalah sebagai berikut.

1.  Pada tampilan *preview* SP3S, klik **Send** untuk mengirim surat ke
    > pejabat tujuan

> ![](.//media/image271.png){width="5.479166666666667in"
> height="2.645135608048994in"}

2.  Sistem menyimpan perubahan dan SP3S akan tersimpan di menu
    > "**Outbox - SP3S**"

    1.  #### Melakukan Drafting SP3S

**Role yang sesuai**

-   *Member User (*Pekerja*)*

> *User* dapat melakukan *drafting* SP3S pada aplikasi P-Office.
> *Drafting* SP3S dilakukan jika *user* akan meneruskan dan melakukan
> perubahan pada SP3S yang sudah disimpan pada menu **Draft.**

Langkah-langkah untuk melakukan *drafting* SP3S adalah sebagai berikut.

1.  Klik menu **Draft** dan pilih tab **SP3S**

> ![](.//media/image272.png){width="5.479166666666667in"
> height="2.645135608048994in"}

2.  Pilih SP3S yang akan diubah. Pilih tab **Detail** kemudian klik
    > **Edit**

> ![](.//media/image273.png){width="5.461805555555555in"
> height="2.6367541557305336in"}

3.  Sistem akan menampilkan *form* **Edit Correspondence**

> ![](.//media/image274.png){width="5.479166666666667in"
> height="2.645135608048994in"}

4.  Lakukan perubahan pada *form*. Klik **Save** untuk menyimpan
    > perubahan pada *form* SP3S. Surat yang disimpan akan tersimpan di
    > menu "**Draft -- SP3S"**

> ![](.//media/image275.png){width="5.461805555555555in"
> height="2.636755249343832in"}

5.  Klik **Edit Content** untuk mengubah isi SP3S

> ![](.//media/image276.png){width="5.480611329833771in"
> height="2.6458333333333335in"}

6.  Sistem menampilkan tampilan *preview* SP3S dalam bentuk Word yang
    > dapat di edit. Untuk melakukan *editing* terhadap isi surat klik
    > **Edit Content** kemudian sistem akan menampilkan *pop up*
    > konfirmasi **Ubah Word Desktop** atau **Ubah *Online***

> ![](.//media/image266.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

##### \[Edit\] Word Desktop

> Langkah -- langkah untuk mengubah isi SP3S melalui Word Desktop adalah
> sebagai berikut.

1.  Klik **Ubah di Word** untuk mengubah melalui aplikasi Microsoft Word

> ![](.//media/image267.png){width="5.46875in"
> height="2.6364818460192474in"}

2.  Lakukan perubahan pada isi surat. Klik **Close** pada aplikasi dan
    > isi surat akan otomatis tersimpan

> ![](.//media/image268.png){width="5.5in" height="2.937182852143482in"}

##### \[Edit\] Ubah *Online*

> Langkah -- langkah untuk mengubah isi SP3S secara *online* adalah
> sebagai berikut.

1.  Ketika *Klik button Edit Content* maka secara otomatis akan membuka
    > dokumen dan bisa mengubah isi surat secara *online*

> ![](.//media/image269.png){width="5.489583333333333in"
> height="2.6501640419947505in"}

2.  Lakukan perubahan pada isi surat.

> ![](.//media/image269.png){width="5.489583333333333in"
> height="2.6501640419947505in"}

3.  Isi surat akan otomatis tersimpan. Jika surat akan disimpan sebagai
    > draft, maka klik **Close.**

> ![](.//media/image270.png){width="5.46875in"
> height="2.640107174103237in"}

4.  Surat yang sudah selesai diubah maka akan tersimpan di menu "**Draft
    > -- SP3S"**

##### Kirim SP3S

Langkah -- langkah untuk mengirim SP3S adalah sebagai berikut.

1.  Pada tampilan *preview* SP3S, klik **Send** untuk mengirim surat ke
    > pejabat tujuan

> ![](.//media/image277.png){width="5.489583333333333in"
> height="2.650165135608049in"}

2.  Sistem menyimpan perubahan dan SP3S akan tersimpan di menu
    > "**Outbox - SP3S**"

    1.  #### Melihat Informasi Lengkap SP3S

**Role yang sesuai**

-   *Approver*

-   *Member User (*Pekerja*)*

> *User* dapat melihat informasi lengkap SP3S termasuk *preview* SP3S,
> detail SP3S dan *history* SP3S. Langkah-langkah untuk melihat
> informasi SP3S adalah sebagai berikut.

1.  Klik menu **Inbox/Draft/Outbox** dan pilih tab **SP3S.** Pilih salah
    > satu SP3S yang akan dilihat informasinya

> ![](.//media/image278.png){width="5.48125in"
> height="2.6461417322834646in"}

##### Preview SP3S

> Pada *button* *Preview* SP3S, ditampilkan *preview* SP3S yang sudah
> dibuat. *Preview* SP3S disesuaikan dengan template berdasarkan jenis
> surat.
>
> ![](.//media/image279.png){width="5.302083333333333in"
> height="2.559646762904637in"}
>
> ![](.//media/image280.png){width="5.302083333333333in"
> height="2.559646762904637in"}

##### Detail SP3S

> Pada tab Detail SP3S, terdapat informasi nomor SP3S, jabatan PJS,
> Pejabat pengganti pertama, jangka waktu, pejabat pengganti kedua (jika
> ada), jangka waktu pejabat pengganti kedua (jika ada), task yang
> diizinkan dan task pengecualian.
>
> ![](.//media/image281.png){width="5.28125in"
> height="2.549588801399825in"}

##### History SP3S

> Pada tab *History* SP3S, ditampilkan riwayat SP3S yang terdapat
> informasi jabatan, tanggal, tindakan dan komentar
>
> ![](.//media/image282.png){width="5.270833333333333in"
> height="2.54455927384077in"}

#### Menyetujui SP3S

**Role yang sesuai**

-   *Approver*

> *User* dapat menyetujui SP3S yang sudah dikirimkan oleh konseptor
> sehingga nomor SP3S akan ter-*generate* secara otomatis*.*
> Langkah-langkah untuk menyetujui SP3S adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **SP3S**

> ![](.//media/image283.png){width="5.479166666666667in"
> height="2.645135608048994in"}

2.  Pilih SP3S yang akan disetujui kemudian pilih tab **Detail**

> ![](.//media/image284.png){width="5.46875in"
> height="2.640107174103237in"}

3.  Klik tombol **Appove** dan pilih **Send.** Isikan komentar jika
    > diperlukan

> ![](.//media/image285.png){width="5.489583333333333in"
> height="2.650165135608049in"}

4.  Sistem berhasil menyimpan perubahan. SP3S yang sudah di kirim akan
    > tersimpan di menu **Outbox -- SP3S**

    1.  #### Menolak SP3S

**Role yang sesuai**

-   *Approver*

> *User* dapat menolak SP3S yang sudah dikirimkan oleh konseptor.
> Langkah-langkah untuk menolak SP3S adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **SP3S**

> ![](.//media/image283.png){width="5.479166666666667in"
> height="2.645135608048994in"}

2.  Pilih SP3S yang akan disetujui kemudian pilih tab **Detail**

> ![](.//media/image284.png){width="5.46875in"
> height="2.640107174103237in"}

3.  Klik tombol **Reject** dan pilih **Send.** Isikan komentar jika
    > diperlukan

> ![](.//media/image286.png){width="5.479166666666667in"
> height="2.645135608048994in"}

4.  Sistem berhasil menyimpan perubahan. SP3S yang sudah di kirim akan
    > akan akan terhapus dari aplikasi secara *soft delete.*

    1.  #### Merevisi SP3S

**Role yang sesuai**

-   *Approver*

> *User* dapat merevisi SP3S yang sudah dikirimkan oleh konseptor.
> Langkah-langkah untuk melakukan revisi SP3S adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **SP3S**

> ![](.//media/image283.png){width="5.479166666666667in"
> height="2.645135608048994in"}

2.  Pilih SP3S yang akan disetujui kemudian pilih tab **Detail**

> ![](.//media/image284.png){width="5.46875in"
> height="2.640107174103237in"}

3.  Klik tombol **Revise** dan pilih **Send.** Isikan komentar jika
    > diperlukan

> ![](.//media/image287.png){width="5.479166666666667in"
> height="2.645135608048994in"}

4.  Sistem menampilkan *form* **Edit Correspondence**

> ![](.//media/image288.png){width="5.490566491688539in"
> height="2.6506397637795276in"}

5.  Lakukan perubahan pada *form*. Klik **Simpan** untuk menyimpan
    > perubahan pada *form* SP3S. Surat yang disimpan akan tersimpan di
    > menu "**Inbox -- SP3S"**

> ![](.//media/image289.png){width="5.5in"
> height="2.6551924759405074in"}

6.  Klik **Edit Content** untuk mengubah isi SP3S

> ![](.//media/image290.png){width="5.462264873140858in"
> height="2.6369761592300964in"}

7.  Sistem menampilkan tampilan *preview* SP3S dalam bentuk Word yang
    > dapat di edit. Untuk melakukan *editing* terhadap isi surat klik
    > **Edit Content** kemudian sistem akan menampilkan *pop up*
    > konfirmasi **Ubah Word Desktop** atau **Ubah *Online***

> ![](.//media/image266.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

##### \[Edit\] Word Desktop

> Langkah -- langkah untuk mengubah isi SP3S melalui Word Desktop adalah
> sebagai berikut.

1.  Klik **Ubah di Word** untuk mengubah melalui aplikasi Microsoft Word

> ![](.//media/image267.png){width="5.46875in"
> height="2.6364818460192474in"}

2.  Lakukan perubahan pada isi surat. Klik **Close** pada aplikasi dan
    > isi surat akan otomatis tersimpan

> ![](.//media/image268.png){width="5.5in" height="2.937182852143482in"}

##### \[Edit\] Ubah *Online*

> Langkah -- langkah untuk mengubah isi SP3S secara *online* adalah
> sebagai berikut.

1.  Ketika *Klik button Edit Content* maka secara otomatis akan membuka
    > dokumen dan bisa mengubah isi surat secara *online*
    > ![](.//media/image269.png){width="5.489583333333333in"
    > height="2.6501640419947505in"}

2.  Lakukan perubahan pada isi surat.

> ![](.//media/image270.png){width="5.46875in"
> height="2.640107174103237in"}

3.  Isi surat akan otomatis tersimpan. Jika surat akan disimpan sebagai
    draft, maka klik **Close.**

> ![](.//media/image270.png){width="5.46875in"
> height="2.640107174103237in"}

4.  Surat yang sudah selesai diubah maka akan tersimpan di menu "**Inbox
    -- SP3S"**

    1.  #### Menonaktifkan SP3S

**Role yang sesuai**

-   *Reviewer (*Pejabat Pjs*)*

> SP3S yang masih berlaku akan non-aktif secara otomatis apabila sudah
> habis masa jabatan pejabat yang sedang di PJS-kan. Namun, apabila
> pejabat definitif kembali bekerja sebelum masa PJS nya habis, maka
> pejabat tersebut harus menon-aktifkan SP3S yang berlaku dengan cara
> sebagai berikut:

1.  Klik menu **Inbox** dan pilih tab **SP3S**

> ![](.//media/image283.png){width="5.479166666666667in"
> height="2.645135608048994in"}

2.  Pilih SP3S yang akan dinon-aktifkan kemudian pilih icon **Disable.**

> ![](.//media/image291.png){width="5.5188681102362205in"
> height="2.664301181102362in"}

3.  SP3S yang sudah tidak aktif akan tersimpan di menu "**Outbox --
    > SP3S**" approver. Untuk pejabat PJS dan pejabat yang meninggalkan
    > tempat, surat akan tersimpan di menu "**Inbox -- SP3S**"

    1.  #### Melihat Riwayat SP3S

**Role yang sesuai**

-   *Approver*

-   *Member User (*Pekerja*)*

> *User* dapat melihat informasi pejabat yang sedang menjabat sebagai
> Pjs baik dalam status aktif maupun non-aktif. Informasi yang
> ditampilkan meliputi nomor SP3S, Nama pejabat, jabatan dan status.
> Langkah-langkah untuk melihat informasi Riwayat SP3S adalah sebagai
> berikut:

1.  Klik menu **History** dan pilih tab **SP3S**

> ![](.//media/image292.png){width="5.5in"
> height="2.6551924759405074in"}

2.  Sistem menampilkan riwayat SP3S

    1.  ### SPPTH

> Pada modul ini mendukung proses input Surat Penunjukan Pelaksana Tugas
> Harian (SPPTH) dan akan dikirimkan ke pejabat terkait. Pengguna yang
> dapat melakukan input SPPTH adalah sekretaris, pekerja yang
> diperintahkan atau pejabat yang akan meninggalkan tempat (dinas,
> cuti). Pejabat yang dapat mengajukan SPPTH hanya berlaku untuk
> direksi. Pengajuann SPPTH akan disetujui oleh direktur utama atau
> Pejabat Sementara (Pjs) direktur utama.

#### Melihat Daftar SPPTH

**Role yang sesuai**

-   *Approver*

-   *Member User (*Pekerja*)*

> *User* dapat melihat daftar SPPTH pada pada menu **Inbox, Draft atau
> Outbox** pada masing-masing akun. Langkah -- langkah untuk melihat
> daftar SPPTH adalah sebagai berikut

1.  Klik menu **Inbox / Draft / Outbox** dan pilih tab **SPPTH**

> ![](.//media/image293.png){width="5.490566491688539in"
> height="2.650638670166229in"}

#### Menambah Pengajuann SPPTH

**Ditujukan kepada**

-   *Approver*

**Role yang sesuai**

-   *Member User (*Pekerja*)*

> SPPTH dibuat oleh konseptor/sekretaris Direksi yang akan meninggalkan
> tempat, sedangkan *approver* adalah Direktur Utama atau Pjs. Direktur
> Utama. Langkah-langkah untuk menambah SPPTH adalah sebagai berikut

1.  Klik menu **New Correspondence**

> ![](.//media/image294.png){width="5.792451881014873in"
> height="2.7963779527559054in"}

2.  Pilih jenis surat "**SPPTH**"

![](.//media/image295.png){width="5.783018372703412in"
height="2.7918241469816274in"}

3.  Isi *form* tambah SPPTH. Terdapat beberapa aksi untuk
    menindaklanjuti SPPTH yang sudah diisi *form*nya yaitu **Save
    SPPTH** dan **Cancel SPPTH.**

> ![](.//media/image296.png){width="5.754716754155731in"
> height="2.7781616360454944in"}

##### Simpan SPPTH

Langkah -- langkah untuk menyimpan SPPTH adalah sebagai berikut.

1.  Isi *form* SPPTH kemudian klik **Save**

> ![](.//media/image297.png){width="5.396225940507437in"
> height="2.605095144356955in"}

2.  Sistem akan menampilkan tampilan *preview* SPPTH dalam bentuk Word
    > yang dapat di edit. Untuk melakukan *editing* terhadap isi surat
    > klik **Edit Content** kemudian sistem akan menampilkan *pop up*
    > konfirmasi **Ubah Word Desktop** atau **Ubah *Online***

> ![](.//media/image298.png){width="5.405660542432196in"
> height="2.609650043744532in"}

##### \[Edit\] Word Desktop

> Langkah -- langkah untuk mengubah isi SPPTH melalui Word Desktop
> adalah sebagai berikut.

1.  Klik **Ubah di Word** untuk mengubah melalui aplikasi Microsoft Word

> ![](.//media/image299.png){width="5.5188681102362205in"
> height="2.6643022747156606in"}

2.  Lakukan perubahan pada isi surat. Klik **Close** pada aplikasi dan
    > isi surat akan otomatis tersimpan

> ![](.//media/image300.png){width="5.5in" height="2.937182852143482in"}

##### \[Edit\] Ubah *Online*

> Langkah -- langkah untuk mengubah isi SPPTH secara *online* adalah
> sebagai berikut.

1.  Ketika *Klik button Edit Content* maka secara otomatis akan membuka
    > dokumen dan bisa mengubah isi surat secara *online*

> ![](.//media/image301.png){width="5.490566491688539in"
> height="2.646999125109361in"}

2.  Lakukan perubahan pada isi surat.

> ![](.//media/image301.png){width="5.490566491688539in"
> height="2.646999125109361in"}

3.  Isi surat akan otomatis tersimpan. Jika surat akan disimpan sebagai
    > draft, maka klik **Close.**

> ![](.//media/image302.png){width="5.5094346019247595in"
> height="2.6560958005249344in"}

4.  Surat yang sudah selesai diubah maka akan tersimpan di menu "**Draft
    > -- SPPTH"**

##### Kirim SPPTH

> Langkah -- langkah untuk mengirim SPPTH adalah sebagai berikut.

1.  Pada tampilan *preview* SPPTH, klik **Kirim** untuk mengirim SPPTH
    > ke *approver*

> ![](.//media/image303.png){width="5.5in" height="2.651547462817148in"}

2.  Sistem menyimpan perubahan dan SPPTH akan tersimpan di menu
    > "**Outbox - SPPTH**"

    1.  #### Melakukan Drafting SPPTH

**Role yang sesuai**

-   *Member User (*Pekerja*)*

> *User* dapat melakukan *drafting* SPPTH pada aplikasi P-Office.
> *Drafting* SPPTH dilakukan jika *user* akan meneruskan dan melakukan
> perubahan pada SPPTH yang sudah disimpan pada menu **Draft.**
> Langkah-langkah untuk melakukan *drafting* SPPTH adalah sebagai
> berikut.

1.  Klik menu **Draft** dan pilih tab **SPPTH**

> ![](.//media/image304.png){width="5.481132983377078in"
> height="2.642451881014873in"}

2.  Pilih SPPTH yang akan diubah. Pilih tab **Detail** kemudian klik
    > **Edit**

> ![](.//media/image305.png){width="5.5in" height="2.651547462817148in"}

3.  Sistem akan menampilkan *form* **Edit Correspondence**

> ![](.//media/image306.png){width="5.480555555555555in"
> height="2.642173009623797in"}

4.  Lakukan perubahan pada *form*. Klik **Save** untuk menyimpan
    > perubahan pada *form* SPPTH. Surat yang disimpan akan tersimpan di
    > menu "**Draft -- SPPTH"**

> ![](.//media/image307.png){width="5.509722222222222in"
> height="2.6562335958005248in"}

5.  Klik **Edit Content** untuk mengubah isi SPPTH

> ![](.//media/image308.png){width="5.509722222222222in"
> height="2.6562335958005248in"}

6.  Sistem menampilkan tampilan *preview* SPPTH dalam bentuk Word yang
    > dapat di edit. Untuk melakukan *editing* terhadap isi surat klik
    > **Edit Content** kemudian sistem akan menampilkan *pop up*
    > konfirmasi **Ubah Word Desktop** atau **Ubah *Online***

> ![](.//media/image298.png){width="5.405660542432196in"
> height="2.609650043744532in"}

##### \[Edit\] Word Desktop

> Langkah -- langkah untuk mengubah isi SPPTH melalui Word Desktop
> adalah sebagai berikut.

1.  Klik **Ubah di Word** untuk mengubah melalui aplikasi Microsoft Word

> ![](.//media/image299.png){width="5.5188681102362205in"
> height="2.6643022747156606in"}

2.  Lakukan perubahan pada isi surat. Klik **Close** pada aplikasi dan
    > isi surat akan otomatis tersimpan

> ![](.//media/image300.png){width="5.5in" height="2.937182852143482in"}

##### \[Edit\] Ubah *Online*

> Langkah -- langkah untuk mengubah isi SPPTH secara *online* adalah
> sebagai berikut.

1.  Ketika *Klik button Edit Content* maka secara otomatis akan membuka
    > dokumen dan bisa mengubah isi surat secara *online*

> ![](.//media/image301.png){width="5.490566491688539in"
> height="2.646999125109361in"}

2.  Lakukan perubahan pada isi surat.

> ![](.//media/image301.png){width="5.490566491688539in"
> height="2.646999125109361in"}

3.  Isi surat akan otomatis tersimpan. Jika surat akan disimpan sebagai
    > draft, maka klik **Close.**

> ![](.//media/image302.png){width="5.5094346019247595in"
> height="2.6560958005249344in"}

4.  Surat yang sudah selesai diubah maka akan tersimpan di menu "**Draft
    -- SPPTH"**

##### Kirim / Setujui SPPTH

Langkah -- langkah untuk mengirim SPPTH adalah sebagai berikut.

1.  Pada tampilan *preview* SPPTH, klik **Kirim** untuk mengirim SPPTH
    > ke atasan pejabat

> ![](.//media/image303.png){width="5.5in" height="2.651547462817148in"}

2.  Sistem menyimpan perubahan dan SPPTH akan tersimpan di menu
    > "**Outbox - SPPTH**"

    1.  #### Melihat Informasi Lengkap SPPTH

**Role yang sesuai**

-   *Approver*

-   *Member User (*Pekerja*)*

> *User* dapat melihat informasi lengkap SPPTH termasuk *preview* SPPTH,
> detail SPPTH dan *history* SPPTH. Langkah-langkah untuk melihat
> informasi SPPTH adalah sebagai berikut

1.  Klik menu **Inbox/Draft/Outbox** dan pilih tab **SPPTH.** Pilih
    > salah satu SPPTH yang akan dilihat informasinya

> ![](.//media/image309.png){width="5.471698381452319in"
> height="2.6379024496937884in"}

##### Preview SPPTH

> Pada *button* *Preview* SPPTH, ditampilkan *preview* SPPTH yang sudah
> dibuat. *Preview* SPPTH disesuaikan dengan template berdasarkan jenis
> surat.
>
> ![](.//media/image310.png){width="5.273584864391951in"
> height="2.5423906386701662in"}
>
> ![](.//media/image311.png){width="5.254716754155731in"
> height="2.5332961504811897in"}

##### Detail SPPTH

> Pada tab Detail SPPTH, terdapat informasi nomor SPPTH, jabatan PTH,
> Pejabat pengganti pertama, jangka waktu serta pejabat pengganti kedua
> (jika ada), jangka waktu pejabat pengganti kedua (jika ada)
>
> ![](.//media/image312.png){width="5.301388888888889in"
> height="2.5557961504811897in"}

##### History SPPTH

> Pada tab *History* SPPTH, ditampilkan riwayat SPPTH yang terdapat
> informasi jabatan, tanggal, tindakan dan komentar
>
> ![](.//media/image313.png){width="5.254716754155731in"
> height="2.5332961504811897in"}

#### Menyetujui SPPTH

**Role yang sesuai**

-   *Approver*

> *User* dapat menyetujui SPPTH yang sudah dikirimkan oleh konseptor
> sehingga nomor SPPTH akan ter-*generate* secara otomatis*.*
> Langkah-langkah untuk menyetujui SPPTH adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **SPPTH**

> ![](.//media/image293.png){width="5.490566491688539in"
> height="2.650638670166229in"}

2.  Pilih SPPTH yang akan disetujui kemudian pilih tab **Detail**

> ![](.//media/image314.png){width="5.490277777777778in"
> height="2.6468602362204723in"}

3.  Klik tombol **Approve** dan pilih **Send.** Isikan komentar jika
    > diperlukan

> ![](.//media/image315.png){width="5.490277777777778in"
> height="2.646859142607174in"}

4.  Sistem berhasil menyimpan perubahan. SPPTH yang sudah di kirim akan
    > tersimpan di menu **Outbox -- SPPTH**

    1.  #### Menolak SPPTH

**Role yang sesuai**

-   *Approver*

> *User* dapat menolak SPPTH yang sudah dikirimkan oleh konseptor.
> Langkah-langkah untuk menolak SPPTH adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **SPPTH**

> ![](.//media/image293.png){width="5.490566491688539in"
> height="2.650638670166229in"}

2.  Pilih SPPTH yang akan disetujui kemudian pilih tab **Detail**

> ![](.//media/image314.png){width="5.490277777777778in"
> height="2.6468602362204723in"}

3.  Klik tombol **Reject** dan pilih **Send.** Isikan komentar jika
    > diperlukan

> ![](.//media/image316.png){width="5.481132983377078in"
> height="2.642450787401575in"}

4.  Sistem berhasil menyimpan perubahan. SPPTH yang sudah di kirim akan
    > akan akan terhapus dari aplikasi secara *soft delete.*

    1.  #### Merevisi SPPTH

**Role yang sesuai**

-   *Approver*

> *User* dapat merevisi SPPTH yang sudah dikirimkan oleh konseptor.
> Langkah-langkah untuk melakukan revisi SPPTH adalah sebagai berikut

1.  Klik menu **Inbox** dan pilih tab **SPPTH**

> ![](.//media/image293.png){width="5.490566491688539in"
> height="2.650638670166229in"}

2.  Pilih SPPTH yang akan disetujui kemudian pilih tab **Detail**

> ![](.//media/image314.png){width="5.490277777777778in"
> height="2.6468602362204723in"}

3.  Klik tombol **Revise** dan pilih **Send.** Isikan komentar jika
    > diperlukan

> ![](.//media/image317.png){width="5.46875in"
> height="2.616227034120735in"}

4.  Sistem menampilkan *form* **Edit Correspondence**

> ![](.//media/image318.png){width="5.5in" height="2.651547462817148in"}

5.  Lakukan perubahan pada *form*. Klik **Save** untuk menyimpan
    > perubahan pada *form* SPPTH. Surat yang disimpan akan tersimpan di
    > menu "**Inbox -- SPPTH"**

> ![](.//media/image319.png){width="5.478472222222222in"
> height="2.641169072615923in"}

6.  Klik **Edit Content** untuk mengubah isi SPPTH

> ![](.//media/image320.png){width="5.5in" height="2.651547462817148in"}

7.  Sistem menampilkan tampilan *preview* SPPTH dalam bentuk Word yang
    > dapat di edit. Untuk melakukan *editing* terhadap isi surat klik
    > **Edit Content** kemudian sistem akan menampilkan *pop up*
    > konfirmasi **Ubah Word Desktop** atau **Ubah *Online***

> ![](.//media/image298.png){width="5.405660542432196in"
> height="2.609650043744532in"}

##### \[Edit\] Word Desktop

> Langkah -- langkah untuk mengubah isi SPPTH melalui Word Desktop
> adalah sebagai berikut.

1.  Klik **Ubah di Word** untuk mengubah melalui aplikasi Microsoft Word

> ![](.//media/image299.png){width="5.5188681102362205in"
> height="2.6643022747156606in"}

2.  Lakukan perubahan pada isi surat. Klik **Close** pada aplikasi dan
    > isi surat akan otomatis tersimpan

> ![](.//media/image300.png){width="5.5in" height="2.937182852143482in"}

##### \[Edit\] Ubah *Online*

> Langkah -- langkah untuk mengubah isi SPPTH secara *online* adalah
> sebagai berikut.

1.  Ketika *Klik button Edit Content* maka secara otomatis akan membuka
    dokumen dan bisa mengubah isi surat secara *online*

> ![](.//media/image301.png){width="5.490566491688539in"
> height="2.646999125109361in"}

2.  Lakukan perubahan pada isi surat.

> ![](.//media/image301.png){width="5.490566491688539in"
> height="2.646999125109361in"}

3.  Isi surat akan otomatis tersimpan. Jika surat akan disimpan sebagai
    draft, maka klik **Close.**

> ![](.//media/image302.png){width="5.5094346019247595in"
> height="2.6560958005249344in"}

4.  Surat yang sudah selesai diubah maka akan tersimpan di menu "**Inbox
    -- SPPTH"**

    1.  #### Menonaktifkan SPPTH

**Role yang sesuai**

-   *Reviewer (*Pejabat Pth)

> SPPTH yang masih berlaku akan non-aktif secara otomatis apabila sudah
> habis masa jabatan pejabat yang sedang di PTH-kan. Namun, apabila
> pejabat definitif kembali bekerja sebelum masa PTH nya habis, maka
> pejabat tersebut harus menon-aktifkan SPPTH yang berlaku dengan cara
> sebagai berikut:

1.  Klik menu **Inbox** dan pilih tab **SPPTH**

> ![](.//media/image321.png){width="5.471698381452319in"
> height="2.6379024496937884in"}

2.  Pilih SPPTH yang akan dinon-aktifkan kemudian pilih icon
    > **Disable.**

> ![](.//media/image322.png){width="5.5in" height="2.651547462817148in"}

3.  SPPTH yang sudah tidak aktif akan tersimpan di menu "**Outbox --
    > SPPTH**" *approver*. Untuk pejabat PTH dan pejabat yang
    > meninggalkan tempat, surat akan tersimpan di menu "**Inbox --
    > SPPTH**"

    1.  #### Melihat Riwayat SPPTH

**Role yang sesuai**

-   *Approver*

-   *Member User (*Pekerja*)*

> *User* dapat melihat informasi pejabat yang sedang menjabat sebagai
> Pth baik dalam status aktif maupun non-aktif. Informasi yang
> ditampilkan meliputi nomor SPPTH, Nama pejabat, jabatan dan status.
> Langkah-langkah untuk melihat informasi Riwayat SPPTH adalah sebagai
> berikut:

1.  Klik menu **History** dan pilih tab **SPPTH**

> ![](.//media/image323.png){width="5.5in" height="2.651547462817148in"}

2.  Sistem menampilkan riwayat SP3S

    1.  ### Archive

> Pada modul ini mendukung tempat penyimpanan dokumen yang melebihi masa
> retensi. Dokumen yang disimpan pada menu Archive meliputi dokumen
> surat masuk, memorandum, surat keluar, fax masuk dan fax keluar.

#### Melihat Dokumen Surat Masuk

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat melihat dokumen surat masuk pada menu Archive. Langkah --
> langkah untuk melihat dokumen surat masuk adalah sebagai berikut

1.  Klik menu **Archive** dan pilih submenu **Surat Masuk**

> ![](.//media/image324.png){width="5.509722222222222in"
> height="2.6562346894138233in"}

2.  Sistem menampilkan dokumen surat masuk yang tersimpan di menu
    > Archive

    1.  #### Melihat Dokumen Memorandum

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat melihat dokumen memorandum pada menu Archive. Langkah --
> langkah untuk melihat dokumen memorandum adalah sebagai berikut

1.  Klik menu **Archive** dan pilih submenu **Memorandum**

> ![](.//media/image325.png){width="5.509722222222222in"
> height="2.6562335958005248in"}

2.  Sistem menampilkan dokumen memorandum yang tersimpan di menu Archive

    1.  #### Melihat Dokumen Surat Keluar

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat melihat dokumen surat keluar pada menu Archive. Langkah
> -- langkah untuk melihat dokumen memorandum adalah sebagai berikut:

1.  Klik menu **Archive** dan pilih submenu **Surat Keluar**

> ![](.//media/image326.png){width="5.5in" height="2.651547462817148in"}

2.  Sistem menampilkan dokumen surat keluar yang tersimpan di menu
    > Archive

    1.  #### Melihat Dokumen Fax Masuk

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat melihat dokumen fax masuk pada menu Archive. Langkah --
> langkah untuk melihat dokumen fax masuk adalah sebagai berikut:

1.  Klik menu **Archive** dan pilih submenu **Fax Masuk**

> ![](.//media/image327.png){width="5.489583333333333in"
> height="2.6465255905511813in"}

2.  Sistem menampilkan dokumen fax masuk yang tersimpan di menu Archive

    1.  #### Melihat Dokumen Fax Keluar

**Role yang sesuai**

-   *Approver*

-   *Reviewer*

-   *Member User (*Pekerja*)*

> *User* dapat melihat dokumen fax keluar pada menu Archive. Langkah --
> langkah untuk melihat dokumen fax keluar adalah sebagai berikut:

1.  Klik menu **Archive** dan pilih submenu **Fax Keluar**

> ![](.//media/image328.png){width="5.5094346019247595in"
> height="2.6560958005249344in"}

2.  Sistem menampilkan dokumen fax keluar yang tersimpan di menu Archive

    1.  ### Document Control

> Pada modul ini mendukung pengelolaan dokumen masuk (Inbox), dokumen
> draft, dokumen keluar (Outbox), dokumen disposisi, rejected dan
> archive oleh sekretaris sesuai dengan pejabat pemilik KBOnya. Pada
> modul *document control* juga terdapat fitur untuk mengajukan nomor
> offline (request offline number) oleh sekretaris dan akan
> ditindaklanjuti oleh admin approver offline number

#### Melihat Daftar Dokumen Masuk (Inbox)

**Role yang sesuai**

-   Sekretaris

> Sekretaris dapat melihat daftar dokumen masuk (Inbox) yang mencatatkan
> seluruh dokumen yang masuk kepada jabatan atasan sekretaris. Langkah
> -- langkah untuk melihat daftar dokumen masuk (Inbox) adalah sebagai
> berikut

1.  Klik menu **Document Control** dan pilih submenu **Dokumen View -
    > Inbox**

> ![](.//media/image329.png){width="5.5188681102362205in"
> height="2.6606430446194227in"}

2.  Sistem menampilkan dokumen masuk (Inbox) yang informasinya meliputi
    > no agenda, tanggal, nomor surat, perihal, dari/asal, status dan
    > *secretary notes.*

    1.  #### Melihat Daftar Dokumen Draft

**Role yang sesuai**

-   Sekretaris

> Sekretaris dapat melihat daftar dokumen draft yang mencatatkan seluruh
> dokumen yang baru disimpan atau dilakukan *drafting* milik atasan
> pejabat sekretaris. Langkah -- langkah untuk melihat daftar dokumen
> draft adalah sebagai berikut

1.  Klik menu **Document Control** dan pilih submenu **Dokumen View -
    > Draft**

> ![](.//media/image330.png){width="5.5in" height="2.651547462817148in"}

2.  Sistem menampilkan dokumen draft yang informasinya meliputi no
    > agenda, tanggal, nomor surat, perihal, dari/asal, status dan
    > *secretary notes.*

    1.  #### Melihat Daftar Dokumen Keluar (Outbox)

**Role yang sesuai**

-   Sekretaris

> Sekretaris dapat melihat daftar dokumen keluar (Outbox) yang
> mencatatkan seluruh dokumen yang keluar kepada jabatan atasan
> sekretaris. Langkah -- langkah untuk melihat daftar dokumen keluar
> (Outbox) adalah sebagai berikut

1.  Klik menu **Document Control** dan pilih submenu **Document View -
    > Outbox**

> ![](.//media/image331.png){width="5.46875in"
> height="2.6364818460192474in"}

2.  Sistem menampilkan dokumen keluar (Outbox) yang informasinya
    > meliputi no agenda, tanggal, nomor surat, perihal, dari/asal,
    > status dan *secretary notes.*

    1.  #### Melihat Daftar Dokumen Disposisi

**Role yang sesuai**

-   Sekretaris

> Sekretaris dapat melihat daftar dokumen disposisi yang mencatatkan
> seluruh dokumen yang didisposisikan kepada jabatan atasan sekretaris.
> Langkah -- langkah untuk melihat daftar dokumen disposisi adalah
> sebagai berikut

1.  Klik menu **Document Control** dan pilih submenu **Document View -
    > Disposisi**

> ![](.//media/image332.png){width="5.481132983377078in"
> height="2.642450787401575in"}

2.  Sistem menampilkan dokumen disposisi yang informasinya meliputi no
    > agenda, tanggal, nomor surat, perihal, dari/asal, status dan
    > *secretary notes.*

    1.  #### Melihat Daftar Dokumen Ditolak (Rejected)

**Role yang sesuai**

-   Sekretaris

> Sekretaris dapat melihat daftar dokumen yang ditolak milik atasan
> pejabat sekretaris. Langkah -- langkah untuk melihat daftar dokumen
> yang ditolak (Rejected) adalah sebagai berikut

1.  Klik menu **Document Control** dan pilih submenu **Document View -
    > Rejected**

> ![](.//media/image333.png){width="5.5in" height="2.651547462817148in"}

2.  Sistem menampilkan dokumen rejected yang informasinya meliputi no
    > agenda, tanggal, nomor surat, perihal, dari/asal, status dan
    > *secretary notes.*

    1.  #### Melihat Daftar Dokumen Archive

**Role yang sesuai**

-   Sekretaris

> Sekretaris dapat melihat daftar dokumen yang diarsipkan milik atasan
> pejabat sekretaris. Langkah -- langkah untuk melihat daftar dokumen
> yang sudah melebihi masa retensi adalah sebagai berikut

1.  Klik menu **Document Control** dan pilih submenu **Document View -
    > Archive**

> ![](.//media/image334.png){width="5.471698381452319in"
> height="2.6379024496937884in"}

2.  Sistem menampilkan dokumen archive yang informasinya meliputi no
    > agenda, tanggal, nomor surat, perihal, dari/asal, status dan
    > *secretary notes.*

    1.  #### Melihat Detail Surat

**Role yang sesuai**

-   Sekretaris

> Pemilik KBO dapat melihat detail surat baik surat yang berklasifikasi
> "Biasa", "Terbatas", "Rahasia" dan "Sangat Rahasia". Sedangkan sebagai
> *role* sekretaris hanya dapat melihat detail surat yang berklasifikasi
> "Biasa" dan "Terbatas". Informasi yang ditampikan detail surat antara
> lain yaitu

-   *Preview* surat

-   Detail surat

-   *Tracking* surat

-   Riwayat / *history surat*

> Langkah-langkah untuk melakukan melihat detail dokumen masuk, dokumen
> keluar dan dokumen disposisi adalah sebagai berikut.

1.  Klik menu **Document Control** dan pilih tab **Document View --
    > Inbox/ Draft / Outbox / Disposisi / Rejected / Archive**

> ![](.//media/image335.png){width="5.5094346019247595in"
> height="2.6560958005249344in"}

2.  Klik salah satu surat yang akan dilihat detailnya

> ![](.//media/image336.png){width="5.481132983377078in"
> height="2.642450787401575in"}

3.  Sistem akan menampilkan detail surat yang dipilih

##### Preview Surat

> Pada tab **Preview Surat**, ditampilkan *preview* surat yang sudah
> dibuat. *Preview* surat disesuaikan dengan template berdasarkan jenis
> surat
>
> ![](.//media/image337.png){width="5.26415135608049in"
> height="2.5378444881889766in"}
>
> ![](.//media/image338.png){width="5.263888888888889in"
> height="2.537717629046369in"}

##### Detail Surat

> Pada tab **Detail Surat**, terdapat informasi asal surat, perihal,
> file lampiran, nomor surat, klasifikasi surat, tanggal surat, tujuan
> surat
>
> ![](.//media/image339.png){width="5.273584864391951in"
> height="2.5423917322834644in"}

##### Tracking Surat

> Pada tab **Tracking Surat**, ditampilkan informasi *tracking*
> memorandum dalam bentuk *chart*
>
> ![](.//media/image340.png){width="5.254716754155731in"
> height="2.5332950568678916in"}

##### History Surat

> Pada tab **History Surat**, ditampilkan riwayat memorandum yang
> terdapat informasi jabatan, tanggal, tindakan dan komentar
>
> ![](.//media/image341.png){width="5.254166666666666in"
> height="2.5330304024496937in"}

#### Menambah Catatan Dokumen

**Role yang sesuai**

-   Sekretaris

Sekretaris dapat menambahkan *notes/*catatan terkait dokumen yang
di-*review*. Langkah-langkah untuk menambah catatan dokumen adalah
sebagai berikut

1.  Klik menu **Document Control** dan pilih tab **Document View --
    > Inbox / Draft / Outbox / Disposisi / Rejected / Archive**

> ![](.//media/image342.png){width="5.490566491688539in"
> height="2.646999125109361in"}

2.  Pilih dokumen/surat yang akan ditambahkan catatan dengan klik button
    > **Note.**

> ![](.//media/image343.png){width="5.5in" height="2.651547462817148in"}

3.  Sistem akan menapilkan pop up **Tambah Catatan.** Isikan catatan dan
    > klik tombol **Save**

> ![](.//media/image344.png){width="5.471698381452319in"
> height="2.6379024496937884in"}

4.  Sistem berhasil menyimpan perubahan catatan dokumen

    1.  #### Mencetak Dokumen Control

**Role yang sesuai**

-   Sekretaris

> Sekretaris dapat mencetak dokumen agenda kendali berdasarkan filter
> yang dipilih dalam format Excel. Langkah-langkah untuk mencetak
> dokumen control adalah sebagai berikut

1.  Klik menu **Document Control** dan pilih tab **Document View --
    > Inbox/ Draft / Outbox / Disposisi / Rejected / Archive**

> ![](.//media/image342.png){width="5.490566491688539in"
> height="2.646999125109361in"}

2.  Klik button **Filter** kemudian sistem menampilkan form filter
    > dokumen yang akan dicetak

> ![](.//media/image345.png){width="5.478472222222222in"
> height="2.6411679790026246in"}

3.  Pilih filter yang akan dicetak kemudian klik **Filter**

> ![](.//media/image346.png){width="5.478472222222222in"
> height="2.6411679790026246in"}

4.  Data akan tampil berdasarkan filter yang sudah dipilih kemudian klik
    > tombol **Excel** untuk mencetak

> ![](.//media/image347.png){width="5.478472222222222in"
> height="2.641169072615923in"}

#### Melakukan Request Nomor Offline

**Role yang sesuai**

-   Sekretaris

> Pengajuan nomor offline digunakan untuk *request* pemrosesan nomor
> dokumen secara offline. Langkah-langkah untuk melakukan *request*
> nomor offline adalah sebagai berikut

1.  Klik menu **Document Control** dan pilih tab **Request Offline
    > Number**

> ![](.//media/image348.png){width="5.5094346019247595in"
> height="2.6560958005249344in"}

2.  Klik button "+" untuk melakukan *request* nomor offline

> ![](.//media/image349.png){width="5.479166666666667in"
> height="2.641502624671916in"}

3.  Sistem menampilkan form **Request Nomor Offline.** Isi form dan klik
    > **Send**

> ![](.//media/image350.png){width="5.509027777777778in"
> height="2.655898950131234in"}

4.  Sistem berhasil menyimpan perubahan dan nomor offline yang sudah di
    > *request* akan tampil di halaman daftar **Request Nomor Offline**
    > dengan status **Waiting**

> ![](.//media/image351.png){width="5.471698381452319in"
> height="2.6433442694663167in"}

#### Menyetujui Pengajuan Nomor Offline

**Role yang sesuai**

-   Admin Approver Offline Number

> Admin Approver Offline Number dapat melakukan tindak lanjut terhadap
> pengajuan nomor offline dengan menyetujui pengajuan yang diajukan oleh
> sekretaris. Langkah-langkah untuk menyetujui pengajuan nomor adalah
> sebagai berikut

1.  Klik menu **Document Control** dan pilih tab **Approval List**

> ![](.//media/image352.png){width="5.487426727909011in"
> height="2.650942694663167in"}

2.  Pilih nomor offline yang akan disetujui kemudian pilih tombol
    > **Approve**

> ![](.//media/image353.png){width="5.490566491688539in"
> height="2.6524595363079615in"}

3.  Sistem berhasil menyimpan perubahan dan nomor offline yang disetujui
    > akan tampil di menu "**Document Control -- List Approval
    > Request**" dengan status **Approved** pada role admin P-Office.
    > Sedangkan untuk role sekretaris tersimpan di menu "**Document
    > Control -- Request Offline Number**" dengan status **Approved**

    1.  #### Menolak Pengajuan Nomor Offline

**Role yang sesuai**

-   Admin Approver Offline Number

> Admin Approver Offline Number dapat melakukan tindak lanjut terhadap
> pengajuan nomor offline dengan menolak /*reject* pengajuan yang
> diajukan oleh sekretaris. Langkah-langkah untuk menolak pengajuan
> nomor adalah sebagai berikut

1.  Klik menu **Document Control** dan pilih tab **Approval List**

> ![](.//media/image352.png){width="5.487426727909011in"
> height="2.650942694663167in"}

2.  Pilih nomor offline yang akan ditolak kemudian pilih tombol
    > **Reject**

> ![](.//media/image354.png){width="5.486805555555556in"
> height="2.6506419510061243in"}

3.  Sistem berhasil menyimpan perubahan dan nomor offline yang ditolak
    > akan tampil di menu "**Document Control -- List Approval
    > Request**" dengan status **Rejected** pada role admin P-Office.
    > Sedangkan untuk role sekretaris tersimpan di menu "**Document
    > Control -- Request Offline Number**" dengan status **Rejected**

    1.  #### Menunggah Dokumen Nomor Offline

**Role yang sesuai**

-   Sekretaris

> Sekretaris dapat mengunggah dokumen permasing-masing nomor offline
> yang sudah di-*request.* Sekretaris yang sudah meunggah dokumen nomor
> offline dapat melakukan pengajuan nomor kembali maksimal 5 kali
> *request*. Langkah-langkah untuk mengunggah dokumen nomor offline
> adalah sebagai berikut

1.  Klik menu **Document Control** dan pilih tab **Request Nomor
    > Offline**

> ![](.//media/image355.png){width="5.490566491688539in"
> height="2.6524595363079615in"}

2.  Pilih nomor offline yang akan diunggah dokumennya dengan klik tombol
    > **Detail**

> ![](.//media/image356.png){width="5.462264873140858in"
> height="2.6387871828521434in"}

3.  Sistem menampilkan detail nomor offline dan daftar nomor berapa saja
    > yang di-*request.*

> ![](.//media/image357.png){width="5.471698381452319in"
> height="2.6433442694663167in"}

4.  Pilih tombol **Upload File** dan pilih file yang akan diunggah

> ![](.//media/image358.png){width="5.471527777777778in"
> height="2.6432622484689414in"}

5.  Sistem berhasil menunggah dokumen/file nomor offline. File yang
    > sudah diunggah muncul di halaman detail nomor offline dan hasil
    > unggahan dapat di unduh oleh *user*

> ![](.//media/image359.png){width="5.487430008748906in"
> height="2.6509437882764653in"}

#### Mengembalikan Nomor Offline

**Role yang sesuai**

-   Sekretaris

**Ditujukan untuk**

-   Admin Approver Offline Number

> Sekretaris dapat mengembalikan nomor offline yang sudah di-*request*.
> Langkah-langkah untuk mengembalikan nomor offline adalah sebagai
> berikut

1.  Klik menu **Document Control** dan pilih tab **Request Nomor
    > Offline**

> ![](.//media/image355.png){width="5.490566491688539in"
> height="2.6524595363079615in"}

2.  Pilih nomor offline yang akan dikembalikan dengan klik tombol
    > **Detail**

> ![](.//media/image356.png){width="5.462264873140858in"
> height="2.6387871828521434in"}

3.  Sistem menampilkan detail nomor offline dan daftar nomor berapa saja
    > yang di-*request.*

> ![](.//media/image357.png){width="5.471698381452319in"
> height="2.6433442694663167in"}

4.  Pilih tombol **Batalkan**

> ![](.//media/image360.png){width="5.471527777777778in"
> height="2.6432622484689414in"}

5.  Nomor yang dikembalikan akan berubah status menjadi **Nomor
    > Dikembalikan** dan pengembalian nomor akan tersimpan di menu
    > "**Document Control -- List Returned Request**" pada role admin
    > P-Office.

> ![](.//media/image361.png){width="5.4483727034120735in"
> height="2.632075678040245in"}

#### Menyetujui Pengembalian Nomor Offline

**Role yang sesuai**

-   Admin Approver Offline Number

**Ditujukan untuk**

-   Sekretaris

> Admin Approver Offline Number dapat menyetujui pengembalian nomor
> offline yang dikembalikan oleh sekretaris. Langkah-langkah untuk
> menyetujui pengembalian nomor offline adalah sebagai berikut

1.  Klik menu **Document Control** dan pilih tab **List Returned
    > Request**

> ![](.//media/image362.png){width="5.487430008748906in"
> height="2.6509437882764653in"}

2.  Pilih nomor offline yang akan disetujui dengan klik tombol
    > **Approve**

> ![](.//media/image363.png){width="5.5094346019247595in"
> height="2.6615748031496063in"}

3.  Sistem menampilkan berhasil menyimpan perubahan*.* Nomor yang sudah
    > disetujui akan berubah status menjadi **Approved**, sedangkan pada
    > role sekretaris nomor offline yang disetujui pengembaliannya akan
    > berubah status menjadi **Pengembalian Disetujui**

> ![](.//media/image364.png){width="5.5094346019247595in"
> height="2.6615748031496063in"}

#### Menambah Komentar Request Nomor Offline

**Role yang sesuai**

-   Sekretaris

-   Approver (Pemilik KBO)

-   Admin Approver Offline Number

> *User* dapat menambahkan komentar pada field komentar yang disediakan
> pada detail pengajuan nomor offline. Langkah-langkah untuk menambahkan
> komentar adalah sebagai berikut

1.  Klik menu **Document Control** dan pilih tab **Request Nomor
    > Offline**

> ![](.//media/image355.png){width="5.490566491688539in"
> height="2.6524595363079615in"}

2.  Pilih nomor offline yang akan ditambahkan komentar dan halaman
    > detail nomor offline akan muncul

> ![](.//media/image356.png){width="5.462264873140858in"
> height="2.6387871828521434in"}

3.  Isikan komentar kemudian klik tombol **Send**

> ![](.//media/image365.png){width="5.461805555555555in"
> height="2.638565179352581in"}

4.  Sistem menyimpan perubahan dan *user* dapat saling berkomentar pada
    > detail nomor offline
