# **Bahan Ajar: Multimedia Digital dan Interaktif**

| Mata Kuliah | Multimedia Digital dan Interaktif |
| :---- | :---- |
| **Program Studi** | D4 Teknologi Rekayasa Multimedia |
| **Institusi** | Politeknik Negeri Lhokseumawe |
| **Pertemuan** | 11-12: Mengembangkan Prototipe untuk Menciptakan Interaksi yang Efektif |
| **Level Kompetensi** | \[C3\] \- Menerapkan |
| **Dosen Pengampu** | Umri Erdiansyah |

### **A. Capaian Pembelajaran & Indikator Penilaian**

#### **Capaian Pembelajaran Mata Kuliah (CPMK 3\)**

Mahasiswa mampu mengembangkan (C3) prototipe fungsional dari sebuah desain antarmuka multimedia interaktif.

#### **Indikator Penilaian (Pertemuan 11-12)**

Melalui Proyek Mini, mahasiswa **mampu menghubungkan (C3) antar halaman/layar dan menambahkan interaksi dasar** (seperti navigasi, *hover*, dan *overlay*) menggunakan perangkat lunak desain.

#### **Tujuan Pembelajaran Pertemuan Ini**

Setelah menyelesaikan dua pertemuan ini, mahasiswa diharapkan mampu:

1. **Menjelaskan** tujuan dan manfaat *prototyping* dalam siklus *User-Centered Design*.  
2. **Mengidentifikasi** konsep inti *prototyping*: *Triggers* (Pemicu), *Actions* (Aksi), dan *Destinations* (Tujuan).  
3. **Menerapkan** fitur *prototyping* pada perangkat lunak (Figma) untuk menghubungkan beberapa layar/frame.  
4. **Mengintegrasikan** aset-aset yang telah diproduksi (ikon, tombol, gambar, video) ke dalam desain prototipe.  
5. **Membangun** sebuah prototipe interaktif (Proyek Mini) yang mensimulasikan alur pengguna utama secara *high-fidelity*.

### **B. Pendahuluan: Menghidupkan Desain Statis**

Selamat datang di pertemuan 11 dan 12\. Sejauh ini, kita telah menyelesaikan pekerjaan seorang arsitek: kita telah memahami pengguna (UCD), membuat denah (*wireframe*), dan memproduksi materialnya (aset grafis, tombol, ikon, dan video).

Namun, saat ini, desain kita masih berupa kumpulan gambar statis yang "mati". Klien, pengguna, atau dosen tidak bisa *merasakan* bagaimana pengalaman menggunakan produk kita.

Di sinilah **prototyping** berperan. *Prototyping* adalah proses merakit semua layar statis dan aset-aset tersebut menjadi sebuah **simulasi interaktif**. Tujuannya sederhana: membuat desain kita bisa diklik, disentuh, dan dirasakan seolah-olah itu adalah aplikasi sungguhan.

Ini adalah langkah krusial untuk menguji alur desain (*user flow*) kita. Apakah navigasinya membingungkan? Apakah tombolnya merespons? Apakah videonya bisa diputar? Dengan membuat prototipe, kita bisa menjawab pertanyaan ini **sebelum** satu baris kode pun ditulis. Dalam dua pertemuan ini, kita akan beralih dari *desainer* menjadi *pembangun prototipe*.

### **C. Pokok Bahasan (Pertemuan 11: Teori & Integrasi Aset)**

#### **1\. Mengapa Kita Membuat Prototipe?**

Prototipe adalah jembatan antara desain dan pengembangan. Manfaat utamanya:

* **Menguji Alur (Validasi Desain):** Apakah alur yang kita rancang masuk akal? Apakah pengguna bisa menyelesaikan tugasnya?  
* **Komunikasi Ide:** Jauh lebih mudah menunjukkan prototipe yang bisa diklik daripada menjelaskan 20 gambar statis.  
* **Umpan Balik Cepat:** Kita bisa melakukan *usability testing* (seperti di P4) pada prototipe ini untuk menemukan masalah.  
* **Menghemat Biaya:** Menemukan kesalahan di tahap ini jauh lebih murah daripada mengubah kode program yang sudah jadi.

#### **2\. Fidelity: Dari *Wireframe* ke Prototipe *Hi-Fi***

