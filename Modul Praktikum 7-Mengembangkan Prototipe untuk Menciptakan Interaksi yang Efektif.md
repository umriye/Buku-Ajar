# **Bahan Ajar: Multimedia Digital dan Interaktif**

| Mata Kuliah | Multimedia Digital dan Interaktif |
| :---- | :---- |
| **Program Studi** | D4 Teknologi Rekayasa Multimedia |
| **Institusi** | Politeknik Negeri Lhokseumawe |
| **Pertemuan** | 11-12: Mengembangkan Prototipe untuk Menciptakan Interaksi yang Efektif |
| **Level Kompetensi** | \[C3\] \- Menerapkan |
| **Dosen Pengampu** | Umri Erdiansyah |

---

### **A. Capaian Pembelajaran & Indikator Penilaian**

#### **Capaian Pembelajaran Mata Kuliah (CPMK 3\)**

Mahasiswa mampu mengembangkan (C3) prototipe fungsional dari sebuah desain antarmuka multimedia interaktif.

#### **Indikator Penilaian (Pertemuan 11-12)**

Melalui Proyek Mini, mahasiswa **mampu menghubungkan (C3) antar halaman/layar dan menambahkan interaksi dasar** (seperti navigasi, *hover*, *overlay*, dan kontrol video) menggunakan perangkat lunak desain Figma.

#### **Tujuan Pembelajaran Pertemuan Ini**

Setelah menyelesaikan dua pertemuan ini, mahasiswa diharapkan mampu:

