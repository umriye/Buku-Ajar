# **Bahan Ajar: Multimedia Digital dan Interaktif**

| Mata Kuliah | Multimedia Digital dan Interaktif |
| :---- | :---- |
| **Program Studi** | D4 Teknologi Rekayasa Multimedia |
| **Institusi** | Politeknik Negeri Lhokseumawe |
| **Pertemuan** | 10: Mengintegrasikan Audio dan Video Menggunakan Perangkat Lunak Editing |
| **Level Kompetensi** | \[C3\] \- Menerapkan |
| **Dosen Pengampu** | \[Nama Dosen Pengampu\] |

### **A. Capaian Pembelajaran & Indikator Penilaian**

#### **Capaian Pembelajaran Mata Kuliah (CPMK 2\)**

Mahasiswa mampu merancang *user interface* (UI) dan *user experience* (UX) untuk aplikasi multimedia interaktif menggunakan proses desain yang berpusat pada pengguna.

#### **Indikator Penilaian (Pertemuan 10\)**

Melalui tugas praktik, mahasiswa **mampu melakukan (C3) editing dasar dan kompresi audio/video** agar siap digunakan sebagai aset pada platform digital (web/mobile).

#### **Tujuan Pembelajaran Pertemuan Ini**

Setelah menyelesaikan pertemuan ini, mahasiswa diharapkan mampu:

1. **Mengoperasikan** fitur dasar perangkat lunak *Non-Linear Editing* (NLE) untuk menggabungkan klip video dan audio.  
2. **Menerapkan** teknik editing dasar seperti *cutting*, *trimming*, dan penambahan *text overlay*.  
3. **Menerapkan** teknik integrasi audio dasar (pengaturan level BGM).  
4. **Menganalisis** parameter kompresi video (Codec, Bitrate, Resolusi) untuk optimasi.  
5. **Mengekspor** hasil editing menjadi file video final yang terkompresi dan efisien.

### **B. Pendahuluan: Menghidupkan Aset**

Selamat datang di pertemuan kesepuluh\! Minggu lalu, kita telah fokus memproduksi dan mengoptimalkan **aset statis** (ikon SVG, tombol, gambar JPEG). Kita belajar bahwa ukuran file dan format adalah kunci utama performa aplikasi.

Hari ini, kita akan menaiki level kesulitan: mengelola **aset dinamis** (audio dan video). Video adalah "aset terberat" di dunia digital. Sebuah video 10 detik yang tidak dioptimalkan bisa lebih berat daripada keseluruhan aset gambar di aplikasi Anda.

Dalam konteks proyek "Tur Virtual Museum" kita, video bisa digunakan sebagai intro, penjelasan artefak, atau profil sejarah. Sebagai perekayasa multimedia, tantangan kita bukan hanya "membuat video", tapi "bagaimana **mengintegrasikan** video dan audio" tersebut ke dalam desain *wireframe* kita agar berjalan mulus di platform web/mobile. Ini membutuhkan dua keterampilan: **editing dasar** (untuk menyusun cerita) dan **kompresi cerdas** (untuk memastikan performa).

### **C. Pokok Bahasan**

#### **1\. Konsep Dasar: *Non-Linear Editing* (NLE)**

Perangkat lunak seperti **Adobe Premiere Pro, DaVinci Resolve, CapCut, atau Filmora** adalah *Non-Linear Editor* (NLE). Disebut "non-linear" karena kita bisa menyusun, memotong, dan memindahkan klip video/audio di *timeline* secara acak, tanpa merusak file aslinya.

Tiga area kerja utama di setiap NLE:

1. **Media Pool/Bin:** Tempat mengimpor dan mengorganisir semua file mentah (video, audio, gambar).  
2. **Timeline/Sequence:** Area kerja utama tempat Anda menyusun klip secara berurutan, memotong, dan menambahkan lapisan (misal: audio di bawah video).  
3. **Program Monitor/Preview:** Jendela untuk melihat hasil editan Anda secara *real-time*.

#### **2\. Praktik 1: Editing Dasar (Menggabungkan Aset)**

Indikator pertama adalah "editing dasar". Ini mencakup:

* **Importing:** Memasukkan klip video dan file audio (misal: musik latar/BGM) ke dalam *Media Pool*.  
* **Sequencing & Splicing:** Menarik klip video ke *timeline* (misal: V1 \- Video Track 1\) dan menyusunnya secara berurutan.  
* **Cutting/Trimming:** Menggunakan *tool* (seperti *Razor Tool* atau *Cut*) untuk memotong bagian yang tidak diinginkan, atau menyeret ujung klip untuk memperpendek (trim).  
* **Text Overlay:** Menambahkan lapisan teks di atas video (di *track* V2) untuk memberi judul atau keterangan.  
* **Integrating Audio:** Menarik file BGM ke *timeline* audio (misal: A2 \- Audio Track 2), di bawah audio asli video (di A1).  
* **Basic Audio Mixing:** Ini adalah inti dari "integrasi". Jika BGM Anda terlalu keras, video Anda akan rusak.  
  * **Teknik:** Menurunkan *gain* atau *volume* di seluruh *track* A2 (misal: ke \-15dB) agar BGM terdengar samar-samar dan tidak menutupi audio utama.

#### **3\. Praktik 2: Kompresi (Optimasi Aset Dinamis)**

Ini adalah indikator kedua dan yang paling krusial untuk multimedia interaktif. Saat Anda menekan "Export" atau "Render", Anda sedang melakukan **kompresi**.

