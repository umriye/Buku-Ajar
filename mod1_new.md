# **Modul Praktikum: Multimedia Interaktif**

| Mata Kuliah | Multimedia Interaktif |
| :---- | :---- |
| **Program Studi** | D4 Teknologi Rekayasa Multimedia |
| **Institusi** | Politeknik Negeri Lhokseumawe |
| **Topik Praktikum** | P2: Analisis Prinsip Desain Interaksi (IxD) dan *User Experience* (UX) |
| **Waktu** | 3 Jam Praktikum (150 Menit) |

### **A. Tujuan Praktikum**

Setelah menyelesaikan praktikum ini, mahasiswa diharapkan mampu:

1. **Menerapkan** prinsip-prinsip Desain Interaksi (IxD) untuk menganalisis alur fitur pada sebuah produk digital.  
2. **Menggunakan** kerangka kerja *UX Honeycomb* untuk mengevaluasi pengalaman pengguna sebuah aplikasi.  
3. **Mendekonstruksi** pengalaman pengguna yang buruk dan mengidentifikasi akar masalahnya.  
4. **Menghasilkan** ide solusi kreatif dalam bentuk sketsa antarmuka (*low-fidelity wireframe*) untuk memperbaiki masalah UX yang ditemukan.

### **B. Alat dan Bahan**

1. Komputer/Laptop dengan koneksi internet.  
2. *Smartphone* dengan beberapa aplikasi terpasang (contoh: Gojek, Grab, Tokopedia, Instagram, dll.).  
3. Perangkat lunak untuk membuat laporan (misal: Microsoft Word, Google Docs).  
4. Alat tulis dan kertas (untuk sketsa), atau perangkat lunak desain sederhana (misal: Figma, Canva, PowerPoint).

### **C. Dasar Teori**

Praktikum ini didasarkan pada materi perkuliahan mengenai Desain Interaksi dan *User Experience*. Bagian ini menyajikan teori secara lebih mendalam agar mahasiswa memiliki landasan konseptual yang kuat sebelum melakukan analisis pada kegiatan praktikum.

---

#### **C.1 Sejarah Singkat Desain Interaksi (IxD) dan User Experience (UX)**

Bidang Desain Interaksi (IxD) dan *User Experience* (UX) tidak muncul secara tiba-tiba, melainkan merupakan hasil evolusi panjang dari berbagai disiplin ilmu.

**Era Awal: Ergonomi dan Human Factors (1940-an–1970-an)**
Akar IxD dan UX dapat ditelusuri dari bidang *ergonomi* dan *human factors* yang berkembang pesat selama Perang Dunia II. Para insinyur militer menyadari bahwa alat-alat perang yang canggih sekalipun gagal dioperasikan secara efektif jika tidak dirancang sesuai kemampuan kognitif dan fisik manusia. Pengamatan ini melahirkan prinsip dasar bahwa desain harus menyesuaikan diri dengan manusia, bukan sebaliknya.

**Era Komputer Personal (1970-an–1990-an)**
Ketika komputer personal mulai memasuki rumah tangga dan kantor pada era 1970-an hingga 1980-an, muncul kebutuhan baru: antarmuka yang dapat dipahami oleh orang awam, bukan hanya programer. Xerox PARC memperkenalkan *Graphical User Interface* (GUI) yang kemudian dipopulerkan oleh Apple Macintosh pada 1984. Pada periode inilah bidang *Human-Computer Interaction* (HCI) lahir sebagai disiplin akademik formal. Don Norman bergabung dengan Apple pada 1993 dan menjabat sebagai *User Experience Architect*—dan inilah pertama kalinya istilah "User Experience" secara resmi digunakan dalam konteks industri.

**Kelahiran Istilah "User Experience" (1990-an)**
Don Norman sendiri menjelaskan bahwa ia sengaja memilih istilah "user experience" karena ia ingin mencakup semua aspek interaksi manusia dengan sistem—termasuk aspek industri, grafis, antarmuka, interaksi fisik, dan panduan. Buku Norman yang berpengaruh, *The Design of Everyday Things* (pertama kali diterbitkan tahun 1988 dengan judul *The Psychology of Everyday Things*), menjadi kitab suci bagi para desainer hingga hari ini.

**Era Web dan Mobile (2000-an–Sekarang)**
Ledakan internet di awal 2000-an dan kemudian revolusi smartphone pada 2007 (peluncuran iPhone pertama) secara dramatis memperluas cakupan IxD dan UX. Aplikasi mobile menjadi kanal interaksi utama bagi miliaran orang di seluruh dunia, termasuk di Indonesia. Perusahaan-perusahaan teknologi besar seperti Google, Facebook, dan Apple berinvestasi besar-besaran dalam penelitian UX karena mereka menyadari bahwa pengalaman pengguna yang superior adalah keunggulan kompetitif yang nyata.

**IxD dan UX di Indonesia**
Di Indonesia, kesadaran akan pentingnya IxD dan UX mulai tumbuh seiring dengan berkembangnya ekosistem *startup* digital pada pertengahan 2010-an. Perusahaan seperti Gojek (didirikan 2010), Tokopedia (didirikan 2009), dan Traveloka (didirikan 2012) menjadi pelopor dalam menerapkan praktik UX yang matang untuk memenangkan persaingan di pasar yang kompetitif. Kini, profesi *UX Designer* dan *UX Researcher* menjadi salah satu profesi yang paling dicari di industri teknologi Indonesia.

---

#### **C.2 Hubungan Antara Desain Interaksi (IxD) dan User Experience (UX)**

Seringkali mahasiswa bingung dengan perbedaan antara IxD dan UX karena kedua istilah ini sering digunakan secara bergantian. Namun, keduanya memiliki fokus yang berbeda meskipun saling berkaitan erat.

**Desain Interaksi (Interaction Design / IxD)** adalah disiplin yang berfokus pada **perancangan perilaku** produk digital: bagaimana sebuah sistem merespons tindakan pengguna, bagaimana alur antar layar dirancang, dan bagaimana antarmuka berkomunikasi dengan pengguna secara dua arah. IxD berurusan dengan *micro-interactions* (misalnya: animasi tombol saat ditekan), *gestures* (misalnya: geser ke kiri untuk menghapus), dan *transitions* (misalnya: animasi perpindahan antar halaman). IxD adalah **bagaimana** sesuatu bekerja.

**User Experience (UX)** adalah disiplin yang lebih luas dan berfokus pada **keseluruhan persepsi dan perasaan** seseorang saat, sebelum, dan setelah berinteraksi dengan sebuah produk atau layanan. UX mencakup riset pengguna, arsitektur informasi, desain visual, konten, dan bahkan aspek layanan pelanggan. UX adalah **apa yang dirasakan** pengguna.

Analogi yang mudah dipahami: Jika sebuah aplikasi adalah sebuah restoran, maka **IxD** adalah tata cara pelayanan (bagaimana pelayan mendekati meja, cara memesan makanan, cara pembayaran), sementara **UX** adalah keseluruhan pengalaman makan (rasa makanan, suasana restoran, kecepatan pelayanan, harga, lokasi, dan kenangan yang terbawa pulang).

**Diagram Hubungan IxD dan UX:**

```
┌─────────────────────────────────────────────┐
│               USER EXPERIENCE (UX)          │
│                                             │
│   ┌─────────────┐   ┌─────────────────────┐ │
│   │   Riset     │   │  Desain Interaksi   │ │
│   │  Pengguna   │   │       (IxD)         │ │
│   └─────────────┘   └─────────────────────┘ │
│   ┌─────────────┐   ┌─────────────────────┐ │
│   │  Arsitektur │   │   Desain Visual     │ │
│   │  Informasi  │   │       (UI)          │ │
│   └─────────────┘   └─────────────────────┘ │
└─────────────────────────────────────────────┘
```