1. **Menjelaskan** tujuan dan manfaat *prototyping* dalam siklus *User-Centered Design* (UCD).
2. **Membedakan** tingkatan *fidelity* prototipe dan memilih tingkatan yang tepat sesuai kebutuhan.
3. **Mengidentifikasi** konsep inti *prototyping*: *Triggers* (Pemicu), *Actions* (Aksi), dan *Destinations* (Tujuan).
4. **Mengoperasikan** antarmuka *Prototype Tab* di Figma secara sistematis.
5. **Menerapkan** fitur *prototyping* pada Figma untuk menghubungkan beberapa layar/*frame*.
6. **Mengintegrasikan** aset-aset yang telah diproduksi (ikon, tombol, gambar, video) ke dalam desain prototipe.
7. **Membangun** sebuah prototipe interaktif (Proyek Mini) yang mensimulasikan alur pengguna utama secara *high-fidelity*.
8. **Menguji** prototipe menggunakan mode Presentasi Figma dan berbagi hasilnya kepada pemangku kepentingan.

---

### **B. Pendahuluan: Menghidupkan Desain Statis**

Selamat datang di pertemuan 11 dan 12\! Sejauh ini, kita telah menyelesaikan pekerjaan seorang arsitek: kita telah memahami pengguna (UCD), membuat denah (*wireframe*), dan memproduksi materialnya (aset grafis, tombol, ikon, dan video).

Namun, saat ini, desain kita masih berupa kumpulan gambar statis yang "mati". Klien, pengguna, atau dosen tidak bisa *merasakan* bagaimana pengalaman menggunakan produk kita.

Di sinilah **prototyping** berperan. *Prototyping* adalah proses merakit semua layar statis dan aset-aset tersebut menjadi sebuah **simulasi interaktif**. Tujuannya sederhana: membuat desain kita bisa diklik, disentuh, dan dirasakan seolah-olah itu adalah aplikasi sungguhan.

Ini adalah langkah krusial untuk menguji alur desain (*user flow*) kita. Apakah navigasinya membingungkan? Apakah tombolnya merespons? Apakah videonya bisa diputar? Dengan membuat prototipe, kita bisa menjawab pertanyaan ini **sebelum** satu baris kode pun ditulis. Dalam dua pertemuan ini, kita akan beralih dari *desainer* menjadi *pembangun prototipe*.

#### **Mengapa Ini Penting bagi Perekayasa Multimedia?**

Sebagai mahasiswa D4 Teknologi Rekayasa Multimedia, Anda berada di persimpangan antara desain dan rekayasa. Kemampuan membuat prototipe yang meyakinkan memberi Anda keuntungan ganda:

* **Dari sisi desain:** Anda bisa menguji dan memvalidasi ide sebelum menghabiskan waktu mengoding.
* **Dari sisi rekayasa:** Prototipe Figma yang detail berfungsi sebagai **spesifikasi teknis** yang presisi bagi *developer*. Mereka bisa langsung melihat ukuran, warna, font, dan alur interaksi tanpa perlu menebak-nebak.

---

### **C. Pokok Bahasan Pertemuan 11: Fondasi Prototyping & Integrasi Aset**

#### **1\. Mengapa Kita Membuat Prototipe? (Justifikasi Mendalam)**

Prototipe adalah jembatan antara desain dan pengembangan. Manfaat utamanya mencakup empat dimensi:

**a. Validasi Desain (Menguji Alur)**

Apakah alur yang kita rancang masuk akal bagi pengguna? Apakah mereka bisa menyelesaikan tugasnya tanpa tersesat? Prototipe memungkinkan kita menjawab pertanyaan ini melalui *usability testing* sebelum tahap pengembangan.

> *Contoh:* Pada proyek Tur Virtual Museum, apakah pengguna tahu cara berpindah dari Galeri ke Detail Artefak? Apakah mereka menemukan tombol "Kembali" dengan mudah? Ini hanya bisa dijawab dengan menguji prototipe.

**b. Komunikasi Ide yang Efektif**

Jauh lebih efektif menunjukkan prototipe yang bisa diklik daripada menjelaskan 20 gambar statis kepada klien atau stakeholder. Sebuah klik lebih berbicara dari seribu kata.

**c. Umpan Balik Cepat (Iterasi Lebih Efisien)**

Mengubah warna tombol, memindahkan elemen, atau mengubah alur di Figma hanya membutuhkan hitungan menit. Mengubah hal yang sama di aplikasi yang sudah dikoding bisa memakan waktu berjam-jam.

**d. Menghemat Biaya Pengembangan**

Riset industri menunjukkan bahwa **biaya memperbaiki bug desain meningkat drastis seiring dengan tahap pengembangan**. Menemukan masalah di tahap prototipe jauh lebih murah dan cepat daripada memperbaikinya setelah kode ditulis.

| Tahap Penemuan Masalah | Relatif Biaya Perbaikan |
| :---- | :---- |
| Prototipe / Desain | 1x |
| Pengembangan (Coding) | 5x |
| Setelah Rilis (Production) | 50x - 100x |

---

#### **2\. Taksonomi Fidelity: Spektrum dari Sketsa ke Simulasi**

*Fidelity* adalah tingkat detail dan ketepatan sebuah prototipe dibandingkan produk akhir. Memahami spektrum ini membantu Anda memilih alat yang tepat untuk tujuan yang tepat.

**a. Prototipe Lo-Fi (Low Fidelity)**

* **Bentuk:** Sketsa tangan di kertas atau bentuk-bentuk dasar abu-abu di Figma (tanpa warna, font spesifik, atau gambar nyata).
* **Tujuan:** Menguji alur dasar dan struktur informasi. Sangat cepat dibuat.
* **Kapan Digunakan:** Di awal proyek, saat ide masih kasar dan perlu banyak eksplorasi. Ini yang kita lakukan di P3 dan P4.
* **Kelemahan:** Tidak cukup realistis untuk menguji aspek visual atau interaksi halus.

**b. Prototipe Mid-Fi (Medium Fidelity)**

* **Bentuk:** *Wireframe* digital yang lebih rapi, menggunakan skala abu-abu, tipografi yang lebih akurat, namun belum menggunakan warna atau gambar final.
* **Tujuan:** Memperbaiki tata letak dan alur sebelum masuk ke desain visual penuh.
* **Kapan Digunakan:** Jembatan antara Lo-Fi dan Hi-Fi.

**c. Prototipe Hi-Fi (High Fidelity) — Tujuan Kita**

* **Bentuk:** Dibuat dari desain UI yang sudah lengkap, menggunakan warna, gambar, ikon, tipografi final, dan komponen interaktif (seperti tombol dengan *states* yang kita buat di P9).
* **Tujuan:** Mensimulasikan pengalaman produk akhir seakurat mungkin. Digunakan untuk *usability testing* final, presentasi ke klien, dan handoff ke *developer*.
* **Kapan Digunakan:** Ini yang akan kita bangun, karena kita sudah memproduksi semua aset di P9 dan P10.

---

#### **3\. Mengenal Antarmuka Prototype Tab di Figma**

Sebelum mulai membuat interaksi, penting untuk memahami di mana semua kontrol berada di Figma.

**Cara Beralih ke Mode Prototipe:**

Di panel kanan Figma, Anda akan melihat tiga tab di bagian atas: **Design | Prototype | Inspect**. Klik tab **"Prototype"** untuk masuk ke mode pembuatan prototipe.

**Elemen Utama di Prototype Tab:**

**a. Device (Perangkat)**

Di bagian atas Prototype Tab, Anda bisa memilih perangkat simulasi (misal: iPhone 14, Pixel 7, Desktop). Ini akan memberi bingkai (*frame*) pada prototipe Anda saat dipresentasikan dan memastikan ukuran layar yang tepat.

**b. Starting Frame**

Ini adalah layar pertama yang akan muncul saat prototipe dijalankan. Anda bisa mengaturnya dengan mengklik *frame* yang ingin dijadikan titik awal, lalu cari opsi **"Set as starting frame"** di Prototype Tab.

**c. Interaction Panel (Panel Interaksi)**

Ini muncul di panel kanan ketika Anda memilih sebuah elemen di *canvas*. Di sinilah Anda menentukan:

* **Trigger (Pemicu):** Aksi pengguna yang memulai interaksi.
* **Action (Aksi):** Respons sistem terhadap trigger tersebut.
* **Destination (Tujuan):** Target dari aksi (layar lain atau elemen).
* **Animation (Animasi):** Jenis transisi visual.

**d. Connection Noodles (Kabel Koneksi)**

Saat Anda berada di Prototype Tab dan mengarahkan kursor ke sebuah elemen, akan muncul lingkaran biru kecil (+) di sisi kanannya. Tarik lingkaran ini ke *frame* atau elemen lain untuk membuat koneksi interaksi. Garis koneksi ini disebut "noodle".

---

#### **4\. Integrasi Aset: Merakit Semua Bahan**

Sebelum memulai *prototyping*, kita harus "merakit" semua bahan dari pertemuan sebelumnya ke dalam file desain di Figma. Ini memastikan prototipe kita adalah *Hi-Fi* yang sesungguhnya.

**Langkah-langkah Integrasi:**

1. **Audit File Figma Anda:** Buka file Figma proyek Tur Virtual Museum Anda. Lihat semua *frame* (layar) yang sudah Anda desain. Identifikasi semua elemen *placeholder* (kotak abu-abu) yang masih perlu diganti.

2. **Ganti Placeholder Gambar (P9):**
   * Pilih *placeholder* gambar (kotak abu-abu) di *frame* Anda.
   * Di panel kiri, pilih salah satu gambar artefak yang sudah Anda optimalkan di P9.
   * Drag gambar ke atas *placeholder*, atau klik ikon "+" di dalam shape dan pilih gambar dari komputer Anda.
   * Pastikan gambar terisi dengan baik menggunakan properti Fill > Image > Fill/Fit/Crop.

3. **Ganti Placeholder Ikon (P9):**
   * Pilih *placeholder* ikon Anda.
   * Di menu **Assets** panel kiri (shortcut: Ctrl+Alt+O), cari komponen ikon yang sudah Anda buat.
   * Seret ke *frame* yang sesuai, atau klik *placeholder* dan gunakan "Swap Component" jika sudah menggunakan komponen.
   * Pastikan ukuran dan posisi ikon sesuai dengan desain asli.

4. **Gunakan Komponen Tombol dengan *Variants* (P9):**
   * Pastikan semua tombol di desain Anda menggunakan komponen tombol yang sudah dibuat di P9 (bukan kotak teks biasa).
   * Menggunakan komponen adalah kunci agar interaksi *hover* bisa berfungsi.
   * Pilih elemen tombol, klik kanan > "Reset Instance" atau "Swap Component" ke komponen tombol Anda.

5. **Integrasikan Video (P10):**
   * Buka *frame* "Halaman Detail Artefak".
   * Di menu **File > Place Image/Video...** (atau seret file langsung dari *file explorer*), pilih file video **.mp4** yang sudah Anda ekspor di P10.
   * Figma mendukung impor video secara langsung. Tempatkan video di posisi yang sesuai dengan *wireframe* Anda.
   * Atur ukuran dan posisi video menggunakan *constraints* (misal: lebar 100%, tinggi proporsional).

6. **Review Final Sebelum Prototyping:**
   * Setelah semua aset terintegrasi, luangkan waktu 5-10 menit untuk me-*review* setiap *frame*.
   * Pastikan tidak ada elemen *placeholder* abu-abu yang tertinggal.
   * Pastikan semua komponen (tombol, ikon) sudah benar dan konsisten.

---

#### **5\. Konsep Inti Prototyping: *Triggers, Actions, Destinations***

Setiap interaksi dalam prototipe Figma terdiri dari tiga bagian yang saling terkait. Memahami ketiga bagian ini adalah kunci untuk membangun interaksi apapun.

**a. Trigger (Pemicu)**

Trigger adalah aksi yang dilakukan oleh pengguna yang "memicu" sebuah respons dari sistem.

| Trigger | Deskripsi | Kapan Digunakan |
| :---- | :---- | :---- |
| **On Click / On Tap** | Pengguna mengklik atau mengetuk elemen. | Navigasi halaman, membuka menu, submit form. |
| **While Hovering** | Kursor berada di atas elemen (tanpa diklik). | Efek hover pada tombol atau kartu konten. |
| **While Pressing** | Elemen sedang ditekan (mouse/jari belum dilepas). | Efek "pressed" pada tombol. |
| **On Drag** | Pengguna menyeret elemen. | Gesture swipe, slider. |
| **After Delay** | Terjadi otomatis setelah jeda waktu tertentu. | Animasi intro, transisi otomatis, loading screen. |
| **On Key/Gamepad** | Pengguna menekan tombol keyboard tertentu. | Shortcut keyboard di aplikasi desktop. |
| **Mouse Enter** | Kursor memasuki area elemen. | Menampilkan tooltip atau label. |
| **Mouse Leave** | Kursor meninggalkan area elemen. | Menyembunyikan tooltip. |

**b. Action (Aksi)**

Action adalah respons yang diberikan oleh sistem setelah trigger terpenuhi.

| Action | Deskripsi | Kapan Digunakan |
| :---- | :---- | :---- |
| **Navigate To** | Berpindah ke *frame* lain. | Navigasi antar halaman utama. |
| **Open Overlay** | Menampilkan *frame* lain di atas layar saat ini (seperti modal atau pop-up). | Menu *sidebar*, notifikasi, dialog konfirmasi. |
| **Swap With** | Mengganti *overlay* yang sedang terbuka dengan *overlay* lain. | Multi-step modal. |
| **Close Overlay** | Menutup *overlay* yang sedang terbuka. | Tombol "X" atau "Tutup" pada pop-up. |
| **Back** | Kembali ke *frame* sebelumnya dalam riwayat navigasi. | Tombol "Kembali". |
| **Change To** | Mengubah *variant* komponen saat ini menjadi *variant* lain. | Efek hover/pressed pada komponen dengan *Variants*. |
| **Scroll To** | Menggulir layar ke posisi elemen tertentu. | Navigasi "anchor" (langsung ke seksi tertentu). |
| **Play Video** | Memutar atau menjeda video yang ada di *frame*. | Kontrol video. |
| **Set Variable** | Mengubah nilai variabel (fitur lanjutan). | Logika kondisional. |
| **Conditional** | Menjalankan aksi berbeda berdasarkan kondisi (fitur lanjutan). | Alur login dengan validasi. |

**c. Destination (Tujuan)**

Destination adalah target dari sebuah aksi — bisa berupa *frame* lain, elemen di *frame* yang sama, atau (untuk *Change To*) sebuah *variant* komponen.

**d. Animation (Animasi)**

Animasi menentukan bagaimana transisi antara *frame* terlihat secara visual.

| Animasi | Efek |
| :---- | :---- |
| **Instant** | Langsung berpindah tanpa efek. |
| **Dissolve** | Fade in/out lembut. |
| **Smart Animate** | Figma secara otomatis menganimasikan perubahan antara dua *frame* (sangat powerful). |
| **Slide In/Out** | Geser dari arah tertentu (kiri, kanan, atas, bawah). |
| **Push** | Kedua *frame* bergerak bersamaan. |
| **Move In/Out** | Hanya *frame* baru yang bergerak masuk. |

---

### **D. Pokok Bahasan Pertemuan 12: Workshop Interaktif — Membangun Semua Koneksi**

Pertemuan ini adalah sesi workshop intensif. Anda akan membangun semua interaksi prototipe secara langsung di Figma menggunakan *Prototype Tab*. Ikuti setiap langkah dengan teliti.

#### **1\. Persiapan: Mengatur *Starting Frame* dan Device**

Sebelum membuat interaksi apapun, atur pengaturan dasar prototipe.

1. Klik di area kosong *canvas* (jangan klik *frame* apapun) untuk memastikan tidak ada elemen yang dipilih.
2. Di Prototype Tab (panel kanan), Anda akan melihat opsi **Device** dan **Starting Frame**.
3. Atur **Device** sesuai target platform Anda (misal: **iPhone 14** untuk mobile).
4. Klik *frame* "Halaman Utama/Homepage" Anda.
5. Di Prototype Tab, klik **"Set as starting frame"** (biasanya berupa tombol atau opsi di panel). Sebuah ikon rumah kecil akan muncul di pojok kiri atas *frame* tersebut, menandakan ini adalah halaman awal.

#### **2\. Indikator 1: Menghubungkan Antar Halaman (Navigasi Utama)**

Ini adalah interaksi paling fundamental. Kita akan membuat semua tombol navigasi utama berfungsi.

**Contoh Kasus A: Tombol "Mulai Tur" → Halaman Galeri**

1. Di Prototype Tab, klik tombol "Mulai Tur" di *frame* Homepage.
2. Lingkaran biru (+) akan muncul di sisi kanan tombol. **Klik dan tahan**, lalu **tarik kabel (*noodle*)** ke *frame* "Halaman Galeri".
3. Setelah Anda melepaskan mouse, panel **Interaction Details** akan muncul di panel kanan. Atur:
   * **Trigger:** On Click
   * **Action:** Navigate To
   * **Destination:** Halaman Galeri
   * **Animation:** Slide In (dari kanan), Durasi: 300ms, *Easing*: Ease Out
4. Tekan **Enter** atau klik di luar panel untuk menyimpan.
5. **Verifikasi:** Tekan **Ctrl+Alt+Enter** (atau klik tombol "Play" ▶ di pojok kanan atas) untuk masuk ke Mode Presentasi. Klik tombol "Mulai Tur" — Anda harus berpindah ke Halaman Galeri.

**Contoh Kasus B: Ikon Navigasi Bawah (Bottom Navigation Bar)**

Jika desain Anda memiliki *bottom navigation bar* (seperti aplikasi mobile pada umumnya), setiap ikon harus dihubungkan:

1. Klik ikon "Home" di *bottom navigation bar*.
2. Tarik kabel ke *frame* "Homepage".
3. Atur: On Click → Navigate To → Homepage → Instant (karena ini navigasi tab, bukan pindah halaman).
4. Ulangi untuk ikon "Galeri" → Halaman Galeri, ikon "Kuis" → Halaman Kuis.

**Tips Penting:** Untuk elemen yang muncul di semua halaman (seperti *bottom navigation bar*), Anda perlu menghubungkannya di **setiap *frame*** di mana elemen tersebut muncul.

**Contoh Kasus C: Item Galeri → Halaman Detail Artefak**

1. Klik salah satu kartu/item artefak di Halaman Galeri.
2. Tarik kabel ke *frame* "Halaman Detail Artefak".
3. Atur: On Click → Navigate To → Halaman Detail Artefak → Smart Animate, Durasi: 350ms
4. Klik tombol "Kembali" di Halaman Detail Artefak.
5. Tarik kabel ke *frame* "Halaman Galeri".
6. Atur: On Click → **Back** (gunakan Back, bukan Navigate To, agar riwayat navigasi terjaga).

#### **3\. Indikator 2: Interaksi Dasar — *Hover* pada Tombol Komponen**

Interaksi *hover* menggunakan *Variants* yang telah dibuat di P9. Pastikan tombol-tombol di desain Anda sudah menggunakan komponen tombol dengan *Variants*.

**Langkah-langkah:**

1. Masuk ke *file* komponen Anda (di panel Assets, klik dua kali komponen Tombol untuk membukanya di editor).
2. Pastikan komponen memiliki minimal dua *Variants*: **State=Default** dan **State=Hover**.
3. Dalam editor komponen, **klik *variant* State=Default**.
4. Di Prototype Tab, tarik kabel dari *variant* Default ke *variant* Hover.
5. Di Interaction Details, atur:
   * **Trigger:** While Hovering
   * **Action:** Change To
   * **Destination:** State=Hover
   * **Animation:** Dissolve atau Smart Animate, Durasi: 150ms
6. Kembali ke *frame* desain utama Anda. **Setiap instance** komponen tombol tersebut sekarang **otomatis** memiliki efek *hover* — Anda tidak perlu mengaturnya satu per satu\!

> **Catatan Penting:** Interaksi *hover* hanya bisa diuji di Mode Presentasi menggunakan **browser/desktop**, bukan di aplikasi Figma mobile.

#### **4\. Indikator 2: Interaksi Dasar — *Overlay* (Menu Sidebar / Pop-up)**

*Overlay* menampilkan konten di atas layar saat ini tanpa berpindah halaman.

**Contoh Kasus: Menu Hamburger → Sidebar Navigasi**

1. **Siapkan *Frame* Sidebar:** Buat (atau pastikan sudah ada) sebuah *frame* terpisah bernama "Sidebar Menu" yang berisi daftar menu navigasi.
   * Posisikan *frame* ini di *canvas* (bisa di mana saja, tidak harus di dalam *frame* halaman).
   * Desain *frame* ini dengan lebar yang sesuai (misal: 280px dari kiri).
   * Jangan lupa tambahkan tombol "X" atau area gelap untuk menutup *sidebar*.

2. **Buat Koneksi Buka:**
   * Klik ikon menu "hamburger" (≡) di Homepage.
   * Di Prototype Tab, tarik kabel ke *frame* "Sidebar Menu".
   * Atur Interaction Details:
     * **Trigger:** On Click
     * **Action:** Open Overlay
     * **Destination:** Sidebar Menu
     * **Position:** Manual (atur ke sisi kiri layar, X=0, Y=0)
     * Centang **"Add background behind overlay"** dan atur opasitas ke 40% untuk efek *dimming*.
     * Centang **"Close when clicking outside"** untuk memudahkan pengguna menutup menu.
   * **Animation:** Move In, dari kiri, Durasi: 300ms.

3. **Buat Koneksi Tutup:**
   * Klik tombol "X" di dalam *frame* "Sidebar Menu".
   * Tarik kabel kembali ke *frame* "Sidebar Menu" itu sendiri (kabel ke elemen itu sendiri adalah cara standar untuk Close Overlay).
   * Atur:
     * **Trigger:** On Click
     * **Action:** Close Overlay
   * **Animation:** Move Out, ke kiri, Durasi: 250ms.

4. **Verifikasi:** Jalankan Mode Presentasi. Klik ikon menu — *sidebar* harus muncul dari kiri dengan latar belakang yang menggelap. Klik "X" — *sidebar* harus menghilang.

#### **5\. Indikator 2: Interaksi Dasar — Kontrol Video**

Figma mendukung pemutaran video secara langsung dalam prototipe.

**Contoh Kasus: Tombol Play → Putar Video Artefak**

1. Buka *frame* "Halaman Detail Artefak" di mana video sudah diintegrasikan.
2. Klik elemen video yang sudah diimpor (file .mp4 Anda).
3. Di **Design Tab** (bukan Prototype Tab), pastikan video ada dan bisa diputar dengan mengklik ikon Play di thumbnail video.

4. **Interaksi Kontrol Play/Pause:**
   * Klik tombol atau ikon "Play" yang Anda desain di atas video.
   * Di Prototype Tab, tarik kabel dari ikon "Play" ke **elemen video** di *frame* yang sama.
   * Atur Interaction Details:
     * **Trigger:** On Click
     * **Action:** Play/Pause Video
     * **Destination:** (pilih elemen video di frame)
   * Figma akan otomatis memutar/menjeda video saat tombol diklik.

5. **Verifikasi:** Jalankan Mode Presentasi di browser. Navigasi ke Halaman Detail Artefak. Klik tombol Play — video harus mulai diputar.

> **Catatan:** Pemutaran video di prototipe Figma hanya berfungsi di **Mode Presentasi via Browser** (bukan di aplikasi desktop atau mobile Figma). Pastikan Anda mengujinya di browser.

#### **6\. Interaksi Lanjutan: Scroll Behavior dan Fixed Elements**

Ini adalah teknik penting untuk mensimulasikan *scrolling* halaman seperti di aplikasi nyata.

**a. Mengaktifkan Scroll pada Frame**

Jika konten halaman Anda lebih panjang dari tinggi layar:

1. Klik *frame* halaman Anda (misal: Halaman Galeri).
2. Di panel **Design**, temukan properti **Clip Content** — centang opsi ini agar konten di luar batas *frame* tidak terlihat.
3. Tambahkan konten di bawah batas tinggi layar (biarkan *frame* tetap di ukuran layar standar, tapi isi konten lebih panjang).
4. Di Prototype Tab, di bagian **Scroll Behavior**, atur menjadi **Vertical Scrolling**.

**b. Membuat Elemen Tetap (*Fixed*)**

Elemen seperti *header* atau *bottom navigation bar* harus tetap di tempatnya saat pengguna *scroll*.

1. Klik elemen yang ingin dibuat tetap (misal: *bottom navigation bar*).
2. Di Design Tab, temukan properti **Constraints** atau **Layer > Fixed position when scrolling**.
3. Centang opsi **"Fix position when scrolling"**.
4. Verifikasi di Mode Presentasi — *scroll* halaman ke bawah, elemen yang di-*fix* harus tetap terlihat.

#### **7\. Interaksi Lanjutan: After Delay (Animasi Otomatis)**

Trigger *After Delay* berguna untuk membuat animasi yang berjalan otomatis.

**Contoh Kasus: Splash Screen → Homepage (Otomatis setelah 3 detik)**

1. Pastikan Anda memiliki *frame* "Splash Screen" (layar pembuka).
2. Klik di area kosong di dalam *frame* Splash Screen.
3. Di Prototype Tab, klik tombol "+" untuk menambahkan interaksi pada *frame* itu sendiri.
4. Atur:
   * **Trigger:** After Delay
   * **Delay:** 3000ms (3 detik)
   * **Action:** Navigate To
   * **Destination:** Homepage
   * **Animation:** Dissolve, Durasi: 500ms
5. Verifikasi: Mulai prototipe — Splash Screen harus otomatis berpindah ke Homepage setelah 3 detik.

#### **8\. Smart Animate: Membuat Transisi yang Halus dan Profesional**

*Smart Animate* adalah fitur Figma yang secara otomatis menganimasikan perubahan antara dua *frame* yang memiliki elemen dengan nama yang sama.

**Cara Kerja Smart Animate:**

Jika *frame* A memiliki persegi biru di pojok kiri atas, dan *frame* B memiliki persegi biru (dengan nama layer yang sama) di tengah layar — saat berpindah dari A ke B menggunakan Smart Animate, Figma akan menganimasikan persegi tersebut bergerak dari pojok kiri atas ke tengah layar secara mulus.

**Contoh Praktis untuk Proyek Museum:**

* *Frame* "Galeri": Kartu artefak berukuran kecil.
* *Frame* "Detail Artefak": Gambar artefak yang sama namun berukuran besar di bagian atas.
* Pastikan layer gambar artefak di kedua *frame* memiliki **nama yang sama persis**.
* Atur animasi dari kartu galeri ke detail artefak menggunakan **Smart Animate** — Figma akan membuat gambar artefak "membesar" dengan mulus saat transisi, menciptakan efek seperti di aplikasi foto profesional.

---

### **E. Menguji Prototipe: Mode Presentasi**

Sebelum menyerahkan atau membagikan prototipe, uji secara menyeluruh menggunakan Mode Presentasi Figma.

#### **1\. Cara Membuka Mode Presentasi**

* Klik tombol **▶ (Play/Present)** di pojok kanan atas Figma, atau tekan **Ctrl+Alt+Enter**.
* Browser akan membuka tab baru dengan prototipe Anda dalam Mode Presentasi.
* Di sisi kanan layar, Anda akan melihat panel dengan pilihan **Starting Point** dan **Device Frame**.

#### **2\. Daftar Periksa Pengujian Prototipe (Checklist)**

Gunakan daftar periksa ini untuk memastikan semua interaksi berfungsi sebelum pengumpulan:

| No. | Item Pengujian | Status |
| :---- | :---- | :---- |
| 1 | Semua tombol navigasi utama mengarah ke halaman yang benar | ☐ |
| 2 | Tombol "Kembali" di setiap halaman berfungsi | ☐ |
| 3 | Menu *sidebar*/*hamburger* bisa dibuka dan ditutup | ☐ |
| 4 | Efek *hover* pada tombol terlihat (uji di browser) | ☐ |
| 5 | Video di Halaman Detail Artefak bisa diputar/dijeda | ☐ |
| 6 | Tidak ada *link* yang "mati" (klik ke mana-mana tidak terjadi apa-apa) | ☐ |
| 7 | Alur utama bisa diselesaikan dari awal sampai akhir | ☐ |
| 8 | *Splash Screen* berpindah otomatis (jika ada) | ☐ |
| 9 | *Scroll* berfungsi pada halaman yang kontennya panjang | ☐ |
| 10 | Elemen *fixed* (header/navbar) tetap pada posisinya saat *scroll* | ☐ |