* **Prototipe Lo-Fi:** Dibuat dari *wireframe* (skala abu-abu). Berguna untuk menguji alur dasar.  
* **Prototipe Hi-Fi (Tujuan Kita):** Dibuat dari desain UI yang sudah lengkap, menggunakan warna, gambar, ikon, dan tipografi final. Ini yang akan kita buat, karena kita sudah memproduksi aset di P9 dan P10.

#### **3\. Integrasi Aset (Menyiapkan Proyek)**

Sebelum memulai *prototyping*, kita harus "merakit" semua bahan dari pertemuan sebelumnya ke dalam file desain kita di Figma.

1. **Ganti Placeholder:** Ganti semua kotak abu-abu di *wireframe* Anda dengan aset yang sebenarnya.  
2. **Gambar:** Masukkan gambar artefak yang sudah dioptimalkan (P9).  
3. **Ikon:** Ganti teks "ikon" dengan file .svg yang sudah Anda buat (P9).  
4. **Tombol:** Gunakan **Komponen Tombol (dengan *Variants*)** yang sudah Anda buat di P9.  
5. **Video:** Tempatkan file video .mp4 (P10) di layar yang sesuai (misal: "Halaman Detail Artefak"). Figma mendukung impor video secara langsung.

#### **4\. Konsep Inti Prototyping: *Triggers, Actions, Destinations***

Setiap interaksi terdiri dari tiga bagian:

1. **Trigger (Pemicu):** Aksi yang dilakukan pengguna.  
   * *Contoh: "On Click/Tap", "While Hovering", "After Delay".*  
2. **Action (Aksi):** Respons yang diberikan oleh sistem.  
   * *Contoh: "Navigate To" (Pindah Halaman), "Open Overlay" (Buka Pop-up), "Play Video".*  
3. **Destination (Tujuan):** Ke mana aksi tersebut mengarah (bisa berupa layar lain atau elemen itu sendiri).

### **D. Pokok Bahasan (Pertemuan 12: Workshop & Interaksi Dasar)**

Pertemuan ini fokus pada praktik langsung di Figma menggunakan *Prototype Tab*.

#### **1\. Indikator 1: Menghubungkan Antar Halaman (Navigasi)**

Ini adalah interaksi paling fundamental untuk membuat alur pengguna.

* **Kasus:** Membuat tombol "Mulai Tur" di *Homepage* mengarah ke *Halaman Galeri*.  
* **Cara di Figma (Prototype Tab):**  
  1. Klik tombol "Mulai Tur".  
  2. Sebuah lingkaran biru (+) akan muncul. Klik dan tarik "kabel" (*noodle*) ke *frame* "Halaman Galeri".  
  3. Atur di panel **Interaction Details**:  
     * Trigger: **On Click**  
     * Action: **Navigate To**  
     * Destination: Halaman Galeri  
     * Animation: *Slide In* (agar terasa seperti pindah halaman)

#### **2\. Indikator 2: Menambahkan Interaksi Dasar**

**A. Interaksi *Hover* (Menggunakan *Variants*)**

* **Tujuan:** Menghidupkan tombol yang kita buat di P9.  
* **Kasus:** Tombol "Lihat Detail" berubah warna saat *mouse* diarahkan ke atasnya.  
* **Cara:**  
  1. Pastikan Anda menggunakan Komponen Tombol yang memiliki *Variants* (misal: State=Default dan State=Hover).  
  2. Klik *variant* Default. Tarik koneksi ke *variant* Hover.  
  3. Atur Interaksi:  
     * Trigger: **While Hovering**  
     * Action: **Change To**  
     * Destination: State=Hover

**B. Interaksi *Overlay* (Menu atau Pop-up)**

* **Tujuan:** Menampilkan konten di atas layar saat ini.  
* **Kasus:** Membuat ikon "Menu" (hamburger) membuka *sidebar* navigasi.  
* **Cara:**  
  1. Desain menu Anda sebagai *frame* terpisah (misal, *frame* "Sidebar Menu").  
  2. Klik ikon "Menu" di *Homepage*. Tarik koneksi ke *frame* "Sidebar Menu".  
  3. Atur Interaksi:  
     * Trigger: **On Click**  
     * Action: **Open Overlay**  
     * Destination: Sidebar Menu  
  4. Atur posisi *overlay* (misal: "Top Left") dan centang "Add background dimming".  
  5. Jangan lupa buat tombol "X" di *sidebar* dengan Action \= Close Overlay.

