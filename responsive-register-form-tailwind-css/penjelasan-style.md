
# Penjelasan Class Tailwind CSS pada `index.html`

Dokumen ini menjelaskan kegunaan dari setiap class utility Tailwind CSS yang digunakan untuk membangun form registrasi pada file `index.html`.

---

### Body (`<body>`)

- `bg-gray-100`: Memberi warna latar belakang abu-abu sangat terang pada seluruh halaman.
- `flex`: Mengaktifkan layout Flexbox.
- `items-center`: Menengahkan konten secara vertikal (di sumbu Y).
- `justify-center`: Menengahkan konten secara horizontal (di sumbu X).
- `min-h-screen`: Memberi tinggi minimal setinggi layar penuh, memastikan konten selalu di tengah layar, bahkan jika kontennya sedikit.

### Kontainer Form (`<div>` utama)

- `bg-white`: Memberi latar belakang putih pada kontainer form.
- `p-8`: Memberi padding (jarak dalam) sebesar 2rem (32px) di semua sisi.
- `rounded-lg`: Memberi sudut yang membulat (border-radius) dengan ukuran besar.
- `shadow-lg`: Memberi efek bayangan yang besar dan jelas di sekitar form.
- `w-full`: Membuat lebar elemen 100% dari induknya.
- `max-w-md`: Membatasi lebar maksimal form hingga `medium` (28rem atau 448px), agar tidak terlalu lebar di layar besar.

### Judul Form (`<h2>`)

- `text-2xl`: Mengatur ukuran font menjadi `1.5rem` (24px).
- `font-bold`: Membuat teks menjadi tebal.
- `text-center`: Menengahkan posisi teks.
- `text-gray-800`: Memberi warna teks abu-abu gelap.
- `mb-8`: Memberi margin bawah (jarak luar bawah) sebesar `2rem` (32px).

### Layout Grid untuk Input Nama (`<div>`)

- `grid`: Mengaktifkan layout Grid.
- `grid-cols-1`: Secara default, menyusun item dalam 1 kolom (untuk layar kecil/mobile).
- `sm:grid-cols-2`: Pada breakpoint `small` (lebar layar 640px atau lebih), mengubah layout menjadi 2 kolom.
- `gap-4`: Memberi jarak (gap) sebesar `1rem` (16px) antara item-item grid.
- `mb-4`: Memberi margin bawah sebesar `1rem` (16px).

### Label untuk Input (`<label>`)

- `block`: Membuat label ditampilkan sebagai elemen block (mengisi satu baris penuh).
- `text-sm`: Mengatur ukuran font menjadi `0.875rem` (14px).
- `font-medium`: Memberi ketebalan font medium.
- `text-gray-700`: Memberi warna teks abu-abu sedang.
- `mb-1`: Memberi margin bawah kecil sebesar `0.25rem` (4px).

### Input Fields (`<input>`)

- `w-full`: Membuat lebar input 100% dari kontainer.
- `px-3`: Memberi padding horizontal (kiri dan kanan) sebesar `0.75rem` (12px).
- `py-2`: Memberi padding vertikal (atas dan bawah) sebesar `0.5rem` (8px).
- `border`: Menambahkan border (garis tepi) tipis di semua sisi.
- `border-gray-300`: Mengatur warna border menjadi abu-abu terang.
- `rounded-md`: Memberi sudut yang membulat dengan ukuran medium.
- `shadow-sm`: Memberi efek bayangan yang sangat tipis.
- `focus:outline-none`: Menghilangkan outline bawaan browser saat input di-fokus.
- `focus:ring-2`: Menambahkan efek "cincin" (ring) saat input di-fokus sebagai pengganti outline.
- `focus:ring-blue-500`: Mengatur warna ring menjadi biru saat di-fokus.

### Tombol Submit (`<button>`)

- `w-full`: Membuat lebar tombol 100%.
- `bg-blue-600`: Memberi warna latar belakang biru.
- `text-white`: Memberi warna teks putih.
- `font-semibold`: Membuat teks menjadi semi-tebal.
- `py-2 px-4`: Memberi padding vertikal `0.5rem` dan horizontal `1rem`.
- `rounded-md`: Memberi sudut membulat ukuran medium.
- `hover:bg-blue-700`: Mengubah warna latar belakang menjadi biru lebih gelap saat kursor mouse berada di atasnya.
- `focus:outline-none`: Menghilangkan outline bawaan browser saat tombol di-fokus.
- `focus:ring-2`: Menambahkan efek ring saat di-fokus.
- `focus:ring-offset-2`: Memberi sedikit jarak antara ring dengan tombol itu sendiri.
- `focus:ring-blue-500`: Mengatur warna ring menjadi biru.
- `transition`: Menambahkan efek transisi yang mulus untuk semua perubahan (misal: perubahan warna saat hover).
- `duration-200`: Mengatur durasi transisi menjadi 200 milidetik.

### Teks Link Login (`<p>` dan `<a>`)

- `text-center`: Menengahkan teks.
- `text-sm`: Mengatur ukuran font menjadi `0.875rem` (14px).
- `text-gray-600`: Memberi warna teks abu-abu sedang.
- `mt-6`: Memberi margin atas sebesar `1.5rem` (24px).
- `text-blue-600`: Memberi warna biru pada link.
- `hover:underline`: Menambahkan garis bawah saat kursor mouse berada di atas link.
- `font-medium`: Memberi ketebalan font medium pada link.