Dengan demikian, IxD adalah **sub-disiplin** dari UX yang berfokus khusus pada aspek interaksi. Seorang UX Designer yang baik harus memiliki kemampuan IxD yang kuat, tetapi kemampuan IxD saja tidak cukup untuk menghasilkan produk dengan UX yang sempurna.

---

#### **C.3 Prinsip Desain Interaksi (IxD) oleh Don Norman — Penjelasan Mendalam**

Don Norman, melalui bukunya *The Design of Everyday Things*, merumuskan enam prinsip fundamental dalam desain interaksi. Berikut adalah penjelasan mendalam dari masing-masing prinsip beserta contoh nyata dari aplikasi-aplikasi yang familiar bagi pengguna Indonesia.

**1. Visibility (Visibilitas)**

*Visibilitas* berarti bahwa semua fungsi penting harus terlihat oleh pengguna. Pengguna tidak seharusnya harus "menebak" apakah sebuah fitur ada atau tidak.

- **Definisi Teknis:** Elemen-elemen UI yang relevan dengan tugas pengguna saat ini harus terlihat jelas tanpa perlu pengguna mencarinya.
- **Contoh Baik (Gojek):** Pada halaman utama Gojek, semua layanan utama (GoRide, GoCar, GoFood, GoSend) ditampilkan sebagai ikon yang jelas dan langsung terlihat tanpa scroll. Pengguna baru sekalipun dapat langsung memahami apa yang bisa dilakukan.
- **Contoh Buruk:** Pada beberapa antarmuka website pemerintah Indonesia, tombol "Submit" atau "Kirim" kadang tersembunyi di bagian bawah halaman yang sangat panjang, memaksa pengguna untuk scroll jauh ke bawah.
- **Implikasi Desain:** Gunakan hierarki visual yang jelas. Elemen yang paling sering digunakan harus paling mudah ditemukan. Hindari "hamburger menu" berlebihan yang menyembunyikan fungsi-fungsi penting.

**2. Feedback (Umpan Balik)**

*Feedback* berarti bahwa sistem harus selalu memberikan respons yang jelas kepada pengguna setelah mereka melakukan suatu tindakan, sehingga pengguna tahu bahwa sistem menerima dan memproses tindakan tersebut.

- **Definisi Teknis:** Setiap aksi pengguna harus menghasilkan reaksi yang dapat dirasakan (visual, audio, atau haptik) dalam waktu yang wajar.
- **Contoh Baik (Shopee):** Saat pengguna menambahkan item ke keranjang belanja, Shopee menampilkan animasi kecil di mana item "terbang" ke ikon keranjang, disertai angka yang berubah pada badge keranjang. Ini adalah multi-layer feedback: visual (animasi), perubahan state (angka badge).
- **Contoh Baik (Tokopedia):** Setelah pembayaran berhasil, Tokopedia menampilkan halaman konfirmasi dengan animasi centang hijau yang memuaskan, disertai notifikasi suara, dan bahkan notifikasi push ke ponsel.
- **Contoh Buruk:** Website SIAKAD di banyak perguruan tinggi sering tidak memberikan feedback yang jelas saat data berhasil disimpan. Pengguna harus menyegarkan halaman secara manual untuk memverifikasi apakah tindakan mereka berhasil.
- **Jenis-jenis Feedback:** (a) *Visual feedback* – perubahan warna tombol, loading spinner; (b) *Audio feedback* – suara notifikasi, *ding* saat berhasil; (c) *Haptic feedback* – getaran pada smartphone; (d) *Textual feedback* – pesan "Berhasil disimpan!" atau pesan error.

**3. Affordance (Keterjangkauan)**

*Affordance* mengacu pada properti fisik atau visual sebuah elemen yang secara intuitif mengisyaratkan kepada pengguna bagaimana cara menggunakannya, tanpa perlu instruksi eksplisit.

- **Definisi Teknis:** Elemen UI harus terlihat seperti apa yang bisa dilakukan dengan elemen tersebut. Tombol harus terlihat bisa diklik, bilah geser harus terlihat bisa digeser.
- **Contoh Baik (Traveloka):** Kotak input pencarian destinasi pada Traveloka memiliki bayangan, sudut membulat, dan ikon pencarian—semua isyarat visual ini secara kolektif mengomunikasikan "ini adalah tempat untuk mengetik tujuan Anda."
- **Contoh Buruk:** Beberapa aplikasi modern menggunakan desain terlalu "flat" sehingga elemen yang dapat diklik tidak berbeda secara visual dari elemen yang tidak dapat diklik. Pengguna menjadi bingung tentang apa yang interaktif.
- **False Affordance:** Ini adalah kebalikannya—sebuah elemen terlihat seperti bisa diklik/diinteraksikan, tetapi sebenarnya tidak. Ini sangat membingungkan pengguna.
- **Perceived vs. Real Affordance:** Norman membedakan antara *real affordance* (kemampuan fisik objek) dan *perceived affordance* (apa yang pengguna percaya bisa mereka lakukan). Dalam desain digital, *perceived affordance* adalah yang terpenting.

**4. Mapping (Pemetaan)**

*Mapping* adalah hubungan antara kontrol (misalnya: tombol, gestur) dan efek yang ditimbulkannya pada sistem. Mapping yang baik adalah mapping yang "natural" dan sesuai dengan ekspektasi pengguna.

- **Definisi Teknis:** Tata letak dan perilaku kontrol harus mencerminkan hubungan logis dengan elemen yang dikontrolnya.
- **Contoh Baik (Maps/Navigasi):** Pada Google Maps atau aplikasi navigasi Waze, menggeser peta ke kanan berarti melihat area yang berada di sebelah kiri—ini adalah *natural mapping* karena sesuai dengan metafora fisik menggeser selembar peta kertas.
- **Contoh di Aplikasi Musik:** Tombol volume yang memiliki ikon speaker kecil (volume rendah) di bawah dan speaker besar (volume keras) di atas secara intuitif menunjukkan hubungan antara posisi tombol dan level suara.
- **Contoh Buruk:** Kompor dengan pengaturan tungku yang tidak berkorespondensi secara jelas dengan burner mana yang dikendalikan adalah contoh *poor mapping* yang klasik dari Don Norman sendiri.
- **Natural Mapping:** Desain yang memanfaatkan analogi dunia fisik—seperti menggunakan gestur "mencubit" (pinch) untuk memperkecil, karena sesuai dengan intuisi fisik—adalah contoh *natural mapping* yang baik.

**5. Constraints (Batasan)**

*Constraints* adalah pembatasan yang disengaja dalam desain untuk mencegah pengguna melakukan kesalahan, atau untuk membimbing pengguna ke jalur yang benar.

- **Definisi Teknis:** Membatasi jenis-jenis interaksi yang mungkin dilakukan pengguna pada titik tertentu dalam alur, untuk mencegah error dan menyederhanakan pengambilan keputusan.
- **Contoh Baik (Shopee/Tokopedia Checkout):** Tombol "Bayar Sekarang" di halaman *checkout* hanya aktif (berwarna cerah dan dapat diklik) setelah pengguna memilih metode pembayaran. Sebelum itu, tombol dalam keadaan *disabled* (abu-abu). Ini adalah *physical constraint* — pengguna secara fisik tidak dapat melanjutkan tanpa memenuhi prasyarat.
- **Contoh Baik (Formulir):** Kolom input nomor telepon yang hanya menerima angka adalah contoh *constraint* yang membantu pengguna menghindari kesalahan input.
- **Jenis Constraints:** (a) *Physical constraint* – tombol tidak dapat diklik sebelum kondisi terpenuhi; (b) *Logical constraint* – urutan langkah yang harus diikuti; (c) *Cultural constraint* – konvensi desain yang sudah dipahami secara budaya (misalnya: warna merah untuk bahaya/error); (d) *Semantic constraint* – berdasarkan makna situasi (misal: pilih tanggal check-out setelah check-in).

