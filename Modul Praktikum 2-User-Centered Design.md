# **Modul Praktikum: Multimedia Digital dan Interaktif**

| Mata Kuliah | Multimedia Digital dan Interaktif |
| :---- | :---- |
| **Program Studi** | D4 Teknologi Rekayasa Multimedia |
| **Institusi** | Politeknik Negeri Lhokseumawe |
| **Topik Praktikum** | P3: Simulasi Proses Desain Berpusat pada Pengguna (UCD) |
| **Waktu** | 3 Jam Praktikum (150 Menit) |

### **A. Tujuan Praktikum**

Setelah menyelesaikan praktikum ini, mahasiswa diharapkan mampu:

1. **Merumuskan** rencana riset pengguna untuk sebuah ide proyek multimedia interaktif.  
2. **Menciptakan** artefak desain seperti Persona dan *User Stories* berdasarkan skenario pengguna.  
3. **Mengembangkan** ide solusi dalam bentuk sketsa alur cerita (*storyboard*) atau *wireframe*.  
4. **Merancang** sebuah skenario pengujian sederhana (*usability testing*) untuk mengevaluasi prototipe.  
5. **Mendokumentasikan** setiap fase dari proses UCD dalam sebuah laporan terstruktur.

### **B. Alat dan Bahan**

1. Komputer/Laptop.  
2. Perangkat lunak untuk membuat laporan (misal: Microsoft Word, Google Docs).  
3. Alat tulis dan kertas untuk sketsa, atau perangkat lunak desain/presentasi (misal: Figma, Canva, PowerPoint) untuk membuat *wireframe* dan persona.

### **C. Dasar Teori**

#### **C.1 Sejarah dan Landasan UCD**

*User-Centered Design* (UCD) adalah pendekatan desain yang menempatkan pengguna akhir (*end user*) sebagai pusat dari setiap keputusan desain sepanjang seluruh proses pengembangan produk. Filosofi ini lahir dari kesadaran bahwa teknologi dan produk yang dirancang tanpa mempertimbangkan kebutuhan, kemampuan, dan konteks penggunanya cenderung gagal—baik secara fungsional maupun komersial.

Istilah *User-Centered Design* pertama kali dipopulerkan oleh Donald Norman, seorang psikolog kognitif dan desainer, dalam bukunya yang berpengaruh *The Design of Everyday Things* (1988). Norman berargumen bahwa desain yang baik harus terasa intuitif—pengguna seharusnya tidak perlu membaca manual untuk memahami cara kerja suatu produk. Prinsip-prinsip seperti *affordance* (petunjuk visual tentang cara menggunakan objek), *feedback* (respons sistem terhadap aksi pengguna), dan *mapping* (hubungan logis antara kontrol dan hasilnya) menjadi fondasi pemikiran UCD.

Secara formal, UCD dikodifikasikan dalam standar internasional **ISO 9241-210:2019** (*Ergonomics of Human-System Interaction — Part 210: Human-centred design for interactive systems*). Standar ini mendefinisikan prinsip-prinsip inti yang harus dipenuhi oleh sebuah proses desain yang berpusat pada manusia (*Human-Centred Design* / HCD):

1. **Desain didasarkan pada pemahaman eksplisit tentang pengguna, tugas, dan lingkungan.** Tidak boleh ada asumsi yang tidak terverifikasi tentang siapa pengguna dan apa yang mereka butuhkan.
2. **Pengguna dilibatkan sepanjang desain dan pengembangan.** Pengguna bukan hanya objek penelitian di awal, tetapi mitra aktif selama proses berlangsung.
3. **Desain digerakkan dan disempurnakan oleh evaluasi yang berpusat pada pengguna.** Pengujian dengan pengguna nyata adalah mekanisme utama untuk memvalidasi dan memperbaiki desain.
4. **Prosesnya bersifat iteratif.** Desain jarang sempurna pada percobaan pertama; siklus desain-evaluasi-perbaikan diulang hingga kebutuhan pengguna terpenuhi.
5. **Desain memperhatikan seluruh pengalaman pengguna (*User Experience* / UX).** Ini mencakup aspek estetika, emosional, dan pragmatis dari interaksi.
6. **Tim desain mencakup keahlian dan perspektif multidisiplin.** Psikolog, desainer grafis, pengembang, dan pakar domain bekerja bersama.

Pentingnya UCD semakin diakui di industri teknologi global. Perusahaan-perusahaan seperti Apple, Google, dan Airbnb dikenal telah menjadikan UCD dan UX sebagai keunggulan kompetitif utama mereka. Di konteks pendidikan dan kebudayaan, seperti studi kasus kita—Tur Virtual Museum—pendekatan UCD memastikan bahwa produk digital yang dihasilkan benar-benar melayani kebutuhan pengunjung, bukan sekadar memamerkan teknologi.

---

#### **C.2 Empat Fase Siklus UCD secara Mendalam**

Praktikum ini adalah penerapan langsung dari empat fase siklus *User-Centered Design* (UCD). Berikut penjelasan mendalam setiap fase:

**Fase 1: Memahami Konteks Pengguna (*Understand the Context of Use*)**

Fase ini adalah fondasi dari seluruh proses. Tujuannya adalah membangun pemahaman yang kaya dan berbasis bukti tentang *siapa* pengguna Anda, *apa* yang ingin mereka capai, dan *bagaimana* serta *di mana* mereka akan menggunakan produk Anda. Tanpa fondasi ini, semua desain hanyalah tebakan.

Aktivitas dalam fase ini meliputi:
- Wawancara pengguna (*user interviews*)
- Observasi kontekstual (*contextual inquiry*)
- Survei dan kuesioner
- Analisis kompetitor (*competitive analysis*)
- Kajian literatur tentang domain pengguna

Output dari fase ini biasanya berupa catatan riset yang kaya, rekaman wawancara, dan data yang siap untuk dianalisis.

**Fase 2: Menentukan Kebutuhan Pengguna (*Specify the User Requirements*)**

Setelah data riset terkumpul, fase ini berfokus pada mensintesis dan mengorganisir temuan tersebut menjadi kebutuhan yang terdefinisi dengan jelas. Kebutuhan pengguna (*user requirements*) berbeda dari kebutuhan fungsional teknis; kebutuhan pengguna dinyatakan dari sudut pandang pengguna dan menjelaskan *apa yang perlu dicapai*, bukan *bagaimana cara teknisnya*.

Artefak yang dihasilkan dalam fase ini:
- **Persona:** Representasi fiktif dari kelompok pengguna target.
- **User Stories:** Deskripsi singkat fitur dari perspektif pengguna.
- **User Journey Map:** Visualisasi perjalanan pengguna dari awal hingga akhir interaksi.
- **Affinity Diagram:** Organisasi visual dari temuan riset berdasarkan tema.

