# NEXORA CONSTRUCTION GROUP

**Tagline:** Building Tomorrow, Today.  
**Target Market:** Malaysia  
**Project Scope:** Proyek Ujian Tengah Semester (UTS) Semester 3 (HTML5 & CSS3 Murni)

## Deskripsi Proyek

Website Company Profile untuk **NEXORA CONSTRUCTION GROUP**, sebuah perusahaan kontraktor konstruksi bangunan demonstrasi yang beroperasi di Malaysia. Seluruh website dibangun menggunakan **HTML5** dan **CSS3 murni** (Flexbox, CSS Grid, Media Queries, Transitions, dan Keyframes) tanpa JavaScript, TypeScript, ataupun framework CSS/JS apa pun.

## Struktur Folder

```text
nexora-construction/
│
├── index.html
├── services.html
├── projects.html
├── contact.html
│
├── css/
│   └── style.css
│
├── images/
│   ├── logo.png
│   ├── hero-construction.jpg
│   ├── about-company.jpg
│   ├── service-residential.jpg
│   ├── service-commercial.jpg
│   ├── service-industrial.jpg
│   ├── service-renovation.jpg
│   ├── service-infrastructure.jpg
│   ├── service-management.jpg
│   ├── project-01.jpg
│   ├── project-02.jpg
│   ├── project-03.jpg
│   └── project-04.jpg
│
└── README.md
```

## Halaman & Fitur Utama

1. **`index.html` (Home)**
   - Navbar transparan di atas hero image dengan navigasi 4 menu utama (`Home`, `Services`, `Projects`, `Contact`) serta menu mobile CSS-only menggunakan elemen `<details>`/`<summary>`.
   - Full-screen hero image dengan headline *"BUILDING THE FUTURE WITH CONFIDENCE"*, subheadline, tombol CTA ke `services.html`, dan strip ringkasan 3 kolom di bagian bawah hero.
   - Ringkasan profil perusahaan, statistik demonstrasi, pratinjau layanan unggulan, pratinjau proyek demonstrasi, dan footer profesional.

2. **`services.html` (Services)**
   - Menampilkan 6 layanan utama: Residential Construction, Commercial Building, Industrial Construction, Renovation & Remodeling, Infrastructure Development, dan Project Management.
   - Setiap layanan dilengkapi foto representatif, deskripsi, rincian lingkup pekerjaan, dan tombol `Contact Us` menuju `contact.html`.

3. **`projects.html` (Projects)**
   - Menampilkan portofolio proyek demonstrasi dalam kategori **Residential**, **Commercial**, **Industrial**, dan **Infrastructure** di berbagai wilayah Malaysia (Kuala Lumpur, Shah Alam, Batu Kawan Penang, Iskandar Puteri Johor).
   - Efek hover zoom gambar menggunakan CSS murni dan label kategori visual tanpa filter JavaScript.

4. **`contact.html` (Contact)**
   - Informasi kantor demonstrasi di Kuala Lumpur (alamat, email `mailto:`, nomor telepon `tel:`, kontak WhatsApp, dan jam operasional).
   - Formulir konsultasi proyek HTML5 dengan validasi bawaan browser (`required`, `type="email"`, `type="tel"`, `minlength`, serta pseudo-class `:user-invalid` / `:user-valid` pada CSS).

## Cara Menjalankan

1. Buka folder `nexora-construction` di Visual Studio Code.
2. Klik kanan pada `index.html` lalu pilih **Open with Live Server**.
3. Uji navigasi antar halaman (`Home`, `Services`, `Projects`, `Contact`), formulir HTML5, serta tampilan responsif di Desktop, Tablet, dan Smartphone.