**6. Consistency (Konsistensi)**

*Konsistensi* berarti bahwa elemen-elemen desain yang serupa harus berperilaku dengan cara yang sama di seluruh bagian aplikasi. Ketika desain konsisten, pengguna dapat mentransfer pengetahuan dari satu bagian aplikasi ke bagian lainnya.

- **Definisi Teknis:** Keseragaman visual, perilaku, dan terminologi di seluruh antarmuka produk.
- **Contoh Baik (Gojek):** Di seluruh ekosistem layanan Gojek, warna hijau selalu digunakan untuk tindakan utama (CTA), dan ikon keranjang belanja selalu berada di pojok kanan atas. Pengguna yang terbiasa dengan GoFood dapat dengan mudah beradaptasi saat menggunakan GoMart karena konsistensi pola desainnya.
- **Jenis Konsistensi:** (a) *Internal consistency* – konsisten dalam satu produk; (b) *External consistency* – konsisten dengan standar platform (misalnya: mengikuti *Material Design* di Android atau *Human Interface Guidelines* di iOS).
- **Contoh Buruk:** Aplikasi yang menggunakan kata "Hapus" di satu tempat dan "Buang" di tempat lain untuk fungsi yang sama menciptakan kebingungan. Begitu pula jika warna merah digunakan untuk tombol "Konfirmasi" di satu layar tetapi untuk "Batalkan" di layar lain.

---

#### **C.4 UX Honeycomb oleh Peter Morville — Penjelasan Mendalam**

Peter Morville, seorang pionir dalam arsitektur informasi, merumuskan *UX Honeycomb* pada tahun 2004 sebagai model untuk memahami kompleksitas pengalaman pengguna. Model ini terdiri dari tujuh facet yang saling terhubung, digambarkan seperti sarang lebah (*honeycomb*).

**1. Useful (Berguna)**
Produk harus memenuhi kebutuhan nyata pengguna. Pertanyaan kuncinya: "Apakah produk ini menyelesaikan masalah yang nyata?"

- *Contoh:* Fitur "Bayar di Alfamart/Indomaret" pada Shopee sangat **useful** bagi jutaan pengguna Indonesia yang belum memiliki rekening bank atau kartu kredit. Fitur ini menjawab kebutuhan nyata yang spesifik pada konteks Indonesia.

**2. Usable (Dapat Digunakan)**
Produk harus mudah digunakan. Pengguna harus dapat mencapai tujuan mereka dengan efisien dan efektif. Ini berkaitan langsung dengan prinsip-prinsip IxD.

- *Contoh:* Gojek secara konsisten mendapatkan nilai *usability* yang tinggi karena proses pemesanan yang streamlined—dari buka aplikasi hingga driver berangkat, hanya membutuhkan beberapa tap.

**3. Findable (Dapat Ditemukan)**
Pengguna harus dapat menavigasi dan menemukan konten atau fitur yang mereka cari dengan mudah. Ini mencakup navigasi yang intuitif, fungsi pencarian yang baik, dan arsitektur informasi yang logis.

- *Contoh:* Fitur pencarian Tokopedia menggunakan *autocomplete* dan menampilkan saran pencarian populer, membantu pengguna menemukan produk yang mereka inginkan bahkan jika mereka tidak tahu nama persis produknya. Kategori produk juga terorganisir secara logis.

**4. Credible (Dapat Dipercaya)**
Pengguna harus dapat mempercayai produk dan organisasi di baliknya. Ini mencakup keamanan data, transparansi, dan profesionalisme visual.

- *Contoh:* Tokopedia dan Shopee membangun kredibilitas melalui sistem ulasan dan rating yang transparan, *badge* "Official Store" untuk brand resmi, garansi uang kembali yang jelas, dan enkripsi pembayaran. Logo sertifikasi keamanan dan informasi yang lengkap tentang penjual meningkatkan kepercayaan pembeli.

**5. Desirable (Diinginkan)**
Produk harus menarik secara emosional dan estetis. Desain visual, merek, dan tone of voice harus menciptakan keterikatan emosional positif.

- *Contoh:* Animasi-animasi halus di Gojek, maskot dan ilustrasi ceria di berbagai aplikasi, penggunaan warna yang konsisten dan menarik—semua ini berkontribusi pada *desirability*. Pengguna tidak hanya menggunakan aplikasi karena *fungsinya*, tetapi karena mereka *menyukainya*.

**6. Accessible (Dapat Diakses)**
Produk harus dapat digunakan oleh semua orang, termasuk penyandang disabilitas dan pengguna dengan keterbatasan teknologi.

- *Contoh:* Fitur pembaca layar (*screen reader*) untuk pengguna tunanetra, pilihan ukuran teks yang dapat diperbesar, kontras warna yang cukup untuk pengguna dengan buta warna, dan antarmuka yang berfungsi baik pada koneksi internet lambat (penting di Indonesia dengan variasi kualitas sinyal yang besar).

**7. Valuable (Bernilai)**
Pada akhirnya, produk harus memberikan nilai, baik bagi pengguna maupun bagi bisnis. Produk yang baik secara UX tetapi tidak menghasilkan nilai bisnis (misal: tidak menghasilkan pendapatan, tidak meningkatkan loyalitas) tidak akan bertahan lama.

- *Contoh:* GoTo Group (induk Gojek dan Tokopedia) mengukur *value* tidak hanya dari jumlah pengguna aktif, tetapi dari *Gross Transaction Value* (GTV) dan tingkat retensi pengguna—semuanya adalah indikator bahwa platform memberikan nilai nyata bagi ekosistem.

**Interaksi Antar Facet Honeycomb:**
Ketujuh facet ini tidak berdiri sendiri-sendiri. Sebuah aplikasi bisa sangat *useful* tetapi tidak *usable* (fitur ada tapi sulit digunakan). Atau bisa sangat *desirable* tetapi tidak *credible* (tampilan menarik tapi pengguna tidak percaya dengan keamanannya). UX yang ideal mencapai keseimbangan optimal di antara semua facet.

---

#### **C.5 Psikologi Kognitif sebagai Landasan IxD**

Desain Interaksi yang baik tidak mungkin dibangun tanpa memahami cara kerja pikiran manusia. Psikologi kognitif memberikan fondasi ilmiah untuk berbagai keputusan desain.

**Mental Models (Model Mental)**
*Mental model* adalah representasi internal yang dimiliki pengguna tentang bagaimana sebuah sistem bekerja. Pengguna menggunakan mental model untuk membuat prediksi tentang apa yang akan terjadi jika mereka melakukan suatu tindakan.

- *Implikasi Desain:* Desainer harus membuat antarmuka yang sesuai dengan mental model pengguna yang sudah ada, bukan memaksa pengguna mempelajari mental model baru. Inilah mengapa ikon "floppy disk" masih digunakan untuk "simpan" meskipun generasi muda belum pernah melihat floppy disk fisik—ikon itu sudah menjadi bagian dari mental model kolektif.

**Cognitive Load (Beban Kognitif)**
*Cognitive load* adalah jumlah usaha mental yang dibutuhkan untuk memproses informasi. Antarmuka yang baik meminimalkan *cognitive load* yang tidak perlu.

- **Intrinsic load:** Kompleksitas inheren dari tugas itu sendiri.
- **Extraneous load:** Beban tambahan yang diciptakan oleh desain yang buruk (instruksi yang membingungkan, navigasi yang rumit).
- **Germane load:** Usaha mental yang dibutuhkan untuk membangun pemahaman dan keterampilan baru.
- *Implikasi Desain:* Tampilkan hanya informasi yang relevan, gunakan *progressive disclosure* (tampilkan detail hanya saat dibutuhkan), dan ikuti konvensi desain yang sudah familiar.