**C. Interaksi Video**

* **Tujuan:** Mengintegrasikan aset video dari P10.  
* **Kasus:** Memutar video artefak saat ikon "Play" ditekan.  
* **Cara:**  
  1. Impor video .mp4 Anda ke *frame* (misal: "Halaman Detail").  
  2. Desain ikon "Play" di atas video tersebut.  
  3. Klik ikon "Play", tarik koneksi ke elemen Video itu sendiri.  
  4. Atur Interaksi:  
     * Trigger: **On Click**  
     * Action: **Play/Pause Video**  
     * Destination: (Video di frame tersebut)

### **E. Kriteria Proyek Mini (Pertemuan 11-12)**

**Judul Proyek:** "Prototipe Interaktif *Hi-Fi*: Tur Virtual Museum Lhokseumawe"

Deskripsi Tugas:  
Anda ditugaskan untuk merakit semua desain layar dan aset (ikon, tombol, gambar, video) yang telah Anda rancang dan produksi dalam studi kasus "Tur Virtual Museum" menjadi sebuah prototipe interaktif high-fidelity di Figma. Prototipe ini harus mensimulasikan alur pengguna utama secara fungsional.  
**Persyaratan Minimum Proyek:**

1. **Jumlah Layar:** Prototipe harus terdiri dari minimal **5 (lima) *frame* (layar)** yang berbeda dan sudah didesain (bukan *wireframe* abu-abu).  
   * *Contoh: 1\. Homepage, 2\. Galeri/Daftar Artefak, 3\. Halaman Detail Artefak (dengan Video), 4\. Halaman Kuis, 5\. Menu Overlay/Sidebar.*  
2. **Integrasi Aset:**  
   * Prototipe **wajib** menggunakan aset-aset yang telah diproduksi pada P9 dan P10 (ikon SVG, tombol komponen, gambar JPEG teroptimasi, dan video MP4).  
3. **Alur Utama (User Flow):** Harus ada minimal **satu alur pengguna yang lengkap** dan bisa diselesaikan tanpa ada *link* yang mati atau buntu.  
   * *Contoh Alur: Dari Homepage \-\> bisa klik ke Galeri \-\> bisa klik salah satu item \-\> masuk ke Detail Artefak \-\> bisa klik "Play" pada video \-\> bisa klik "Kembali" ke Galeri.*  
4. **Indikator: Menghubungkan Layar (Navigasi)**  
   * Semua tombol yang terlihat di menu navigasi utama (misal: ikon Home, Galeri, Kuis) harus berfungsi dan mengarah ke *frame* yang benar (Maps To).  
5. **Indikator: Interaksi Dasar**  
   * Prototipe **wajib** memiliki minimal **satu (1) interaksi "Open Overlay"** (misal: menu *sidebar* atau *pop-up* notifikasi) yang bisa dibuka dan ditutup.  
   * Prototipe **wajib** menunjukkan minimal **satu (1) interaksi "While Hovering"** (seperti pada komponen tombol P9).  
   * Prototipe **wajib** memiliki minimal **satu (1) interaksi video** (Play/Pause Video) untuk aset video dari P10.

**Pengumpulan:**

* Kumpulkan **satu (1) link prototipe Figma**.  
* Pastikan pengaturan *sharing* diatur ke **"Anyone with the link can view"**.  
* Kirimkan link yang mengarah langsung ke **mode Presentasi (Prototype)** (klik tombol "Play" lalu salin URL).

**Matriks Penilaian Proyek Mini:**

| Kriteria Penilaian | Bobot | Deskripsi |
| :---- | :---- | :---- |
| **Kelengkapan Alur Pengguna & Navigasi** (Indikator 1\) | 35% | Alur utama berfungsi lancar, minimal 5 layar terhubung dengan logis. |
| **Integrasi Aset (P9 & P10)** | 25% | Aset (ikon, gambar, video) dari tugas sebelumnya terintegrasi dengan baik. |
| **Penerapan Interaksi Dasar (Indikator 2\)** | 40% | Interaksi Overlay, Hover, dan Video berhasil diterapkan dan berfungsi sesuai syarat. |
| **Total** | 100% |  |