#### **3\. Panduan *Think-Aloud* Testing Mandiri**

Setelah semua interaksi berfungsi, lakukan pengujian mandiri dengan metode *Think-Aloud*:

1. **Bayangkan Anda adalah pengguna pertama kali** yang tidak tahu apa-apa tentang proyek ini.
2. **Buka prototipe di browser**, mulai dari Splash Screen.
3. **Ucapkan dengan keras** (atau tuliskan) apa yang Anda pikirkan di setiap langkah:
   * "Saya melihat tombol ini, saya pikir ini akan membawa saya ke galeri..."
   * "Saya bingung, saya tidak tahu cara kembali dari halaman ini..."
4. **Catat semua kebingungan** yang Anda rasakan — itu adalah sinyal bahwa desain perlu diperbaiki.
5. **Iterasi:** Perbaiki masalah yang ditemukan, lalu uji kembali.

---

### **F. Berbagi dan Mempresentasikan Prototipe**

#### **1\. Mengatur Izin Berbagi**

1. Klik tombol **"Share"** di pojok kanan atas Figma.
2. Di menu yang muncul, ubah pengaturan dari "Only people invited" menjadi **"Anyone with the link can view"**.
3. Klik **"Copy link"** untuk menyalin *link* file desain.

#### **2\. Mendapatkan Link Mode Presentasi**