**Hick's Law**
Waktu yang dibutuhkan untuk membuat keputusan meningkat secara logaritmis seiring bertambahnya jumlah pilihan. Semakin banyak opsi yang disajikan, semakin lama pengguna membutuhkan waktu untuk memilih.

- *Implikasi Desain:* Kurangi jumlah pilihan yang tersedia di satu layar. Jika harus menampilkan banyak pilihan, kelompokan secara logis. Inilah mengapa aplikasi seperti Grab menggunakan tab/kategori untuk mengorganisir layanannya.

**Fitts's Law**
Waktu yang dibutuhkan untuk mencapai target (misalnya: tombol) adalah fungsi dari jarak ke target dan ukuran target. Target yang lebih besar dan lebih dekat lebih mudah dan cepat dijangkau.

- *Implikasi Desain:* Tombol aksi utama harus berukuran besar dan mudah dijangkau jempol (terutama pada desain mobile). Inilah mengapa tombol CTA utama pada aplikasi mobile biasanya besar, ditempatkan di bagian bawah layar (mudah dijangkau jempol), dan berwarna kontras.

**Miller's Law (The Magic Number 7 ± 2)**
Memori kerja manusia hanya dapat memproses sekitar 7 (plus atau minus 2) item dalam satu waktu.

- *Implikasi Desain:* Batasi jumlah item dalam menu navigasi, jangan tampilkan terlalu banyak opsi sekaligus, gunakan *chunking* (pengelompokan) untuk informasi yang kompleks.

---

#### **C.6 Heuristik Nielsen — 10 Prinsip Evaluasi Usability**

Jakob Nielsen, bersama Rolf Molich, merumuskan 10 Heuristik Usability pada tahun 1990 (diperbarui 1994) yang menjadi standar emas dalam evaluasi antarmuka pengguna. *Heuristic Evaluation* adalah metode inspeksi usability di mana evaluator menilai antarmuka berdasarkan prinsip-prinsip (heuristik) yang telah terbukti.

**1. Visibility of System Status**
Sistem harus selalu menginformasikan pengguna tentang apa yang sedang terjadi melalui feedback yang tepat dalam waktu yang wajar.
- *Contoh:* Loading bar pada Tokopedia saat memproses pembayaran, indikator "Mengirim..." pada WhatsApp.

**2. Match Between System and the Real World**
Sistem harus berbicara dalam bahasa pengguna—menggunakan kata-kata, frasa, dan konsep yang familiar bagi pengguna, bukan jargon teknis.
- *Contoh:* Shopee menggunakan istilah "Keranjang" (bukan "Cart" atau "Basket") dan "Wishlist" yang sudah familiar di Indonesia.

**3. User Control and Freedom**
Pengguna sering melakukan tindakan yang tidak disengaja dan membutuhkan "pintu darurat" yang jelas untuk meninggalkan state yang tidak diinginkan tanpa harus melalui proses panjang.
- *Contoh:* Tombol "Batal" yang selalu tersedia selama proses checkout, kemampuan untuk mengedit pesanan sebelum konfirmasi akhir di GoFood.

**4. Consistency and Standards**
Pengguna tidak seharusnya harus bertanya-tanya apakah kata, situasi, atau tindakan yang berbeda berarti hal yang sama.
- *Contoh:* Gojek secara konsisten menggunakan warna dan tipografi yang sama di semua layanannya.

**5. Error Prevention**
Lebih baik desain yang baik mencegah masalah terjadi sejak awal daripada menampilkan pesan error yang baik.
- *Contoh:* Konfirmasi "Apakah Anda yakin ingin membatalkan pesanan?" sebelum aksi permanen dilakukan di Grab.

**6. Recognition Rather Than Recall**
Minimalkan beban memori pengguna dengan membuat objek, tindakan, dan opsi terlihat. Pengguna tidak seharusnya harus mengingat informasi dari satu bagian antarmuka ke bagian lainnya.
- *Contoh:* Riwayat pencarian dan pesanan sebelumnya di Tokopedia membantu pengguna tanpa harus mengingat nama produk yang pernah dibeli.

**7. Flexibility and Efficiency of Use**
Accelerator—yang tidak terlihat oleh pengguna pemula—memungkinkan pengguna ahli untuk mempercepat interaksi. Desain harus melayani keduanya.
- *Contoh:* Fitur "Pesan Lagi" di GoFood memungkinkan pengguna lama untuk memesan ulang dengan satu tap, sementara pengguna baru tetap bisa melalui alur pencarian normal.

**8. Aesthetic and Minimalist Design**
Dialog tidak boleh mengandung informasi yang tidak relevan atau jarang dibutuhkan. Setiap unit informasi tambahan bersaing dengan informasi relevan dan mengurangi visibilitasnya.
- *Contoh:* Halaman pembayaran yang hanya menampilkan informasi esensial (nama item, harga, metode bayar, tombol konfirmasi).

**9. Help Users Recognize, Diagnose, and Recover from Errors**
Pesan error harus diekspresikan dalam bahasa biasa (bukan kode error), menjelaskan masalah secara tepat, dan menyarankan solusi secara konstruktif.
- *Contoh Buruk:* "Error: 404" tanpa penjelasan. *Contoh Baik:* "Ups! Halaman ini tidak ditemukan. Mungkin link sudah kedaluwarsa. Kembali ke Beranda?"

**10. Help and Documentation**
Meskipun lebih baik jika sistem dapat digunakan tanpa dokumentasi, mungkin perlu menyediakan bantuan. Informasi tersebut harus mudah dicari, fokus pada tugas pengguna, dan tidak terlalu panjang.
- *Contoh:* Fitur *Help Center* Shopee yang dapat dicari berdasarkan topik, dengan FAQ yang menjawab pertanyaan umum pengguna.

---

#### **C.7 Prinsip Gestalt dalam Desain UI**

Psikologi Gestalt adalah teori persepsi visual yang menjelaskan bagaimana otak manusia mengorganisir informasi visual menjadi pola yang bermakna. Prinsip-prinsip Gestalt sangat relevan dalam desain antarmuka karena membantu desainer memahami bagaimana pengguna akan mempersepsikan tata letak visual.

**1. Proximity (Kedekatan)**
Elemen-elemen yang berdekatan secara spasial cenderung dipersepsikan sebagai kelompok.
- *Implikasi:* Kelompokkan label form dengan input field-nya, tempatkan tombol "Beli Sekarang" dekat dengan informasi produk. Di Shopee, harga, rating, dan tombol "+" untuk kuantitas dikelompokkan dekat satu sama lain karena semua berkaitan dengan keputusan pembelian.

**2. Similarity (Kesamaan)**
Elemen-elemen yang memiliki tampilan serupa (warna, bentuk, ukuran) cenderung dipersepsikan sebagai bagian dari kelompok yang sama.
- *Implikasi:* Semua tombol aksi utama memiliki warna yang sama, semua link memiliki gaya yang konsisten. Di Gojek, semua layanan transportasi ditampilkan dengan ikon yang memiliki gaya visual serupa untuk menunjukkan bahwa mereka adalah kategori yang sama.

**3. Closure (Penutupan)**
Otak cenderung "melengkapi" bentuk yang tidak sempurna untuk menciptakan objek yang utuh.
- *Implikasi:* Card yang terpotong di tepi layar mengisyaratkan kepada pengguna bahwa ada konten lagi jika mereka menggeser (scroll). Ini adalah teknik desain yang umum digunakan di berbagai aplikasi e-commerce.

**4. Continuity (Kesinambungan)**
Mata cenderung mengikuti garis dan kurva yang mulus, merasakan aliran yang berkelanjutan.
- *Implikasi:* Tata letak kolom yang mengikuti garis vertikal memudahkan pemindaian visual. Desainer menggunakan garis panduan imajiner untuk menyelaraskan elemen UI.