* **Kenapa Kompresi?** File video mentah dari kamera (RAW) bisa berukuran puluhan GB. Kompresi "memperkecil" ukuran file agar bisa di-streaming di web.  
* **Dua Konsep Kunci: Codec & Container**  
  1. **Container (.mp4, .mov, .mkv):** Ini adalah "kotak" atau "wadah" yang membungkus video, audio, dan *metadata*. **.MP4** adalah standar universal untuk web dan mobile.  
  2. **Codec (H.264, H.265, AAC):** Ini adalah "algoritma" yang melakukan kompresi.  
     * **Video Codec:** **H.264 (atau AVC)** adalah codec paling umum dan kompatibel di seluruh perangkat.  
     * **Audio Codec:** **AAC** adalah standar untuk audio terkompresi, pasangan dari H.264.  
* **Tiga Pengaturan Kunci Saat Ekspor:**  
  1. **Resolusi:** Ukuran frame video (misal: **1920x1080** atau 1080p).  
  2. **Frame Rate (FPS):** Jumlah gambar per detik (misal: **30 fps**).  
  3. **Bitrate (SANGAT PENTING):** Ini adalah **raja** dari kualitas vs. ukuran file. Bitrate adalah jumlah data yang dialokasikan per detik.  
     * Bitrate Tinggi \= Kualitas Bagus, File Besar.  
     * Bitrate Rendah \= Kualitas Buruk, File Kecil.

**Aturan Praktis (Rule of Thumb) untuk Web/Mobile (1080p, 30fps):**

* **Video Bitrate:** 4,000 \- 6,000 kbps (atau 4-6 Mbps).  
* **Audio Bitrate:** 128 \- 192 kbps.

### **D. Rangkuman**

Hari ini kita belajar bahwa "membuat video" untuk platform digital memiliki dua sisi:

1. **Sisi Kreatif (Editing Dasar):** Menggunakan NLE untuk menggabungkan klip video, teks, dan audio (integrasi) di *timeline* untuk menyampaikan informasi.  
2. **Sisi Teknis (Kompresi):** Menggunakan pengaturan ekspor yang tepat (**H.264 Codec**, dalam **.MP4 Container**, dengan **Bitrate** yang terkontrol) untuk menyeimbangkan kualitas visual dengan ukuran file yang efisien.

### **E. Kriteria Tugas Praktik (Pertemuan 10\)**

**Judul Tugas:** "Membuat Aset Video untuk Tur Virtual Museum"

**Tujuan:** Menerapkan C3 dengan melakukan editing dasar dan kompresi untuk menghasilkan video pendek yang relevan dengan studi kasus dan siap diunggah ke web/aplikasi.

**Spesifikasi Tugas:**

1. **Cari Bahan:**  
   * Unduh 2-3 klip video *stock* gratis yang relevan dengan tema **museum, sejarah, artefak, atau budaya** (misal: dari Pexels.com, Pixabay.com).  
   * Unduh 1 file musik *royalty-free* dengan nuansa **tenang, edukatif, atau sinematik** (misal: dari Pixabay Music).  
2. **Gunakan Perangkat Lunak:** Buka *Non-Linear Editor* (NLE) apapun (Premiere, DaVinci, CapCut PC, Filmora, dll).  
3. **Lakukan Editing Dasar:**  
   * Buat *sequence* baru (1080p, 30fps).  
   * Susun 2-3 klip video Anda di *timeline* hingga durasi total **minimal 15 detik, maksimal 20 detik**.  
   * Tambahkan 1 transisi sederhana (misal: *Cross Dissolve*) di antara dua klip.  
   * **Wajib:** Tambahkan 1 *text overlay* (Judul) sederhana di awal video yang relevan dengan konten (misal: "Artefak Abad ke-18" atau "Sejarah Lhokseumawe").  
4. **Lakukan Integrasi Audio:**  
   * Masukkan musik BGM di *track* audio terpisah.  
   * Potong durasi musik agar sesuai dengan video.  
   * **Wajib:** Atur level volume musik (BGM) agar terdengar jelas namun tidak terlalu keras (misalnya, atur *gain* ke \-15dB atau \-18dB).  
5. **Lakukan Kompresi & Ekspor:**  
   * Ekspor video Anda dengan pengaturan **wajib** berikut:  
     * Format/Container: **.MP4**  
     * Video Codec: **H.264**  
     * Resolusi: **1920x1080**  
     * Frame Rate: 30 fps  
     * Video Bitrate: Target **4,000 kbps** (atau 4 Mbps).  
     * Audio Codec: **AAC**, Bitrate: **128 kbps**.

**Kriteria Penilaian & Pengumpulan:**

* **Output yang Dikumpulkan:**  
  1. File video final: NIM\_VideoAsetMuseum.mp4  
  2. Satu *screenshot* yang **memperlihatkan pengaturan ekspor Anda** (ini membuktikan Anda mengatur bitrate, codec, dll): NIM\_SettingsEkspor.jpg  
* **Penilaian Indikator (Lulus/Tidak Lulus):**  
  * \[ \] **Relevansi Tema:** Video yang dihasilkan sesuai dengan tema museum/sejarah.  
  * \[ \] **Editing Dasar:** Durasi 15-20 detik, ada *text overlay*, dan ada transisi.  
  * \[ \] **Integrasi Audio:** Musik BGM ada dan volumenya seimbang/tidak pecah.  
  * \[ \] **Kompresi:**  
    * File yang dikumpulkan adalah .mp4.  
    * Ukuran file final untuk video 20 detik harus **di bawah 15 MB**. (Jika file Anda 100MB, berarti pengaturan bitrate Anda gagal).  
    * *Screenshot* pengaturan ekspor dilampirkan dan sesuai spesifikasi.