Link Mode Presentasi (Prototype Link) berbeda dari link file desain biasa dan langsung membuka prototipe dalam mode siap diuji:

1. Klik tombol **▶ (Present)** untuk membuka Mode Presentasi di browser.
2. Salin URL dari *address bar* browser Anda — ini adalah **Prototype Link**.
3. URL ini biasanya berformat: `https://www.figma.com/proto/...`
4. Bagikan URL ini kepada dosen, klien, atau penguji.

#### **3\. Tips Presentasi yang Efektif**

Saat mempresentasikan prototipe kepada audiens:

* **Ceritakan alur, jangan hanya mengklik:** "Bayangkan seorang pelajar yang baru pertama kali membuka aplikasi ini. Mereka akan melihat Splash Screen, kemudian otomatis masuk ke Homepage..."
* **Tampilkan di perangkat nyata:** Buka prototipe di smartphone Anda menggunakan aplikasi Figma Mirror untuk presentasi yang lebih realistis.
* **Sorot interaksi penting:** Demonstrasikan setiap jenis interaksi (navigasi, hover, overlay, video) satu per satu agar audiens mengerti.
* **Siapkan backup:** Ambil *screenshot* dari setiap layar sebagai cadangan jika koneksi internet bermasalah.

---

### **G. Rangkuman Pertemuan 11-12**