**5. Figure-Ground (Figur-Latar)**
Otak secara otomatis memisahkan elemen visual menjadi subjek utama (figur) dan latar belakang (ground).
- *Implikasi:* Penggunaan overlay gelap di belakang modal/popup untuk memfokuskan perhatian pengguna pada konten modal. Tombol dengan warna berbeda dari latar belakang akan "muncul" sebagai figur yang dapat diklik.

**6. Common Fate (Nasib Bersama)**
Elemen-elemen yang bergerak bersama cenderung dipersepsikan sebagai kelompok.
- *Implikasi:* Animasi di mana beberapa elemen bergerak bersama-sama mengkomunikasikan bahwa elemen-elemen tersebut terkait secara fungsional.

---

#### **C.8 Tren UX dalam Ekosistem Digital Indonesia**

Memahami konteks lokal sangat penting dalam menerapkan prinsip IxD dan UX. Indonesia memiliki karakteristik unik yang membentuk tren dan tantangan desain tersendiri.

**Penetrasi Smartphone dan Fragmentasi Perangkat**
Indonesia adalah salah satu negara dengan penetrasi smartphone tertinggi di Asia Tenggara, namun dengan fragmentasi perangkat yang sangat tinggi. Pengguna menggunakan perangkat dari berbagai kisaran harga, mulai dari flagship hingga entry-level dengan spesifikasi terbatas. Implikasinya: desainer UX Indonesia harus memastikan aplikasi berfungsi baik di perangkat berspesifikasi rendah, dengan memori terbatas dan layar kecil.

**Ekosistem Super-App GoTo**
Setelah merger Gojek dan Tokopedia membentuk GoTo Group, Indonesia menjadi salah satu negara pionir dalam adopsi *super-app*—satu aplikasi yang mengintegrasikan berbagai layanan (transportasi, pengiriman makanan, e-commerce, pembayaran digital, layanan keuangan). Tren ini menciptakan tantangan UX yang unik: bagaimana merancang navigasi yang jelas dan tidak membingungkan ketika satu aplikasi menawarkan puluhan layanan berbeda.

**Dominasi Pembayaran Digital dan GoPay/OVO/DANA**
Meningkatnya adopsi dompet digital seperti GoPay, OVO, DANA, dan ShopeePay telah mengubah cara pengguna Indonesia berinteraksi dengan sistem pembayaran. UX pembayaran yang mulus—dengan metode seperti QR Code, transfer antar-dompet, dan integrasi dengan perbankan—menjadi faktor diferensiasi kompetitif yang kritis.

**Konektivitas yang Beragam**
Kualitas koneksi internet di Indonesia sangat bervariasi. Di kota besar seperti Jakarta, Surabaya, dan Medan, koneksi 4G/5G tersedia luas. Namun di banyak daerah, koneksi masih mengandalkan 3G atau bahkan 2G. Desain UX yang baik untuk pasar Indonesia harus mempertimbangkan *offline capability*, *lazy loading*, dan kompresi aset untuk memastikan pengalaman yang baik bahkan pada koneksi lambat.

**Literasi Digital yang Beragam**
Pengguna digital Indonesia mencakup rentang literasi yang sangat luas—dari generasi muda yang sangat melek teknologi hingga pengguna baru yang baru pertama kali menggunakan smartphone. UX yang inklusif harus dapat mengakomodasi kedua segmen ini, dengan *onboarding* yang jelas untuk pengguna baru dan *shortcut* yang efisien untuk pengguna berpengalaman.

**Tren Dark Mode dan Personalisasi**
Seiring meningkatnya kesadaran tentang kesehatan mata dan konsumsi baterai, *dark mode* menjadi fitur yang semakin banyak diminta pengguna Indonesia. Aplikasi-aplikasi lokal seperti Gojek dan platform streaming seperti Vidio mulai mengintegrasikan opsi ini.

**Voice Interface dan Bahasa Indonesia**
Dengan semakin canggihnya Natural Language Processing (NLP) untuk Bahasa Indonesia, antarmuka berbasis suara (voice interface) mulai hadir di pasar Indonesia. Google Assistant, Siri, dan asisten virtual lokal kini mendukung Bahasa Indonesia dengan lebih baik, membuka peluang baru dalam desain interaksi berbasis suara.


### **D. Langkah-langkah Praktikum**

Praktikum ini terdiri dari **empat kegiatan utama** yang dirancang secara progresif. Alokasi waktu: Kegiatan 1 (40 menit), Kegiatan 2 (35 menit), Kegiatan 3 (40 menit), Kegiatan 4 (35 menit).

---

#### **Kegiatan 1: Analisis Produk Digital Unggul (40 Menit)**

Pada kegiatan ini, kita akan menganalisis aplikasi yang dianggap memiliki desain yang baik untuk memahami mengapa aplikasi tersebut berhasil dari perspektif IxD dan UX.

**Langkah 1.1 – Pemilihan Aplikasi dan Fitur (5 Menit)**

* Buka salah satu aplikasi berikut di *smartphone* Anda: **Grab, Shopee, Tokopedia, atau Traveloka**.
* Pilih **satu alur fitur spesifik** untuk dianalisis. Contoh:
  * *Alur pemesanan GoRide/GrabBike dari membuka aplikasi hingga mendapatkan driver.*
  * *Alur mencari produk, memasukkan ke keranjang, hingga ke halaman checkout di Tokopedia.*
  * *Alur pencarian dan pemilihan tiket pesawat di Traveloka.*
* Catat nama aplikasi dan nama alur fitur yang dipilih di lembar laporan Anda.

**Langkah 1.2 – Eksplorasi dan Observasi Mendalam (10 Menit)**

* Jalankan alur fitur yang Anda pilih **minimal 3 kali** dengan pendekatan berbeda:
  * **Pertama:** Jalankan seperti pengguna biasa tanpa memikirkan desain.
  * **Kedua:** Jalankan sambil memperhatikan setiap elemen visual dan interaksi—warna, ukuran, posisi tombol, animasi, pesan teks, dan waktu respons.
  * **Ketiga:** Coba lakukan kesalahan yang disengaja (misalnya: coba lanjut tanpa mengisi field wajib) untuk melihat bagaimana sistem menangani error.
* Ambil screenshot dari langkah-langkah kunci untuk dilampirkan di laporan.

**Langkah 1.3 – Analisis Menggunakan Prinsip IxD (15 Menit)**

* Isi tabel analisis berikut secara lengkap. Berikan penjelasan konkret yang merujuk pada elemen spesifik—sebutkan nama tombol, warna, atau interaksi spesifik yang Anda temukan.

| Prinsip IxD | Diterapkan? (Ya/Tidak) | Penjelasan & Contoh Konkret pada Alur Fitur | Skor (1–5) |
| :---- | :---- | :---- | :---- |
| **Visibility** | Ya | *Tombol "Pesan GoRide" terlihat jelas dengan warna hijau di halaman utama.* | 5 |
| **Feedback** | | | |
| **Affordance** | | | |
| **Mapping** | | | |
| **Constraints** | | | |
| **Consistency** | | | |
| **Rata-rata Skor IxD** | | | |

* Skor 1 = Tidak diterapkan sama sekali; 5 = Diterapkan dengan sangat baik.

**Langkah 1.4 – Analisis Menggunakan UX Honeycomb (10 Menit)**

* Lengkapi tabel analisis UX berikut. Beri peringkat 1 (Sangat Buruk) hingga 5 (Sangat Baik) dan jelaskan alasannya secara spesifik.

| Aspek UX | Peringkat (1-5) | Alasan dan Penjelasan Konkret |
| :---- | :---- | :---- |
| **Useful** | 5 | *Sangat bermanfaat karena menyelesaikan masalah transportasi saya dengan cepat.* |
| **Usable** | | |
| **Findable** | | |
| **Credible** | | |
| **Desirable** | | |
| **Accessible** | | |
| **Valuable** | | |
| **Rata-rata Skor UX** | | |