**Fase 3: Merancang Solusi Desain (*Produce Design Solutions*)**

Dengan kebutuhan yang terdefinisi jelas, tim desain mulai menghasilkan solusi. Fase ini bersifat kreatif dan divergen di awal (menghasilkan banyak ide), kemudian konvergen (menyempurnakan dan memilih solusi terbaik). Prosesnya dimulai dari representasi yang kasar dan murah (sketsa tangan) menuju yang semakin terperinci (wireframe digital, prototipe interaktif).

Tingkatan fidelitas dalam desain:
- **Sketsa (*Sketching*):** Gambar tangan bebas yang cepat. Fokus pada eksplorasi ide, bukan keindahan.
- **Wireframe:** Representasi skematis dari tata letak antarmuka. Menunjukkan struktur dan hierarki konten tanpa detail visual.
- **Mockup:** Wireframe dengan tambahan elemen visual (warna, tipografi, gambar).
- **Prototipe Interaktif:** Mockup yang dapat diklik dan mensimulasikan alur interaksi nyata.

**Fase 4: Mengevaluasi Desain (*Evaluate the Design*)**

Fase ini adalah mekanisme kontrol kualitas dari perspektif pengguna. Desain yang telah dibuat diuji dengan pengguna nyata untuk menemukan masalah kegunaan (*usability issues*) sebelum produk benar-benar dikembangkan secara penuh. Menemukan masalah lebih awal jauh lebih murah daripada memperbaikinya setelah produk diluncurkan.

Metode evaluasi umum:
- **Usability Testing:** Pengguna diminta menyelesaikan tugas tertentu sementara observer mengamati dan mencatat kesulitan.
- **Heuristic Evaluation:** Pakar UX mengevaluasi antarmuka berdasarkan prinsip-prinsip kegunaan yang telah terbukti (misal: 10 Heuristik Nielsen).
- **A/B Testing:** Dua versi desain dibandingkan untuk melihat mana yang lebih efektif.
- **Cognitive Walkthrough:** Tim mengevaluasi desain dengan mensimulasikan perspektif pengguna baru.

Setelah evaluasi, temuan diumpankan kembali ke Fase 2 atau 3 untuk iterasi berikutnya. Siklus ini berulang hingga produk memenuhi standar kegunaan yang ditetapkan.

---

#### **C.3 Design Thinking dan Hubungannya dengan UCD**

*Design Thinking* adalah pendekatan pemecahan masalah yang berpusat pada manusia yang sering disebut bersamaan dengan UCD. Meskipun keduanya berbagi filosofi yang sama—menempatkan manusia di pusat—ada perbedaan penting:

| Aspek | UCD | Design Thinking |
|---|---|---|
| **Fokus Utama** | Proses desain produk interaktif | Pemecahan masalah kreatif secara umum |
| **Asal** | Ergonomi & HCI (ISO 9241) | IDEO & Stanford d.school |
| **Standar** | ISO 9241-210 (formal) | Tidak ada standar formal |
| **Fase** | 4 fase iteratif | 5 fase (Empathize, Define, Ideate, Prototype, Test) |
| **Output** | Produk interaktif yang *usable* | Solusi inovatif untuk masalah kompleks |

Dalam praktik, Design Thinking sering digunakan sebagai *mindset* dan alat brainstorming di awal proyek, sementara UCD memberikan kerangka kerja yang lebih terstruktur untuk proses desain produk secara keseluruhan. Keduanya saling melengkapi.

Fase **Empathize** dalam Design Thinking berkorespondensi dengan Fase 1 UCD. Fase **Define** berkorespondensi dengan Fase 2. Fase **Ideate** dan **Prototype** berkorespondensi dengan Fase 3. Dan fase **Test** berkorespondensi dengan Fase 4.

---

#### **C.4 Metode Riset Pengguna**

Riset pengguna adalah tulang punggung UCD. Tanpa data riset yang valid, seluruh proses desain berdiri di atas asumsi yang rapuh. Berikut adalah metode-metode riset pengguna yang paling umum digunakan:

**a. Wawancara (*User Interviews*)**

Wawancara adalah percakapan terstruktur atau semi-terstruktur antara peneliti dan pengguna. Tujuannya adalah menggali motivasi, kebutuhan, perilaku, dan frustrasi pengguna secara mendalam—hal-hal yang tidak bisa didapat dari survei.

Tips wawancara yang efektif:
- Gunakan pertanyaan terbuka (*open-ended*): "Ceritakan pengalaman Anda saat mengunjungi museum…" bukan "Apakah Anda suka museum?"
- Hindari pertanyaan yang mengarahkan (*leading questions*): Jangan tanya "Apakah fitur ini berguna?"
- Gunakan teknik *5 Whys*: Terus tanyakan "Mengapa?" untuk menggali motivasi yang lebih dalam.
- Rekam sesi (dengan izin) agar tidak ada informasi yang terlewat.
- Wawancarai minimal 5-8 pengguna untuk menemukan pola yang signifikan.

**b. Survei dan Kuesioner (*Surveys*)**

Survei cocok untuk mengumpulkan data kuantitatif dari banyak pengguna secara efisien. Berguna untuk memvalidasi temuan wawancara pada skala yang lebih besar.

Tips membuat survei yang baik:
- Jaga agar survei singkat (idealnya bisa diselesaikan dalam 5-7 menit).
- Gunakan skala Likert (1-5 atau 1-7) untuk mengukur sikap.
- Awali dengan pertanyaan yang mudah untuk membangun keterlibatan responden.
- Hindari pertanyaan ganda (*double-barreled questions*): "Apakah aplikasi ini mudah digunakan dan menyenangkan?" → Pisahkan menjadi dua pertanyaan.

**c. Observasi Kontekstual (*Contextual Inquiry*)**

Peneliti mengamati dan kadang berpartisipasi dalam aktivitas pengguna di lingkungan alami mereka (di rumah, di sekolah, di tempat kerja). Metode ini mengungkap perilaku aktual yang sering berbeda dari apa yang pengguna *katakan* mereka lakukan.

**d. Diary Studies**

Pengguna diminta untuk mendokumentasikan pengalaman, pikiran, dan perilaku mereka secara mandiri selama periode waktu tertentu (beberapa hari hingga beberapa minggu). Berguna untuk memahami perilaku yang terjadi dalam jangka panjang atau dalam konteks yang sulit diobservasi langsung.

---

#### **C.5 Membuat Persona yang Efektif**

Persona adalah karakter fiktif yang mewakili sekelompok pengguna nyata dengan karakteristik, tujuan, dan perilaku yang serupa. Persona bukan karakter yang diinventarisasi; persona adalah sintesis dari data riset nyata.

**Mengapa Persona Penting?**
- Memberikan "wajah" pada data riset yang abstrak.
- Membantu tim desain berempati dengan pengguna.
- Menjadi referensi keputusan desain: "Apakah fitur ini akan berguna untuk Budi?"
- Mencegah tim merancang untuk diri mereka sendiri (*self-referential design*).