Dalam dua pertemuan ini, kita telah melakukan transformasi menyeluruh:

**Dari:** Sekumpulan gambar desain statis dan aset-aset yang terpisah (ikon, tombol, gambar, video).

**Menjadi:** Sebuah prototipe interaktif *high-fidelity* yang bisa diklik, dinavigasi, dan dirasakan seperti aplikasi nyata.

Kita telah mempelajari dan menerapkan:

1. **Fondasi Prototyping:** Tujuan, manfaat, dan taksonomi *fidelity* prototipe.
2. **Antarmuka Figma:** Prototype Tab, Starting Frame, Device, dan Connection Noodles.
3. **Konsep TAD:** *Triggers, Actions, Destinations* — kerangka berpikir universal untuk semua interaksi.
4. **Interaksi Wajib:**
   * **Navigasi** antar halaman (On Click → Navigate To)
   * **Interaksi Hover** pada komponen tombol (While Hovering → Change To)
   * **Overlay** untuk menu/pop-up (On Click → Open Overlay + Close Overlay)
   * **Kontrol Video** (On Click → Play/Pause Video)
5. **Interaksi Lanjutan:** Scroll Behavior, Fixed Elements, After Delay, Smart Animate.
6. **Pengujian dan Berbagi:** Mode Presentasi, checklist pengujian, dan cara berbagi *prototype link*.