---

#### **Kegiatan 2: Ideasi Ulang Pengalaman Buruk (35 Menit)**

Di sini, Anda akan menjadi seorang *problem solver*. Cari masalah UX di sekitar Anda dan tawarkan ide kreatif untuk menyelesaikannya.

**Langkah 2.1 – Pemilihan Sistem Bermasalah (5 Menit)**

* Identifikasi sebuah aplikasi atau sistem digital yang menurut Anda memiliki pengalaman pengguna yang buruk.
* **Saran:** SIAKAD kampus, aplikasi layanan publik, website pemerintah, antarmuka mesin ATM, atau aplikasi di ponsel Anda yang membingungkan.

**Langkah 2.2 – Identifikasi Masalah (10 Menit)**

* Identifikasi dan dokumentasikan **minimal 3 masalah UX** menggunakan tabel berikut:

| No | Deskripsi Masalah | Prinsip IxD Dilanggar | Aspek UX Terdampak | Tingkat Keparahan (1–5) |
| :---- | :---- | :---- | :---- | :---- |
| 1 | *Setelah klik "Simpan KRS", tidak ada indikator loading atau pesan konfirmasi.* | *Feedback* | *Credible, Usable* | 4 |
| 2 | | | | |
| 3 | | | | |

* Tingkat keparahan: 1 = Kosmetik, 2 = Minor, 3 = Mayor, 4 = Kritis, 5 = Bencana.

**Langkah 2.3 – Brainstorming Solusi (5 Menit)**

* Pilih **satu masalah** yang paling kritis. Tulis minimal 5 ide solusi tanpa menilai kualitasnya, kemudian pilih satu ide terbaik untuk dikembangkan menjadi sketsa.

**Langkah 2.4 – Pembuatan Sketsa / Low-Fidelity Wireframe (15 Menit)**

* Gambarkan ide solusi Anda dalam bentuk sketsa antarmuka sederhana di atas kertas atau software (Figma, Canva, PowerPoint).
* Gunakan kotak untuk mewakili gambar/media, garis horizontal untuk teks, dan label untuk menjelaskan nama elemen.
* Jika lebih dari satu layar, gambarkan berurutan dan hubungkan dengan panah.
* Foto atau scan sketsa untuk dilampirkan dalam laporan.

*Contoh sketsa low-fidelity untuk perbaikan alur.*

---

#### **Kegiatan 3: Evaluasi Heuristik Nielsen (40 Menit)**

Pada kegiatan ini, Anda akan melakukan *Heuristic Evaluation* secara formal menggunakan 10 Heuristik Nielsen pada aplikasi ketiga.

**Langkah 3.1 – Pemilihan Aplikasi (3 Menit)**

* Pilih aplikasi yang **berbeda** dari Kegiatan 1 dan 2. Saran:
  * Streaming lokal: **Vidio, WeTV, RCTI+**
  * Berita: **Detik.com, Kompas.com**
  * Keuangan: **BRImo, BSI Mobile, Jenius**
  * Pemerintah: **SatuSehat, e-Samsat**

**Langkah 3.2 – Eksplorasi Aplikasi (7 Menit)**

* Eksplorasi bebas selama 7 menit. Catat hal-hal yang terasa "janggal" atau "membingungkan".

**Langkah 3.3 – Evaluasi Berdasarkan 10 Heuristik Nielsen (25 Menit)**

* *Severity Rating*: **0** = bukan masalah, **1** = kosmetik, **2** = minor, **3** = major, **4** = bencana usability.

| No | Heuristik Nielsen | Contoh Penerapan Baik | Pelanggaran yang Ditemukan | Severity (0–4) |
| :---- | :---- | :---- | :---- | :---- |
| 1 | Visibility of System Status | | | |
| 2 | Match Between System & Real World | | | |
| 3 | User Control and Freedom | | | |
| 4 | Consistency and Standards | | | |
| 5 | Error Prevention | | | |
| 6 | Recognition Rather Than Recall | | | |
| 7 | Flexibility and Efficiency of Use | | | |
| 8 | Aesthetic and Minimalist Design | | | |
| 9 | Help Users Recognize, Diagnose & Recover from Errors | | | |
| 10 | Help and Documentation | | | |

**Langkah 3.4 – Rangkuman Temuan (5 Menit)**

* Jawab: (1) Berapa total pelanggaran ditemukan? (2) Heuristik mana paling sering dilanggar? (3) Sebutkan 3 masalah terparah beserta rekomendasi perbaikan singkat. (4) Beri penilaian *usability* keseluruhan skala 1–10 beserta alasannya.

---

#### **Kegiatan 4: Analisis Komparatif Dua Aplikasi Kompetitor (35 Menit)**

**Langkah 4.1 – Pemilihan Pasangan Kompetitor (3 Menit)**

* Pilih salah satu pasangan: **Gojek vs. Grab**, **Tokopedia vs. Shopee**, **Traveloka vs. Tiket.com**, **GoPay vs. OVO**, atau **Vidio vs. Mola**.

**Langkah 4.2 – Penentuan Alur Fitur yang Sama (2 Menit)**

* Tentukan satu alur fitur ekuivalen yang akan dibandingkan di kedua aplikasi.

**Langkah 4.3 – Analisis Perbandingan (25 Menit)**

| Dimensi Perbandingan | Aplikasi A: ________ | Aplikasi B: ________ | Pemenang (A/B/Seri) |
| :---- | :---- | :---- | :---- |
| Jumlah langkah untuk menyelesaikan tugas | | | |
| Kejelasan navigasi (Findable) | | | |
| Kecepatan respons / performa | | | |
| Kualitas Feedback pada setiap interaksi | | | |
| Penanganan error | | | |
| Estetika dan daya tarik visual (Desirable) | | | |
| Kemudahan bagi pengguna baru (Onboarding) | | | |
| Fitur unik yang meningkatkan UX | | | |
| Kejelasan informasi harga/biaya | | | |
| Rasa kepercayaan (Credible) | | | |

**Langkah 4.4 – Kesimpulan Komparatif (5 Menit)**

* Tulis kesimpulan dalam paragraf (minimal 150 kata) yang menjawab: Aplikasi mana yang UX-nya lebih baik dan mengapa? Apa keunggulan unik masing-masing? Jika Anda adalah UX Designer di tim yang kalah, satu perubahan paling *impactful* apa yang akan Anda rekomendasikan?

---

### **E. Laporan Praktikum**

Susunlah laporan praktikum dengan format berikut:

1. **Judul Praktikum, Nama, NIM, Kelas.**
2. **Kegiatan 1: Analisis Produk Digital**
   * Nama Aplikasi dan Alur Fitur yang dianalisis.
   * Tabel Analisis Prinsip IxD yang sudah diisi lengkap beserta skor.
   * Tabel Analisis *UX Honeycomb* yang sudah diisi lengkap beserta skor.
   * Screenshot dari langkah-langkah kunci alur yang dianalisis.
3. **Kegiatan 2: Ideasi Ulang Pengalaman Buruk**
   * Nama Sistem/Aplikasi yang dianalisis beserta konteks penggunaan.
   * Tabel identifikasi masalah (minimal 3 masalah) menggunakan terminologi IxD dan UX.
   * Daftar ide brainstorming dan alasan pemilihan ide terbaik.
   * Gambar/Foto Sketsa Solusi Kreatif beserta penjelasan singkat.
4. **Kegiatan 3: Evaluasi Heuristik**
   * Nama aplikasi yang dievaluasi.
   * Tabel evaluasi 10 Heuristik Nielsen yang sudah diisi.
   * Rangkuman temuan dan rekomendasi perbaikan.