**Template Persona Standar:**

```
╔══════════════════════════════════════════════════════════════╗
║  [FOTO/AVATAR]    NAMA FIKSI: Budi Santoso                  ║
║                   "Saya ingin belajar sejarah dengan cara    ║
║                    yang tidak membosankan."                  ║
╠══════════════════════════════════════════════════════════════╣
║ DEMOGRAFI                  │ PSIKOGRAFI                     ║
║ Usia: 16 tahun             │ Kepribadian: Penasaran,        ║
║ Pekerjaan: Pelajar SMA     │ mudah bosan dengan teks        ║
║ Lokasi: Lhokseumawe        │ panjang, visual learner        ║
║ Perangkat: Smartphone      │                                ║
╠══════════════════════════════════════════════════════════════╣
║ GOALS (TUJUAN)             │ FRUSTRATIONS (FRUSTRASI)       ║
║ • Memahami sejarah lokal   │ • Buku teks terlalu kering     ║
║   Lhokseumawe dengan cara  │ • Museum konvensional          ║
║   yang menarik             │   membosankan                  ║
║ • Mendapat nilai bagus     │ • Sulit memvisualisasikan      ║
║   untuk tugas sejarah      │   peristiwa sejarah            ║
╠══════════════════════════════════════════════════════════════╣
║ SCENARIO PENGGUNAAN                                          ║
║ Budi mendapat tugas dari guru sejarahnya untuk mencari      ║
║ informasi tentang artefak bersejarah Lhokseumawe. Ia        ║
║ membuka laptop di rumah dan mengakses tur virtual museum.   ║
╚══════════════════════════════════════════════════════════════╝
```

**Tips Membuat Persona:**
- Dasarkan pada data riset nyata, bukan imajinasi.
- Buat 2-4 persona untuk satu proyek (terlalu banyak justru membingungkan).
- Tambahkan kutipan (*quote*) yang mencerminkan sikap pengguna.
- Sertakan konteks penggunaan (*usage context*) yang spesifik.
- Perbarui persona jika ada data riset baru.

---

#### **C.6 User Stories, Epics, dan User Journey Maps**

**User Stories**

*User Story* adalah deskripsi singkat tentang fitur atau fungsionalitas dari perspektif pengguna. Format standarnya adalah:

> **"Sebagai seorang [peran pengguna], saya ingin [aksi/fitur], agar saya bisa [tujuan/manfaat]."**

Contoh untuk studi kasus Museum Virtual:
- "Sebagai seorang **pelajar SMA**, saya ingin **melihat rekonstruksi 3D artefak**, agar saya bisa **memahami bentuk dan ukurannya secara lebih nyata**."
- "Sebagai seorang **turis**, saya ingin **mendengarkan narasi audio dalam Bahasa Indonesia dan Inggris**, agar saya bisa **menikmati tur tanpa harus membaca banyak teks**."
- "Sebagai seorang **guru**, saya ingin **berbagi tautan tur ke kelas saya**, agar **murid-murid saya bisa belajar mandiri di rumah**."

**Epics**

*Epic* adalah kumpulan *User Stories* yang berkaitan dan bersama-sama membentuk sebuah fungsi besar. Jika *User Story* adalah langkah kecil, *Epic* adalah tujuan besar.

Contoh:
- **Epic: Navigasi Tur** → Berisi user stories tentang memilih ruangan, bergerak 360 derajat, melihat peta museum.
- **Epic: Interaksi Artefak** → Berisi user stories tentang mengklik artefak, melihat detail, mendengar audio, menonton video.
- **Epic: Kuis Interaktif** → Berisi user stories tentang memulai kuis, menjawab pertanyaan, melihat skor.

**User Journey Map**

*User Journey Map* adalah visualisasi yang menceritakan perjalanan pengguna saat berinteraksi dengan produk, dari titik kontak pertama hingga terakhir. Peta ini menangkap tidak hanya *apa yang dilakukan* pengguna, tetapi juga *apa yang dipikirkan dan dirasakan* mereka di setiap tahap.

Komponen utama User Journey Map:
1. **Persona:** Siapa pengguna yang melakukan perjalanan ini?
2. **Skenario:** Apa tujuan utama yang ingin dicapai?
3. **Tahapan (*Stages/Phases*):** Apa saja langkah-langkah utama dalam perjalanan? (misal: Menemukan → Mendaftar → Menjelajah → Berinteraksi → Selesai)
4. **Aksi (*Actions*):** Apa yang dilakukan pengguna di setiap tahap?
5. **Pikiran (*Thoughts*):** Apa yang dipikirkan pengguna? (bisa berupa kutipan)
6. **Emosi (*Emotions*):** Bagaimana perasaan pengguna? (visualisasikan dengan kurva emosi)
7. **Titik Sakit (*Pain Points*):** Di mana pengguna merasa frustasi atau bingung?
8. **Peluang (*Opportunities*):** Bagaimana desain bisa memperbaiki pengalaman di titik-titik sakit tersebut?

---

#### **C.7 Affinity Mapping dan Teknik Sintesis**

Setelah melakukan riset pengguna, Anda akan memiliki tumpukan data mentah: catatan wawancara, hasil survei, rekaman observasi. Tantangannya adalah mengubah data mentah ini menjadi *insight* (pemahaman bermakna) yang bisa menginformasikan desain.

*Affinity Mapping* (atau *Affinity Diagram*) adalah teknik untuk mengorganisir dan mengelompokkan data kualitatif berdasarkan tema atau hubungannya.

**Cara membuat Affinity Map:**
1. Tuliskan setiap temuan, kutipan, atau observasi pada satu kartu/sticky note terpisah.
2. Tempel semua kartu di dinding atau papan digital.
3. Secara berkelompok, pindahkan kartu-kartu yang berkaitan secara tematis ke kelompok yang sama (tanpa banyak diskusi di awal—biarkan pola muncul secara organik).
4. Beri nama/label untuk setiap kelompok tema.
5. Identifikasi pola dan insight utama dari setiap kelompok.

Tools digital untuk Affinity Mapping: **Miro, FigJam, MURAL, Lucidspark**.

**Teknik Sintesis Lainnya:**
- **"How Might We" (HMW) Questions:** Mengubah masalah/pain point menjadi peluang desain. Contoh: Pain point "Pengguna bingung menavigasi museum" → HMW: "Bagaimana kita bisa membuat navigasi museum virtual semudah menggunakan Google Maps?"
- **Insight Statement:** Pernyataan ringkas yang menangkap temuan kunci riset. Format: "[Pengguna] membutuhkan [kebutuhan], karena [insight/alasan yang ditemukan dari riset]."

---

#### **C.8 Proses Double Diamond**

