## Daftar Style Tailwind CSS pada `index.html`

Berikut adalah daftar kelas-kelas Tailwind CSS yang digunakan dalam file `index.html` beserta penjelasan singkat mengenai fungsinya.

### Body & Layout Utama
- `bg-gray-100`: Memberi warna latar belakang abu-abu sangat terang pada elemen `<body>`.
- `font-sans`: Mengatur jenis font menjadi sans-serif.
- `leading-normal`: Mengatur tinggi baris (line-height) normal.
- `tracking-normal`: Mengatur jarak antar huruf (letter-spacing) normal.
- `flex`: Mengaktifkan layout flexbox.
- `md:flex-row-reverse`: Pada layar medium (md) dan lebih besar, mengatur arah flexbox menjadi baris terbalik (konten utama di kiri, sidebar di kanan)., karena sidebar terdapat fixed, sehingga keluar dari hukum fixed
- `flex-wrap`: Memungkinkan item flex untuk pindah ke baris baru jika tidak cukup ruang.

### Sidebar
- `w-full`: Mengatur lebar elemen menjadi 100% dari parent.
- `md:w-1/5`: Pada layar medium (md) dan lebih besar, lebar sidebar menjadi 1/5 dari lebar layar.
- `bg-gray-900`: Memberi warna latar belakang abu-abu sangat gelap.
- `px-2`: Memberi padding horizontal (kiri dan kanan) sebesar 0.5rem.
- `text-center`: Mengatur teks agar rata tengah.
- `fixed`: Memposisikan elemen secara tetap (fixed) relatif terhadap viewport.
- `bottom-0`: Memposisikan elemen di bagian bawah layar (untuk mobile).
- `md:pt-8`: Pada layar medium (md) dan lebih besar, memberi padding atas sebesar 2rem.
- `md:top-0`: Pada layar medium (md) dan lebih besar, memposisikan elemen di bagian atas layar.
- `md:left-0`: Pada layar medium (md) dan lebih besar, memposisikan elemen di sisi kiri layar.
- `h-16`: Mengatur tinggi elemen menjadi 4rem (untuk mobile).
- `md:h-screen`: Pada layar medium (md) dan lebih besar, tinggi elemen menjadi 100% dari tinggi viewport.
- `md:border-r-4`: Pada layar medium (md) dan lebih besar, memberi border kanan setebal 4px.
- `md:border-gray-600`: Mengatur warna border menjadi abu-abu gelap.
- `md:relative`: Pada layar medium (md) dan lebih besar, mengubah posisi menjadi relatif.
- `mx-auto`: Mengatur margin horizontal menjadi auto (untuk menengahkan).
- `list-reset`: Menghapus styling default dari list (seperti bullet points).
- `flex-row`: Mengatur item flex dalam satu baris (untuk mobile).
- `md:flex-col`: Pada layar medium (md) dan lebih besar, mengatur item flex dalam satu kolom.
- `md:text-left`: Pada layar medium (md) dan lebih besar, mengatur teks rata kiri.
- `text-gray-400`: Mengatur warna teks menjadi abu-abu.
- `hover:text-white`: Mengubah warna teks menjadi putih saat kursor mouse di atasnya.
- `border-b-2`: Memberi border bawah setebal 2px.
- `hover:border-blue-500`: Mengubah warna border menjadi biru saat kursor di atasnya.
- `text-xs`: Mengatur ukuran font menjadi sangat kecil.
- `md:text-base`: Pada layar medium (md) dan lebih besar, ukuran font menjadi normal.
- `block`: Mengubah display menjadi block.
- `md:inline-block`: Pada layar medium (md) dan lebih besar, display menjadi inline-block.

### Konten Utama
- `md:w-4/5`: Pada layar medium (md) dan lebih besar, lebar konten menjadi 4/5 dari lebar layar.
- `container`: Membuat container dengan lebar maksimum yang responsif.
- `pt-16`: Memberi padding atas sebesar 4rem.
- `px-6`: Memberi padding horizontal sebesar 1.5rem.
- `mx-auto`: Menengahkan container.
- `text-3xl`: Mengatur ukuran font menjadi sangat besar.
- `font-bold`: Menebalkan teks.
- `text-gray-800`: Mengatur warna teks menjadi abu-abu gelap.
- `text-gray-600`: Mengatur warna teks menjadi abu-abu medium.
- `flex-wrap`: Memungkinkan item (kartu) untuk wrap ke baris baru.
- `-mx-4`: Memberi margin horizontal negatif untuk meniadakan padding dari parent.

### Kartu (Cards)
- `w-full`, `md:w-1/2`, `xl:w-1/3`: Mengatur lebar kartu agar responsif. 1 kolom di mobile, 2 di tablet, dan 3 di layar besar.
- `p-4`: Memberi padding di semua sisi sebesar 1rem.
- `bg-white`: Memberi warna latar belakang putih.
- `border`: Memberi border tipis.
- `rounded-lg`: Membuat sudut elemen menjadi lebih tumpul (rounded).
- `shadow-lg`: Memberi efek bayangan yang besar.
- `p-5`: Memberi padding di semua sisi sebesar 1.25rem.
- `flex`: Mengaktifkan flexbox untuk layout di dalam kartu.
- `items-center`: Menyelaraskan item flex secara vertikal di tengah.
- `w-12`, `h-12`: Mengatur lebar dan tinggi ikon menjadi 3rem.
- `bg-blue-500`, `bg-green-500`, `bg-yellow-500`: Memberi warna latar belakang pada ikon.
- `rounded-full`: Membuat elemen menjadi lingkaran sempurna.
- `justify-center`: Menyelaraskan item flex secara horizontal di tengah.
- `text-white`: Mengatur warna teks (ikon) menjadi putih.
- `ml-4`: Memberi margin kiri sebesar 1rem.
- `text-lg`: Mengatur ukuran font menjadi besar.
- `font-semibold`: Menebalkan teks (sedang).
- `text-gray-700`: Mengatur warna teks menjadi abu-abu.
- `text-2xl`: Mengatur ukuran font menjadi ekstra besar.
- `text-gray-900`: Mengatur warna teks menjadi abu-abu sangat gelap.