Dengan kemampuan ini, Anda tidak hanya menjadi desainer, tetapi juga seorang komunikator teknis yang dapat menjembatani visi desain dengan tim pengembang.

---

### **H. Soal Tes Formatif**

Kerjakan soal-soal berikut untuk menguji pemahaman Anda sebelum memulai Proyek Mini.

**Pilihan Ganda (Pilih satu jawaban yang paling tepat)**

**1\.** Anda ingin membuat menu *popup* kecil muncul di atas layar saat ini tanpa berpindah ke halaman baru saat pengguna mengklik tombol "Info". Kombinasi Action yang paling tepat adalah...

   a. Navigate To → Halaman Info

   b. **Open Overlay → Frame "Popup Info"** ✓

   c. Change To → Variant "Info"

   d. Back → Frame sebelumnya

**2\.** Anda memiliki komponen tombol dengan *Variants* State=Default dan State=Hover. Trigger yang tepat untuk membuat efek *hover* adalah...

   a. On Click

   b. While Pressing

   c. **While Hovering** ✓

   d. Mouse Enter

**3\.** Anda ingin *Splash Screen* berpindah otomatis ke Homepage setelah 2,5 detik tanpa pengguna mengklik apapun. Trigger yang tepat adalah...

   a. On Click

   b. On Drag

   c. While Hovering

   d. **After Delay (2500ms)** ✓