*Double Diamond* adalah model proses desain yang dikembangkan oleh *Design Council* (UK) pada tahun 2005. Model ini menggambarkan proses desain sebagai dua berlian (*diamond*) yang menunjukkan pergerakan antara pemikiran divergen (memperluas kemungkinan) dan konvergen (mempersempit pilihan).

```
         DIVERGEN           KONVERGEN   DIVERGEN           KONVERGEN
        ____________         _________  ____________         _________
       /            \       /         \/            \       /         \
AWAL  /   Discover   \     / Define    \   Develop   \     /  Deliver  \ AKHIR
     /   (Riset &     \___/ (Sintesis & \  (Ideasi &  \___/ (Prototipe & \
    /    Eksplorasi)       Definisi      \  Desain)         Pengujian)    \
```

**Berlian Pertama: Menemukan Masalah yang Tepat**
- *Discover (Temukan):* Memperluas pemahaman tentang konteks dan pengguna melalui riset. Terbuka terhadap semua kemungkinan dan perspektif.
- *Define (Definisikan):* Menyempurnakan dan memilih masalah yang paling penting untuk diselesaikan berdasarkan temuan riset.

**Berlian Kedua: Menemukan Solusi yang Tepat**
- *Develop (Kembangkan):* Mengeksplorasi berbagai solusi mungkin melalui ideasi, prototipe awal, dan pengujian.
- *Deliver (Sampaikan):* Menyempurnakan dan meluncurkan solusi terbaik.

Model Double Diamond sangat berguna karena secara eksplisit mengingatkan desainer bahwa ada dua masalah yang harus dipecahkan: (1) menemukan masalah yang tepat (*right problem*), dan (2) menemukan solusi yang tepat (*right solution*). Banyak proyek gagal karena tim terburu-buru menyelesaikan masalah yang *salah*.

---

### **D. Langkah-langkah Praktikum**

**Studi Kasus Proyek:** "Tur Virtual Interaktif Museum Sejarah Lokal Lhokseumawe"

**Skenario:** Anda adalah bagian dari tim yang ditugaskan untuk merancang pengalaman tur museum virtual. Pengguna harus bisa menjelajahi ruangan museum secara 360 derajat, berinteraksi dengan artefak untuk mendapatkan informasi (teks, audio, video), dan mengikuti kuis interaktif di akhir tur.

**Konteks Studi Kasus:** Museum Sejarah Lokal Lhokseumawe menyimpan koleksi artefak penting yang mencerminkan sejarah Aceh Utara, mulai dari masa Kerajaan Samudera Pasai, masa penjajahan Belanda, hingga era kemerdekaan. Namun, kunjungan fisik ke museum terbatas oleh jarak, waktu, dan aksesibilitas. Proyek Tur Virtual ini bertujuan menjangkau lebih banyak orang—terutama pelajar dan generasi muda—melalui teknologi digital interaktif.

---

#### **Kegiatan 1: Perencanaan Riset dan Definisi Kebutuhan (Fase 1 & 2 — 60 Menit)**

**Tujuan Kegiatan:** Mensimulasikan Fase 1 (Memahami Konteks Pengguna) dan Fase 2 (Menentukan Kebutuhan Pengguna) dari siklus UCD.

**Langkah 1.1 — Identifikasi dan Segmentasi Pengguna (±15 Menit)**

Sebelum merancang produk apapun, kita harus tahu *untuk siapa* produk ini dibuat. Produk yang sama bisa melayani berbagai kelompok pengguna dengan kebutuhan yang sangat berbeda.

* Identifikasi dan tuliskan **dua kelompok target pengguna (audiens)** yang paling potensial untuk Tur Virtual Museum ini. Gunakan tabel berikut sebagai panduan:

| Aspek | Kelompok Pengguna 1 | Kelompok Pengguna 2 |
|---|---|---|
| Nama Kelompok | (Contoh: Pelajar SMP/SMA) | (Contoh: Turis & Pemerhati Budaya) |
| Rentang Usia | | |
| Motivasi Utama | | |
| Tingkat Keakraban Teknologi | | |
| Perangkat yang Digunakan | | |

* **Pilih SATU** kelompok audiens sebagai fokus utama untuk sisa praktikum ini. Tuliskan alasan pemilihan Anda (minimal 2 kalimat): mengapa kelompok ini paling penting untuk dilayani?

> **💡 Tips:** Pilih kelompok yang paling Anda pahami atau yang memiliki kebutuhan paling mendesak. Untuk studi kasus ini, *Pelajar SMA* adalah pilihan yang baik karena mereka adalah pengguna teknologi yang aktif namun mungkin kurang tertarik dengan museum konvensional.

**Langkah 1.2 — Perencanaan Riset Pengguna (±10 Menit)**

Setelah menentukan audiens target, langkah selanjutnya adalah merencanakan bagaimana kita akan mempelajari mereka. Dalam proyek nyata, Anda akan benar-benar melakukan wawancara ini; dalam praktikum ini, kita merancang pertanyaannya.

* Tuliskan **5 pertanyaan wawancara** yang akan Anda ajukan kepada audiens pilihan Anda. Pastikan:
  * Minimal 3 pertanyaan bersifat *open-ended* (terbuka, tidak bisa dijawab ya/tidak).
  * Pertanyaan menggali pengalaman, motivasi, dan frustrasi—bukan sekadar preferensi fitur.
  * Hindari pertanyaan yang mengarahkan (*leading questions*).

Contoh pertanyaan yang BAIK vs BURUK:
  * ❌ BURUK: "Apakah Anda suka fitur kuis di museum virtual?"
  * ✅ BAIK: "Ceritakan pengalaman Anda terakhir kali belajar tentang sejarah lokal. Apa yang paling Anda ingat dari pengalaman itu?"

**Langkah 1.3 — Membuat Persona (±20 Menit)**

Berdasarkan audiens yang Anda pilih, buatlah **satu Persona** yang detail. Gunakan template berikut:

```
NAMA PERSONA: ___________________________
FOTO/AVATAR: (tempel gambar atau gambar tangan)
KUTIPAN KHAS: "____________________________________________"

DEMOGRAFI:
• Usia: ___    • Pekerjaan/Status: ___    • Lokasi: ___
• Perangkat Utama: ___    • Tingkat Literasi Digital: ___

GOALS (TUJUAN):
1. ___________________________________________________
2. ___________________________________________________
3. ___________________________________________________

FRUSTRATIONS (FRUSTRASI/TITIK SAKIT):
1. ___________________________________________________
2. ___________________________________________________
3. ___________________________________________________

SKENARIO PENGGUNAAN:
[Tuliskan paragraf singkat (3-5 kalimat) yang menggambarkan
bagaimana dan kapan persona ini akan menggunakan Tur Virtual Museum]

KEBUTUHAN UTAMA DARI PRODUK:
___________________________________________________
```