5. **Kegiatan 4: Analisis Komparatif**
   * Nama dua aplikasi yang dibandingkan dan alur fitur yang dipilih.
   * Tabel komparatif yang sudah diisi.
   * Paragraf kesimpulan komparatif (minimal 150 kata).
6. **Kesimpulan Akhir:** Rangkum apa yang Anda pelajari dari keseluruhan praktikum ini dalam 3–5 kalimat, hubungkan dengan materi perkuliahan.

---

### **F. Pertanyaan Diskusi**

Jawab pertanyaan-pertanyaan berikut secara individual atau dalam diskusi kelompok. Setiap jawaban minimal 3–5 kalimat.

1. Menurut Anda, prinsip IxD mana yang paling sering diabaikan dalam aplikasi-aplikasi buatan Indonesia? Berikan contoh nyata dan jelaskan dampaknya terhadap pengalaman pengguna.

2. Apakah sebuah aplikasi bisa mendapat nilai tinggi di semua tujuh facet *UX Honeycomb* secara bersamaan? Jelaskan potensi trade-off yang mungkin terjadi antara facet-facet tersebut dengan menggunakan contoh konkret.

3. Bagaimana perbedaan karakteristik pengguna Indonesia (variasi literasi digital, koneksi internet tidak merata, kebiasaan penggunaan ponsel) memengaruhi keputusan desain UX sebuah aplikasi?

4. Dalam konteks *super-app* seperti GoTo (Gojek + Tokopedia), bagaimana tantangan desain interaksi berbeda dibandingkan aplikasi dengan satu fungsi? Prinsip IxD dan heuristik mana yang menjadi paling kritis?

5. Don Norman berpendapat bahwa "desain yang baik adalah desain yang tidak terlihat." Apa maksud pernyataan ini? Apakah Anda setuju? Berikan argumen dengan contoh dari aplikasi yang Anda gunakan sehari-hari.

6. Bandingkan pendekatan *Heuristic Evaluation* (Nielsen) dengan pendekatan *UX Honeycomb* (Morville). Apa kelebihan dan kekurangan masing-masing? Dalam situasi apa Anda akan memilih salah satunya?

7. Prinsip Gestalt *Proximity* menyatakan bahwa elemen yang berdekatan dianggap berhubungan. Identifikasi tiga contoh penerapan prinsip ini dalam aplikasi yang Anda gunakan sehari-hari dan jelaskan mengapa hal itu membuat antarmuka lebih mudah dipahami.

8. Hick's Law menyatakan bahwa lebih banyak pilihan berarti lebih lama waktu pengambilan keputusan. Namun, pengguna juga sering mengeluh jika pilihan terlalu sedikit. Bagaimana seorang desainer UX menyeimbangkan keduanya?

9. *Cognitive load* adalah konsep penting dalam IxD. Identifikasi tiga fitur desain spesifik pada aplikasi yang Anda gunakan yang secara efektif mengurangi *cognitive load* pengguna, dan jelaskan mekanisme kerjanya.

10. Di era AI generatif saat ini, antarmuka berbasis percakapan (*conversational UI*) seperti ChatGPT semakin populer. Bagaimana prinsip-prinsip IxD Don Norman dan heuristik Nielsen masih relevan (atau perlu diadaptasi) untuk jenis antarmuka ini?

11. Seorang UX Designer senior mengatakan: "Data kuantitatif memberi tahu Anda *apa* yang terjadi, tetapi hanya riset kualitatif yang bisa memberi tahu Anda *mengapa* hal itu terjadi." Jelaskan pernyataan ini dalam konteks proses desain UX.

12. Aksesibilitas sering menjadi aspek UX yang diabaikan di Indonesia. Mengapa hal ini terjadi? Apa konsekuensi hukum, etis, dan bisnis dari mengabaikan aksesibilitas?

---

### **G. Rubrik Penilaian**

Laporan praktikum akan dinilai berdasarkan rubrik berikut. Total nilai: **100 poin**.

#### **G.1 Kegiatan 1: Analisis Produk Digital (25 Poin)**

| Kriteria | Sangat Baik (5) | Baik (4) | Cukup (3) | Kurang (2) | Sangat Kurang (1) |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Kelengkapan Tabel IxD** | Semua 6 prinsip diisi dengan penjelasan sangat spesifik dan contoh akurat | 5 prinsip diisi dengan baik | 4 prinsip diisi | 3 atau kurang | Tidak diisi |
| **Kualitas Penjelasan IxD** | Menunjukkan pemahaman mendalam, merujuk elemen UI spesifik | Penjelasan baik dengan beberapa referensi spesifik | Penjelasan cukup tapi generik | Penjelasan sangat dangkal | Tidak ada penjelasan bermakna |
| **Kelengkapan Tabel UX Honeycomb** | Semua 7 aspek diisi dengan skor yang justified | 5–6 aspek diisi | 3–4 aspek diisi | 1–2 aspek | Tidak diisi |
| **Kualitas Analisis UX** | Analisis mendalam, skor sesuai penjelasan, ada insight orisinal | Analisis baik, skor umumnya sesuai | Analisis cukup, beberapa skor tidak dijustifikasi | Analisis sangat dangkal | Tidak ada analisis |
| **Screenshot dan Dokumentasi** | Screenshot relevan dan terlampir untuk semua langkah kunci | Screenshot ada tapi tidak lengkap | Hanya 1–2 screenshot | Screenshot tidak relevan | Tidak ada |

#### **G.2 Kegiatan 2: Ideasi Ulang (25 Poin)**

| Kriteria | Sangat Baik (5) | Baik (4) | Cukup (3) | Kurang (2) | Sangat Kurang (1) |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Identifikasi Masalah** | 3+ masalah dengan terminologi IxD & UX yang tepat | 3 masalah diidentifikasi dengan baik | 2 masalah, terminologi kurang tepat | 1 masalah, deskripsi dangkal | Tidak ada identifikasi bermakna |
| **Penggunaan Terminologi** | Tepat dan konsisten di seluruh laporan | Umumnya tepat | Beberapa terminologi tepat | Terminologi jarang tepat | Tidak menggunakan terminologi |
| **Kreativitas Solusi** | Orisinal, feasible, langsung mengatasi masalah | Solusi baik dan relevan | Cukup tapi kurang orisinal | Generik dan kurang relevan | Tidak ada solusi bermakna |
| **Kualitas Wireframe** | Jelas, berlabel dengan baik, alur dapat dipahami | Cukup jelas | Ada tapi sulit dipahami | Sangat kasar | Tidak ada |
| **Justifikasi Desain** | Menghubungkan solusi dengan masalah secara eksplisit | Penjelasan baik | Penjelasan cukup | Penjelasan sangat singkat | Tidak ada penjelasan |

#### **G.3 Kegiatan 3: Evaluasi Heuristik (25 Poin)**

| Kriteria | Sangat Baik (5) | Baik (4) | Cukup (3) | Kurang (2) | Sangat Kurang (1) |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Kelengkapan Evaluasi** | Semua 10 heuristik diisi dengan contoh konkret | 8–9 heuristik diisi | 6–7 heuristik | 3–5 heuristik | Kurang dari 3 |
| **Ketepatan Identifikasi** | Pelanggaran tepat, *severity rating* justified | Umumnya tepat | Beberapa tepat | Banyak tidak tepat | Tidak teridentifikasi |
| **Kualitas Rekomendasi** | Spesifik, actionable, langsung merespons pelanggaran | Rekomendasi baik | Cukup tapi generik | Sangat umum | Tidak ada |
| **Pemahaman Konsep** | Menunjukkan pemahaman jelas tentang makna setiap heuristik | Pemahaman baik | Pemahaman cukup | Beberapa miskonsepsi | Banyak miskonsepsi |
| **Rangkuman Akhir** | Komprehensif, penilaian justified dengan data | Rangkuman baik | Cukup | Sangat singkat | Tidak ada |