**4\.** Apa perbedaan utama antara prototipe *Lo-Fi* dan *Hi-Fi*?

   a. Lo-Fi menggunakan Figma, Hi-Fi menggunakan Photoshop.

   b. Lo-Fi lebih mahal untuk dibuat.

   c. **Lo-Fi fokus pada alur dasar tanpa detail visual; Hi-Fi menyertakan warna, gambar, dan tipografi final.** ✓

   d. Tidak ada perbedaan, keduanya sama saja.

**5\.** Seorang mahasiswa menggunakan Action "Navigate To" untuk tombol "Kembali" di Halaman Detail. Apa masalah yang mungkin muncul dibandingkan menggunakan Action "Back"?

   a. Tidak ada masalah, keduanya identik.

   b. Navigate To tidak bisa digunakan untuk tombol.

   c. **Riwayat navigasi pengguna tidak terjaga; jika pengguna datang dari halaman yang berbeda, mereka selalu kembali ke halaman yang sama (bukan halaman asal mereka).** ✓

   d. Navigate To selalu lebih cepat dari Back.

**Uraian Singkat**

**6\.** Jelaskan dengan kata-kata Anda sendiri apa yang dimaksud dengan *Triggers, Actions,* dan *Destinations* dalam konteks prototyping Figma. Berikan satu contoh nyata dari proyek Tur Virtual Museum untuk masing-masing konsep!

**7\.** Anda diminta mendesain interaksi untuk tombol "Favorit" (♡) di Halaman Detail Artefak. Saat diklik, ikon hati harus berubah menjadi hati berwarna merah (♥) sebagai tanda sudah difavoritkan. Jelaskan langkah-langkah yang perlu Anda lakukan di Figma untuk mengimplementasikan interaksi ini menggunakan *Variants* dan *Change To* Action!

---

### **I. Kriteria Proyek Mini (Pertemuan 11-12)**

**Judul Proyek:** "Prototipe Interaktif *Hi-Fi*: Tur Virtual Museum Lhokseumawe"

**Deskripsi Tugas:**

Anda ditugaskan untuk merakit semua desain layar dan aset (ikon, tombol, gambar, video) yang telah Anda rancang dan produksi dalam studi kasus "Tur Virtual Museum" menjadi sebuah prototipe interaktif *high-fidelity* di Figma. Prototipe ini harus mensimulasikan alur pengguna utama secara fungsional.

#### **Persyaratan Minimum Proyek:**

1. **Jumlah Layar:** Prototipe harus terdiri dari minimal **5 (lima) *frame* (layar)** yang berbeda dan sudah didesain (bukan *wireframe* abu-abu).
   * *Contoh: 1. Homepage, 2. Galeri/Daftar Artefak, 3. Halaman Detail Artefak (dengan Video), 4. Halaman Kuis, 5. Menu Overlay/Sidebar.*

2. **Integrasi Aset:** Prototipe **wajib** menggunakan aset-aset yang telah diproduksi pada P9 dan P10:
   * Ikon SVG (minimal 3 ikon)
   * Komponen Tombol dengan *Variants* (minimal 1 komponen)
   * Gambar/foto artefak yang teroptimasi (JPEG)
   * Video artefak .mp4

3. **Alur Utama (User Flow):** Harus ada minimal **satu alur pengguna yang lengkap** dan bisa diselesaikan tanpa ada *link* yang mati atau buntu.
   * *Contoh Alur: Homepage → Galeri → Detail Artefak → Play Video → Kembali ke Galeri*