> **💡 Tips Persona:** Beri nama yang terasa nyata (misal: "Rizky Maulana" bukan "User A"). Persona yang terasa seperti orang sungguhan lebih efektif membantu tim desain berempati. Pastikan setiap elemen persona dapat Anda jelaskan dengan logika: mengapa persona ini memiliki frustrasi tertentu?

**Langkah 1.4 — Menulis User Stories (±15 Menit)**

Berdasarkan Persona yang Anda buat, tuliskan **lima (5) *User Stories***. Gunakan format standar:

> "Sebagai seorang **[nama/peran Persona]**, saya ingin **[melakukan aksi/mendapat fitur tertentu]**, agar saya bisa **[mencapai tujuan tertentu]**."

Setelah menulis semua User Stories, tandai mana yang menurut Anda paling penting (*high priority*) dan mana yang bisa dikerjakan belakangan (*low priority*). Gunakan simbol: ⭐ untuk prioritas tinggi, dan ○ untuk prioritas rendah.

Contoh output Langkah 1.4:

| # | User Story | Prioritas |
|---|---|---|
| 1 | Sebagai **Rizky (pelajar SMA)**, saya ingin **dapat mengklik artefak dan langsung melihat penjelasannya**, agar saya bisa **belajar tanpa harus membaca buku teks yang tebal**. | ⭐ Tinggi |
| 2 | Sebagai **Rizky**, saya ingin **mengerjakan kuis di akhir tur**, agar saya bisa **menguji pemahaman saya dan mendapat nilai untuk tugas sekolah**. | ⭐ Tinggi |
| 3 | Sebagai **Rizky**, saya ingin **bisa berbagi tautan tur ke teman-teman sekelas**, agar kami bisa **belajar bersama dari jarak jauh**. | ○ Rendah |

---

#### **Kegiatan 2: Desain Solusi dan Perencanaan Evaluasi (Fase 3 & 4 — 60 Menit)**

**Tujuan Kegiatan:** Mensimulasikan Fase 3 (Merancang Solusi Desain) dan Fase 4 (Mengevaluasi Desain) dari siklus UCD.

**Langkah 2.1 — Ideasi dan Pemilihan User Story (±10 Menit)**

* Dari daftar *User Stories* yang Anda buat di Kegiatan 1, pilih **satu User Story berprioritas tinggi** yang akan menjadi fokus desain Anda.
* Tuliskan 3-5 ide awal (*brainstorm*) tentang bagaimana fitur ini bisa diwujudkan. Tidak perlu detail—cukup ide-ide kasar. Contoh: "Popup informasi saat klik artefak", "Panel samping yang muncul dari kanan", "Halaman baru yang terbuka penuh".
* Pilih satu ide yang paling menjanjikan dan jelaskan alasan pemilihan Anda.

**Langkah 2.2 — Membuat Wireframe atau Storyboard (±35 Menit)**

Wujudkan ide yang Anda pilih dalam bentuk visual. Anda bebas memilih:

**Pilihan A — Wireframe (Direkomendasikan untuk fitur antarmuka):**
* Gambarkan **minimal 3 layar/tampilan** yang membentuk alur fitur tersebut.
* Contoh alur untuk User Story "melihat detail artefak": (1) Layar Utama Tur 360° → (2) Layar setelah mengklik artefak (panel detail muncul) → (3) Layar tampilan penuh informasi artefak dengan audio.
* Untuk setiap layar, beri label pada elemen-elemen penting: tombol navigasi, area konten, ikon, dll.
* Tambahkan panah atau anotasi yang menunjukkan alur interaksi antar layar.

**Pilihan B — Storyboard (Direkomendasikan untuk alur pengalaman pengguna):**
* Gambarkan **4-6 panel** yang menceritakan perjalanan Persona Anda dari awal hingga selesai menggunakan fitur tersebut.
* Setiap panel harus berisi: (a) gambar situasi, (b) deskripsi singkat apa yang terjadi, (c) pikiran atau perasaan Persona.
* Sertakan konteks di luar layar: di mana Persona berada? Apa situasinya?

> **💡 Tips:** Fokus pada *alur dan logika*, bukan pada keindahan gambar. Sketsa tangan yang jelas lebih baik daripada desain digital yang indah namun membingungkan. Gunakan persegi panjang untuk mewakili gambar, garis berliku untuk teks, dan lingkaran untuk tombol.

**Langkah 2.3 — Merencanakan Usability Testing (±15 Menit)**

Bayangkan wireframe/storyboard Anda telah menjadi prototipe interaktif yang bisa diklik. Rencanakan sesi *Usability Testing* dengan mengisi dokumen berikut:

**Dokumen Rencana Usability Testing:**

```
JUDUL PENGUJIAN: Usability Testing — Tur Virtual Museum Lhokseumawe
TANGGAL: _______________    DURASI YANG DIRENCANAKAN: ___ menit
JUMLAH PESERTA YANG DIRENCANAKAN: ___ orang

1. TUJUAN PENGUJIAN:
   [Tuliskan apa yang ingin Anda pelajari dari sesi ini.
   Contoh: "Mengetahui apakah pengguna dapat menavigasi tur
   dan menemukan informasi artefak dengan mudah tanpa bantuan."]
   ___________________________________________________

2. PROFIL PESERTA (Kriteria Rekrutmen):
   [Siapa yang seharusnya menjadi peserta pengujian?]
   ___________________________________________________

3. SKENARIO & TUGAS PENGUJIAN:
   Tugas 1: ___________________________________________
   [Berikan konteks dan instruksi yang jelas tanpa menyebutkan
   nama elemen UI spesifik. Contoh: "Bayangkan Anda mendapat
   tugas dari guru untuk mencari informasi tentang 'Keris
   Pasee'. Gunakan aplikasi ini untuk menemukan informasinya."]

   Tugas 2: ___________________________________________

4. METRIK KEBERHASILAN:
   Tugas 1 dianggap berhasil jika: ___________________
   Tugas 2 dianggap berhasil jika: ___________________

5. HAL YANG AKAN DIOBSERVASI:
   • Di mana pengguna tampak bingung atau ragu?
   • Elemen apa yang tidak diklik padahal seharusnya diklik?
   • Komentar spontan apa yang diucapkan pengguna?
```

---

#### **Kegiatan 3: Membuat User Journey Map (Fase 2 Lanjutan — 30 Menit)**

**Tujuan Kegiatan:** Memvisualisasikan pengalaman pengguna secara holistik melalui pembuatan *User Journey Map* untuk Persona yang telah dibuat di Kegiatan 1.

**Langkah 3.1 — Tentukan Skenario Journey (±5 Menit)**