#### **G.4 Kegiatan 4: Analisis Komparatif (25 Poin)**

| Kriteria | Sangat Baik (5) | Baik (4) | Cukup (3) | Kurang (2) | Sangat Kurang (1) |
| :---- | :---- | :---- | :---- | :---- | :---- |
| **Kelengkapan Tabel** | Semua 10 dimensi diisi dengan informasi spesifik | 8–9 dimensi | 6–7 dimensi | 3–5 dimensi | Kurang dari 3 |
| **Objektivitas Analisis** | Objektif, penilaian didukung observasi konkret | Umumnya objektif | Cukup objektif | Banyak penilaian tanpa dasar | Sangat bias |
| **Kedalaman Perbandingan** | Menemukan perbedaan substantif dan non-obvious | Perbedaan yang baik | Beberapa perbedaan | Sangat permukaan | Hampir tidak ada |
| **Kualitas Kesimpulan** | Menjawab semua pertanyaan panduan, 150+ kata, didukung data | Baik, semua pertanyaan terjawab | Sebagian besar terjawab | Satu dua terjawab | Tidak ada kesimpulan |
| **Rekomendasi Perbaikan** | Spesifik, justified, dan feasible | Rekomendasi baik | Cukup | Sangat generik | Tidak ada |

---

### **H. Glosarium**

| No | Istilah | Definisi |
| :---- | :---- | :---- |
| 1 | **Affordance** | Properti visual atau fisik elemen yang mengisyaratkan cara penggunaannya tanpa instruksi eksplisit. Contoh: tombol yang terlihat cembung mengisyaratkan bahwa ia bisa diklik. |
| 2 | **Cognitive Load** | Jumlah usaha mental yang dibutuhkan untuk memproses informasi dalam sebuah antarmuka. Desain yang baik meminimalkan *cognitive load* yang tidak perlu. |
| 3 | **Constraints** | Pembatasan yang disengaja dalam desain untuk mencegah pengguna membuat kesalahan. Contoh: tombol submit yang tidak aktif sampai semua field wajib terisi. |
| 4 | **Desirability** | Aspek UX Honeycomb yang mengacu pada daya tarik emosional dan estetis sebuah produk—seberapa jauh pengguna "menyukai" dan menginginkan produk tersebut. |
| 5 | **Feedback** | Respons yang diberikan sistem kepada pengguna setelah mereka melakukan suatu tindakan, mengkonfirmasi bahwa tindakan tersebut diterima dan diproses. |
| 6 | **Fitts's Law** | Prinsip yang menyatakan bahwa waktu untuk mencapai target adalah fungsi dari jarak dan ukuran target. Target yang lebih besar dan lebih dekat lebih mudah dijangkau. |
| 7 | **Gestalt Principles** | Sekumpulan prinsip psikologi persepsi visual yang menjelaskan bagaimana otak mengorganisir elemen visual menjadi pola bermakna (proximity, similarity, closure, dll.). |
| 8 | **Heuristic Evaluation** | Metode evaluasi usability di mana evaluator menilai antarmuka berdasarkan prinsip-prinsip yang telah terbukti. Dikembangkan oleh Jakob Nielsen. |
| 9 | **Hick's Law** | Prinsip yang menyatakan bahwa waktu pengambilan keputusan meningkat logaritmis seiring bertambahnya jumlah pilihan. |
| 10 | **Interaction Design (IxD)** | Disiplin desain yang berfokus pada perancangan perilaku produk digital: bagaimana sistem merespons tindakan pengguna dan bagaimana alur antar layar dirancang. |
| 11 | **Low-Fidelity Wireframe** | Sketsa kasar antarmuka yang menggambarkan tata letak dan alur secara umum tanpa memperhatikan detail visual. Digunakan di tahap awal desain. |
| 12 | **Mental Model** | Representasi internal yang dimiliki pengguna tentang cara kerja sebuah sistem, digunakan untuk memprediksi apa yang akan terjadi akibat suatu tindakan. |
| 13 | **Mapping** | Hubungan logis antara kontrol (tombol atau gestur) dan efek yang ditimbulkannya. *Natural mapping* menggunakan analogi dunia fisik untuk menciptakan hubungan yang intuitif. |
| 14 | **Severity Rating** | Skala penilaian tingkat keparahan masalah usability dalam *heuristic evaluation*, dari 0 (bukan masalah) hingga 4 (bencana usability yang harus diperbaiki segera). |
| 15 | **Super-App** | Aplikasi yang mengintegrasikan berbagai layanan dalam satu platform. Contoh di Indonesia: GoTo (Gojek + Tokopedia). |
| 16 | **Usability** | Kemudahan dan efisiensi dengan mana pengguna dapat mencapai tujuan mereka saat menggunakan sebuah produk. Merupakan salah satu facet dari *UX Honeycomb*. |
| 17 | **User Experience (UX)** | Keseluruhan persepsi dan perasaan seseorang saat, sebelum, dan setelah berinteraksi dengan sebuah produk atau layanan—mencakup aspek fungsional, emosional, dan estetis. |
| 18 | **UX Honeycomb** | Kerangka kerja yang dikembangkan Peter Morville (2004) yang mendefinisikan tujuh facet kualitas UX: Useful, Usable, Findable, Credible, Desirable, Accessible, dan Valuable. |

---

### **I. Referensi**

1. Norman, D. A. (2013). *The Design of Everyday Things: Revised and Expanded Edition*. Basic Books.

2. Nielsen, J., & Molich, R. (1990). Heuristic evaluation of user interfaces. *Proceedings of the SIGCHI Conference on Human Factors in Computing Systems*, 249–256. https://doi.org/10.1145/97243.97281

3. Morville, P. (2004). *User Experience Design*. Semantic Studios. Diakses dari https://semanticstudios.com/user_experience_design/

4. Nielsen, J. (1994). *Usability Engineering*. Morgan Kaufmann Publishers.

5. Garrett, J. J. (2011). *The Elements of User Experience: User-Centered Design for the Web and Beyond* (2nd ed.). New Riders.

6. Cooper, A., Reimann, R., Cronin, D., & Noessel, C. (2014). *About Face: The Essentials of Interaction Design* (4th ed.). Wiley.

7. Sweller, J. (1988). Cognitive load during problem solving: Effects on learning. *Cognitive Science*, 12(2), 257–285. https://doi.org/10.1207/s15516709cog1202_4

8. Fitts, P. M. (1954). The information capacity of the human motor system in controlling the amplitude of movement. *Journal of Experimental Psychology*, 47(6), 381–391. https://doi.org/10.1037/h0055392

9. Hick, W. E. (1952). On the rate of gain of information. *Quarterly Journal of Experimental Psychology*, 4(1), 11–26. https://doi.org/10.1080/17470215208416600

10. Wertheimer, M. (1923). Untersuchungen zur Lehre von der Gestalt II. *Psychologische Forschung*, 4, 301–350.

11. Shneiderman, B., Plaisant, C., Cohen, M., Jacobs, S., & Elmqvist, N. (2016). *Designing the User Interface: Strategies for Effective Human-Computer Interaction* (6th ed.). Pearson.

12. APJII. (2023). *Laporan Survei Internet Indonesia 2022–2023*. Asosiasi Penyelenggara Jasa Internet Indonesia. Diakses dari https://apjii.or.id/survei

13. Google, Temasek, & Bain & Company. (2023). *e-Conomy SEA 2023: Indonesia Digital Economy Report*. Diakses dari https://economysea.withgoogle.com/

14. ISO 9241-210. (2019). *Ergonomics of human-system interaction — Part 210: Human-centred design for interactive systems*. International Organization for Standardization.

15. Tidwell, J., Brewer, C., & Valencia, A. (2020). *Designing Interfaces: Patterns for Effective Interaction Design* (3rd ed.). O'Reilly Media.