4. **Indikator: Menghubungkan Layar (Navigasi)**
   * Semua tombol yang terlihat di menu navigasi utama (misal: ikon Home, Galeri, Kuis) harus berfungsi dan mengarah ke *frame* yang benar.
   * Tombol "Kembali" di setiap halaman berfungsi.

5. **Indikator: Interaksi Dasar**
   * Prototipe **wajib** memiliki minimal **satu (1) interaksi "Open Overlay"** (misal: menu *sidebar* atau *pop-up* notifikasi) yang bisa dibuka dan ditutup.
   * Prototipe **wajib** menunjukkan minimal **satu (1) interaksi "While Hovering"** (pada komponen tombol P9).
   * Prototipe **wajib** memiliki minimal **satu (1) interaksi video** (Play/Pause Video) untuk aset video dari P10.

6. **Bonus (tidak wajib, namun meningkatkan nilai):**
   * *Splash Screen* dengan transisi otomatis (*After Delay*).
   * Penggunaan *Smart Animate* untuk transisi yang mulus.
   * *Scroll behavior* pada halaman yang panjang.
   * *Fixed* elemen navigasi saat *scroll*.

#### **Pengumpulan:**

* Kumpulkan **satu (1) link prototipe Figma** dalam Mode Presentasi.
* Pastikan pengaturan *sharing* diatur ke **"Anyone with the link can view"**.
* Kirimkan link yang mengarah langsung ke **mode Presentasi (Prototype)** (klik tombol "▶ Play" lalu salin URL dari *address bar* browser).
* Sertakan juga *screenshot* minimal 5 *frame* desain Anda dalam laporan PDF.

#### **Matriks Penilaian Proyek Mini:**

| Kriteria Penilaian | Bobot | Deskripsi Indikator Keberhasilan |
| :---- | :---- | :---- |
| **Kelengkapan Alur Pengguna & Navigasi** | 35% | Minimal 5 layar terhubung; alur utama bisa diselesaikan; semua tombol navigasi berfungsi; tombol "Kembali" berfungsi. Tidak ada *dead link*. |
| **Integrasi Aset (P9 & P10)** | 25% | Ikon SVG, komponen tombol, gambar JPEG, dan video MP4 dari tugas sebelumnya terintegrasi dengan baik dan terlihat di prototipe. |
| **Penerapan Interaksi Dasar** | 40% | Interaksi Overlay (buka+tutup), Hover (pada komponen tombol), dan Video (Play/Pause) berhasil diterapkan dan berfungsi sesuai syarat. |
| **Total** | **100%** | |

---

### **J. Glosarium**

| Istilah | Definisi |
| :---- | :---- |
| **Prototype (Prototipe)** | Model simulatif dari sebuah produk yang digunakan untuk menguji desain sebelum pengembangan penuh. |
| **Fidelity** | Tingkat kemiripan sebuah prototipe dengan produk akhir; Lo-Fi (rendah) hingga Hi-Fi (tinggi). |
| **Trigger** | Aksi pengguna yang memulai sebuah interaksi (On Click, While Hovering, After Delay, dll.). |
| **Action** | Respons sistem terhadap trigger (Navigate To, Open Overlay, Change To, Play Video, dll.). |
| **Destination** | Target dari sebuah aksi; bisa berupa *frame* lain atau *variant* komponen. |
| **Overlay** | Elemen UI yang tampil di atas layar saat ini tanpa berpindah halaman (modal, pop-up, sidebar). |
| **Smart Animate** | Fitur Figma yang menganimasikan perubahan antara dua *frame* secara otomatis berdasarkan persamaan nama *layer*. |
| **Starting Frame** | *Frame* pertama yang dijalankan saat prototipe dibuka di Mode Presentasi. |
| **Connection Noodle** | Garis/kabel visual di Figma Prototype Tab yang menghubungkan dua elemen/frame dalam sebuah interaksi. |
| **Variants** | Variasi dari sebuah komponen Figma (misal: State=Default, State=Hover, State=Pressed). |
| **Usability Testing** | Metode evaluasi desain dengan mengamati pengguna nyata saat mencoba menggunakan prototipe. |
| **Fixed Position** | Properti elemen yang membuatnya tetap pada posisinya di layar meskipun pengguna *scroll*. |
| **Prototype Link** | URL unik yang mengarah langsung ke Mode Presentasi prototipe Figma. |
| **Handoff** | Proses penyerahan aset dan spesifikasi desain dari desainer kepada tim pengembang. |

---

### **K. Referensi**

1. Figma, Inc. (2024). *Prototype interactions and animations*. Figma Help Center. https://help.figma.com/hc/en-us/articles/360040315773
2. Figma, Inc. (2024). *Create component variants*. Figma Help Center. https://help.figma.com/hc/en-us/articles/360056440594
3. Norman, D. A. (2013). *The design of everyday things: Revised and expanded edition*. Basic Books.
4. Brown, T. (2009). *Change by design: How design thinking transforms organizations and inspires innovation*. HarperBusiness.
5. Preece, J., Rogers, Y., & Sharp, H. (2015). *Interaction design: Beyond human-computer interaction* (4th ed.). Wiley.
6. Nielsen, J., & Budiu, R. (2012). *Mobile usability*. New Riders.
7. Krug, S. (2014). *Don't make me think, revisited: A common sense approach to web usability* (3rd ed.). New Riders.
8. Hoekman, R. (2007). *Designing the obvious: A common sense approach to web & mobile application design*. New Riders.
9. Gothelf, J., & Seiden, J. (2013). *Lean UX: Applying lean principles to improve user experience*. O'Reilly Media.
10. Cooper, A., Reimann, R., Cronin, D., & Noessel, C. (2014). *About face: The essentials of interaction design* (4th ed.). Wiley.