* Gunakan Persona dari Kegiatan 1.
* Tentukan satu skenario lengkap: "Persona [nama] menggunakan Tur Virtual Museum untuk [tujuan tertentu]."
* Contoh: "Rizky menggunakan Tur Virtual Museum Lhokseumawe untuk menyelesaikan tugas sejarah tentang artefak Kerajaan Samudera Pasai."

**Langkah 3.2 — Identifikasi Tahapan Perjalanan (±5 Menit)**

Bagi perjalanan pengguna menjadi 5-6 tahapan utama. Contoh tahapan untuk studi kasus ini:

1. **Menemukan** — Bagaimana Rizky tahu tentang Tur Virtual ini? (Dari guru, media sosial, Google?)
2. **Mengakses** — Rizky membuka tautan dan memuat aplikasi tur.
3. **Orientasi** — Rizky menjelajahi antarmuka untuk pertama kalinya.
4. **Eksplorasi** — Rizky menjelajahi ruangan dan berinteraksi dengan artefak.
5. **Penyelesaian Tugas** — Rizky menemukan informasi yang dibutuhkan dan mengerjakan kuis.
6. **Setelah Penggunaan** — Rizky menutup aplikasi dan menggunakan informasi yang didapat.

**Langkah 3.3 — Isi User Journey Map (±20 Menit)**

Buat tabel User Journey Map menggunakan format berikut (bisa dibuat di kertas besar, spreadsheet, atau Figma/Miro):

| Elemen | Menemukan | Mengakses | Orientasi | Eksplorasi | Penyelesaian Tugas | Setelah Penggunaan |
|---|---|---|---|---|---|---|
| **Aksi** | | | | | | |
| **Pikiran** | | | | | | |
| **Emosi** | 😐 | | | | | |
| **Pain Points** | | | | | | |
| **Peluang Desain** | | | | | | |

**Panduan pengisian:**
* **Aksi:** Apa yang *dilakukan* Persona secara konkret? (verba aktif: mengklik, membaca, mendengarkan, menggulir)
* **Pikiran:** Apa yang *dipikirkan* Persona? (tulis sebagai kutipan, misal: "Di mana tombol untuk kembali?")
* **Emosi:** Gunakan emoji atau skala (+/-) untuk menunjukkan perasaan Persona.
* **Pain Points:** Masalah, hambatan, atau frustrasi yang dialami di tahap ini.
* **Peluang Desain:** Ide bagaimana desain bisa memperbaiki pengalaman di titik sakit ini.

> **💡 Tips:** Kurva emosi yang naik-turun adalah hal yang *wajar* dan bahkan *diharapkan* dalam User Journey Map. Jika kurva emosi selalu datar di atas, berarti Anda tidak jujur dalam mengidentifikasi pain points. Pain points adalah peluang desain yang paling berharga!

### **E. Laporan Praktikum**

Susunlah laporan praktikum Anda dengan format berikut dan kumpulkan dalam bentuk PDF.

1. **Judul Praktikum, Nama, NIM, Kelas.**  
2. **Kegiatan 1: Perencanaan & Kebutuhan Pengguna**  
   * Tabel deskripsi dua target audiens dan alasan pemilihan kelompok fokus.  
   * 5 Pertanyaan wawancara yang telah dibuat.  
   * Visual atau deskripsi Persona yang Anda buat (gunakan template yang diberikan).  
   * Tabel 5 *User Stories* beserta prioritasnya.  
3. **Kegiatan 2: Desain & Evaluasi**  
   * Gambar/foto sketsa *wireframe* atau *storyboard* Anda (minimal 3 layar/panel). Beri penjelasan singkat untuk setiap layar/panel.  
   * Dokumen Rencana *Usability Testing* yang telah diisi lengkap (Tujuan, Profil Peserta, Skenario & Tugas, Metrik Keberhasilan, Hal yang Diobservasi).  
4. **Kegiatan 3: User Journey Map**  
   * Tabel User Journey Map yang telah diisi lengkap untuk semua tahapan.  
   * Identifikasi minimal 3 *Pain Points* utama dan *Peluang Desain* yang diusulkan.  
5. **Kesimpulan:** Rangkum dalam 3-5 kalimat: (a) apa yang Anda pelajari dari proses UCD ini, (b) apa tantangan terbesar yang Anda hadapi, dan (c) bagaimana proses ini mengubah cara Anda berpikir tentang desain produk digital.

---

### **F. Pertanyaan Refleksi**

Jawab pertanyaan-pertanyaan refleksi berikut secara individu setelah menyelesaikan semua kegiatan praktikum. Jawaban tidak harus panjang, tetapi harus menunjukkan pemikiran kritis Anda. Sertakan jawaban ini di bagian akhir laporan praktikum Anda.

1. **Tentang Empati:** Ketika Anda membuat Persona, seberapa mudah atau sulit untuk "masuk ke dalam kepala" pengguna yang berbeda dari diri Anda sendiri? Apa yang membuat proses ini menantang?

2. **Tentang Riset vs. Asumsi:** Dalam praktikum ini, Anda membuat Persona berdasarkan skenario yang diberikan (bukan riset nyata). Bagaimana menurut Anda hasilnya akan berbeda jika Anda benar-benar mewawancarai 5 pelajar SMA sebelum membuat Persona? Apa risiko merancang berdasarkan asumsi?

3. **Tentang Prioritas:** Anda diminta memprioritaskan *User Stories*. Apa kriteria yang Anda gunakan untuk menentukan mana yang paling penting? Apakah ada konflik antara apa yang "diinginkan" pengguna vs. apa yang "mudah dibangun" secara teknis?

4. **Tentang Iterasi:** UCD menekankan bahwa proses ini bersifat iteratif. Setelah menyelesaikan Kegiatan 2 dan 3, adakah hal dalam Persona atau *User Stories* Anda (dari Kegiatan 1) yang ingin Anda ubah atau perbaiki? Mengapa?

5. **Tentang User Journey Map:** Pada tahap mana dalam *User Journey Map* Anda menemukan *pain point* yang paling kritis? Mengapa tahap itu penting dan apa peluang desain yang Anda usulkan?

6. **Tentang Usability Testing:** Mengapa penting untuk memberikan tugas yang spesifik dan tidak menyebutkan nama elemen UI dalam sesi *Usability Testing*? Apa yang bisa terjadi jika Anda memberikan instruksi seperti: "Klik tombol 'Detail Artefak' untuk melihat informasi"?

7. **Tentang Double Diamond:** Dalam kerangka Double Diamond, di fase manakah Anda menghabiskan waktu paling banyak dalam praktikum ini? Menurut Anda, apakah ada fase yang kurang mendapat perhatian? Apa dampaknya?

8. **Tentang Stakeholder vs. Pengguna:** Bayangkan pihak museum (sebagai klien/stakeholder) meminta fitur yang menurut riset Anda tidak dibutuhkan atau bahkan mengganggu pengguna. Bagaimana Anda akan menghadapi situasi ini sebagai seorang desainer UX?

9. **Tentang Inklusivitas:** Apakah Persona yang Anda buat mewakili keberagaman pengguna yang mungkin menggunakan Tur Virtual Museum ini? Kelompok pengguna apa yang mungkin terabaikan (misal: lansia, penyandang disabilitas, pengguna koneksi internet lambat)? Apa implikasinya terhadap desain?

10. **Tentang Nilai UCD:** Setelah menjalani simulasi proses UCD ini, apakah Anda percaya bahwa investasi waktu dan sumber daya untuk melakukan riset pengguna yang mendalam (wawancara, observasi, dll.) sepadan hasilnya? Berikan argumen Anda dengan contoh konkret dari pengalaman praktikum ini.

---

### **G. Rubrik Penilaian**

Laporan praktikum Anda akan dinilai berdasarkan rubrik berikut. Total nilai: **100 poin**.

#### **G.1 Kegiatan 1 — Riset dan Definisi Kebutuhan (30 Poin)**

| Komponen | Kriteria Sangat Baik (90-100%) | Kriteria Baik (70-89%) | Kriteria Cukup (50-69%) | Kriteria Kurang (<50%) | Bobot |
|---|---|---|---|---|---|
| **Identifikasi Audiens** | Dua kelompok audiens didefinisikan dengan sangat jelas, spesifik, dan disertai alasan pemilihan yang logis dan mendalam. | Dua kelompok audiens terdefinisi dengan baik dan alasan pemilihan cukup jelas. | Dua kelompok audiens disebutkan namun kurang spesifik; alasan pemilihan dangkal. | Hanya satu kelompok atau kelompok tidak relevan dengan studi kasus. | 5 Poin |
| **Pertanyaan Wawancara** | Lima pertanyaan, semuanya *open-ended*, tidak mengarahkan, dan menggali motivasi/frustrasi secara mendalam dan relevan. | Minimal 4 pertanyaan *open-ended* yang relevan. | Campuran pertanyaan terbuka dan tertutup; beberapa masih mengarahkan. | Pertanyaan bersifat tertutup (ya/tidak) atau tidak relevan. | 5 Poin |
| **Persona** | Persona sangat detail, realistis, memiliki semua elemen (nama, foto/avatar, demografi, goals, frustrations, skenario, kutipan), dan terasa seperti orang nyata berdasarkan riset. | Persona memiliki semua elemen utama dan terasa cukup realistis. | Persona ada namun beberapa elemen penting hilang atau terlalu dangkal/generik. | Persona sangat minim atau tidak ada. | 12 Poin |
| **User Stories** | Lima *User Stories* dengan format yang benar, bervariasi (mencakup berbagai aspek produk), diprioritaskan dengan logika yang jelas. | Minimal 4 *User Stories* dengan format benar dan prioritas yang masuk akal. | Minimal 3 *User Stories* namun ada yang formatnya salah atau prioritas tidak logis. | Kurang dari 3 *User Stories* atau format salah semua. | 8 Poin |

#### **G.2 Kegiatan 2 — Desain dan Evaluasi (35 Poin)**

| Komponen | Kriteria Sangat Baik (90-100%) | Kriteria Baik (70-89%) | Kriteria Cukup (50-69%) | Kriteria Kurang (<50%) | Bobot |
|---|---|---|---|---|---|
| **Wireframe/Storyboard** | Minimal 3 layar/panel, semua elemen penting diberi label, alur interaksi jelas dengan anotasi/panah, terhubung langsung dengan *User Story* yang dipilih. | Minimal 3 layar/panel dengan elemen berlabel, alur cukup jelas. | 2 layar/panel atau elemen tidak berlabel, alur membingungkan. | 1 layar/panel atau tidak relevan dengan *User Story*. | 20 Poin |
| **Rencana Usability Testing** | Semua elemen rencana diisi lengkap dan berkualitas tinggi: tujuan spesifik dan terukur, tugas realistis tanpa nama elemen UI, metrik keberhasilan jelas dan terukur. | Semua elemen diisi, kualitas baik dengan sedikit kekurangan. | Sebagian elemen diisi atau kualitas sangat bervariasi. | Lebih dari dua elemen tidak diisi atau rencana tidak realistis. | 15 Poin |

#### **G.3 Kegiatan 3 — User Journey Map (20 Poin)**

| Komponen | Kriteria Sangat Baik (90-100%) | Kriteria Baik (70-89%) | Kriteria Cukup (50-69%) | Kriteria Kurang (<50%) | Bobot |
|---|---|---|---|---|---|
| **Kelengkapan Journey Map** | Semua baris (Aksi, Pikiran, Emosi, Pain Points, Peluang) diisi untuk semua tahapan dengan detail yang kaya dan spesifik. | Hampir semua sel terisi dengan kualitas yang baik. | Sebagian besar terisi namun banyak sel yang kosong atau terlalu generik. | Kurang dari setengah tabel terisi. | 12 Poin |
| **Kualitas Insight** | Pain points spesifik dan realistis; Peluang Desain kreatif, inovatif, dan langsung menjawab pain points yang diidentifikasi. | Pain points dan peluang cukup spesifik dan relevan. | Pain points ada namun dangkal; Peluang Desain terlalu generik. | Pain points atau Peluang Desain tidak ada atau tidak relevan. | 8 Poin |

#### **G.4 Kualitas Laporan dan Refleksi (15 Poin)**

| Komponen | Bobot | Deskripsi |
|---|---|---|
| **Struktur & Format Laporan** | 5 Poin | Laporan mengikuti format yang diminta, rapi, mudah dibaca, dan diserahkan sebagai PDF. |
| **Kualitas Jawaban Refleksi** | 10 Poin | Jawaban menunjukkan pemikiran kritis yang mendalam, tidak sekadar mengulang teori, dan didukung dengan contoh dari pengalaman praktikum. |

---

### **H. Glosarium**

Berikut adalah daftar istilah penting yang digunakan dalam modul ini beserta penjelasannya:

| No. | Istilah | Definisi |
|---|---|---|
| 1 | **User-Centered Design (UCD)** | Pendekatan desain yang menempatkan kebutuhan, kemampuan, dan konteks pengguna akhir sebagai pusat dari setiap keputusan desain sepanjang seluruh proses pengembangan. |
| 2 | **Persona** | Representasi fiktif namun berbasis data dari sekelompok pengguna nyata yang memiliki karakteristik, tujuan, dan perilaku serupa. Digunakan untuk membantu tim desain berempati dengan pengguna target. |
| 3 | **User Story** | Deskripsi singkat tentang fitur atau fungsionalitas dari sudut pandang pengguna, menggunakan format: "Sebagai [peran], saya ingin [aksi], agar [tujuan]." |
| 4 | **Epic** | Kumpulan *User Stories* yang berkaitan dan bersama-sama membentuk sebuah fungsi atau modul besar dalam produk. |
| 5 | **User Journey Map** | Diagram visual yang memetakan langkah-langkah, pikiran, emosi, dan *pain points* yang dialami pengguna saat berinteraksi dengan sebuah produk atau layanan dari awal hingga akhir. |
| 6 | **Wireframe** | Representasi visual skematis dari tata letak antarmuka pengguna (*UI layout*) yang menunjukkan struktur, hierarki konten, dan fungsionalitas tanpa detail visual seperti warna atau tipografi akhir. |
| 7 | **Storyboard** | Serangkaian gambar berurutan (seperti komik) yang mengilustrasikan bagaimana seorang pengguna berinteraksi dengan produk dalam konteks skenario tertentu. |
| 8 | **Usability Testing** | Metode evaluasi desain di mana pengguna representatif diminta menyelesaikan tugas-tugas spesifik menggunakan produk (atau prototipenya) sementara peneliti mengobservasi dan mencatat kesulitan yang dialami. |
| 9 | **Prototipe** | Versi awal atau simulasi dari sebuah produk yang digunakan untuk menguji konsep dan ide desain. Tingkatan fidelitas bervariasi dari sketsa kasar (*low-fidelity*) hingga antarmuka interaktif digital (*high-fidelity*). |
| 10 | **Affinity Mapping** | Teknik kolaboratif untuk mengorganisir dan mengelompokkan data kualitatif yang berjumlah besar (misalnya hasil wawancara) ke dalam kelompok-kelompok berdasarkan tema atau kesamaan, untuk menemukan pola dan *insight*. |
| 11 | **Pain Point** | Masalah, hambatan, frustrasi, atau ketidaknyamanan spesifik yang dialami pengguna saat berinteraksi dengan sebuah produk, layanan, atau sistem. |
| 12 | **Design Thinking** | Pendekatan pemecahan masalah yang berpusat pada manusia, terdiri dari lima fase: Empathize (Berempati), Define (Mendefinisikan), Ideate (Menghasilkan Ide), Prototype (Membuat Prototipe), dan Test (Menguji). |
| 13 | **Double Diamond** | Model proses desain dari Design Council UK yang menggambarkan proses kreatif sebagai dua fase divergen-konvergen: (1) menemukan masalah yang tepat, dan (2) menemukan solusi yang tepat. |
| 14 | **ISO 9241-210** | Standar internasional (*International Organization for Standardization*) yang mendefinisikan prinsip-prinsip dan persyaratan untuk proses desain yang berpusat pada manusia (*Human-Centred Design*) untuk sistem interaktif. |
| 15 | **Affordance** | Properti atau karakteristik sebuah objek (fisik maupun digital) yang secara intuitif memberikan petunjuk kepada pengguna tentang bagaimana objek tersebut seharusnya digunakan. Contoh: tombol yang timbul (*raised*) memberikan *affordance* untuk diklik. |
| 16 | **Usability** | Tingkat di mana sebuah produk dapat digunakan oleh pengguna tertentu untuk mencapai tujuan tertentu dengan efektif (*effectiveness*), efisien (*efficiency*), dan kepuasan (*satisfaction*) dalam konteks penggunaan tertentu (ISO 9241-11). |
| 17 | **Contextual Inquiry** | Metode riset pengguna di mana peneliti mengamati dan mewawancarai pengguna di lingkungan alami mereka (tempat mereka biasanya menggunakan produk) untuk memahami konteks penggunaan secara nyata. |
| 18 | **Fidelity (Wireframe)** | Tingkat detail dan realisme sebuah representasi desain. *Low-fidelity* (Lo-Fi) berarti kasar dan sederhana (sketsa tangan); *high-fidelity* (Hi-Fi) berarti sangat detail dan mendekati produk final. |
| 19 | **Iterasi** | Proses pengulangan siklus desain-evaluasi-perbaikan yang dilakukan beberapa kali hingga desain memenuhi standar kualitas yang ditetapkan. Merupakan inti dari pendekatan UCD. |
| 20 | **"How Might We" (HMW)** | Teknik framing pertanyaan yang mengubah *pain point* atau tantangan menjadi peluang desain yang positif dan dapat ditindaklanjuti. Contoh: "Bagaimana kita bisa membuat navigasi museum virtual semudah membaca peta?" |

---

### **I. Referensi**

Berikut adalah sumber-sumber akademis dan profesional yang menjadi landasan teori modul ini. Mahasiswa dianjurkan untuk membaca sumber-sumber ini untuk memperdalam pemahaman.

1. Norman, D. A. (2013). *The Design of Everyday Things: Revised and Expanded Edition*. Basic Books.

2. ISO. (2019). *ISO 9241-210:2019 Ergonomics of human-system interaction — Part 210: Human-centred design for interactive systems*. International Organization for Standardization.

3. Nielsen, J., & Budiu, R. (2012). *Mobile Usability*. New Riders Press.

4. Courage, C., & Baxter, K. (2005). *Understanding Your Users: A Practical Guide to User Requirements Methods, Tools, and Techniques*. Morgan Kaufmann Publishers.

5. Cooper, A., Reimann, R., Cronin, D., & Noessel, C. (2014). *About Face: The Essentials of Interaction Design* (4th ed.). Wiley.

6. Design Council. (2005). *A Study of the Design Process: The Double Diamond*. Design Council UK. Diakses dari https://www.designcouncil.org.uk/

7. Brown, T. (2009). *Change by Design: How Design Thinking Transforms Organizations and Inspires Innovation*. Harper Business.

8. Goodman, E., Kuniavsky, M., & Moed, A. (2012). *Observing the User Experience: A Practitioner's Guide to User Research* (2nd ed.). Morgan Kaufmann.

9. Pruitt, J., & Adlin, T. (2006). *The Persona Lifecycle: Keeping People in Mind Throughout Product Design*. Morgan Kaufmann Publishers.

10. Rosenfeld, L., Morville, P., & Arango, J. (2015). *Information Architecture: For the Web and Beyond* (4th ed.). O'Reilly Media.

11. Krug, S. (2014). *Don't Make Me Think, Revisited: A Common Sense Approach to Web Usability* (3rd ed.). New Riders.

12. Patton, J. (2014). *User Story Mapping: Discover the Whole Story, Build the Right Product*. O'Reilly Media.

13. Kalbach, J. (2016). *Mapping Experiences: A Complete Guide to Creating Value through Journeys, Blueprints, and Diagrams*. O'Reilly Media.

14. Gothelf, J., & Seiden, J. (2021). *Lean UX: Designing Great Products with Agile Teams* (3rd ed.). O'Reilly Media.

15. Lazar, J., Feng, J. H., & Hochheiser, H. (2017). *Research Methods in Human-Computer Interaction* (2nd ed.). Morgan Kaufmann.