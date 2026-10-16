Pengertian Bootstrap
Bootstrap adalah framework CSS yang digunakan untuk mempermudah proses
pembuatan tampilan website. Bootstrap menyediakan berbagai komponen siap
pakai, seperti navbar, tombol, form, card, dan sistem grid. Bootstrap juga
mendukung desain responsif sehingga tampilan website dapat menyesuaikan
ukuran layar perangkat, seperti komputer, tablet, dan smartphone.
2. Memasang Bootstrap
Ada beberapa cara untuk menggunakan Bootstrap pada sebuah proyek website,
yaitu:
1. CDN (Content Delivery Network): Menghubungkan file CSS dan JavaScript
Bootstrap melalui URL CDN tanpa harus mengunduh file secara manual.
2. Download manual: Mengunduh file Bootstrap, kemudian menyimpan dan
menghubungkannya dengan proyek website.
3. Package manager: Memasang Bootstrap menggunakan package manager
seperti npm untuk mengelola dependensi proyek.
3. Grid dan Breakpoint
Grid Bootstrap adalah sistem tata letak yang menggunakan 12 kolom untuk
mengatur posisi dan lebar elemen pada halaman website. Grid menggunakan class
seperti container, row, dan col.
Breakpoint adalah batas ukuran layar yang digunakan untuk menyesuaikan tata
letak website berdasarkan perangkat yang digunakan.
Breakpoint Bootstrap 5 meliputi:
xs: ukuran layar di bawah 576 px.
sm: ukuran layar mulai dari 576 px.
md: ukuran layar mulai dari 768 px.
lg: ukuran layar mulai dari 992 px.
xl: ukuran layar mulai dari 1200 px.
xxl: ukuran layar mulai dari 1400 px.
Contohnya, class col-md-6 membuat elemen memiliki lebar 50% mulai dari ukuran
layar 768 px. Pada layar yang lebih kecil, elemen tersebut secara default dapat
menggunakan lebar penuh.
4. Class Bootstrap
Berikut beberapa class Bootstrap beserta kegunaannya:
container: Membuat wadah konten dengan lebar yang menyesuaikan ukuran layar.
row: Membuat baris untuk menyusun kolom dalam sistem grid.
btn btn-primary: Membuat tombol dengan warna utama Bootstrap.
form-control: Memberikan tampilan standar pada elemen input form.
text-center: Mengatur teks agar rata tengah.
d-flex: Mengaktifkan tata letak Flexbox.
mt-3: Memberikan margin atas dengan ukuran spacing 3.
shadow: Memberikan efek bayangan pada elemen.
navbar: Membuat komponen navigasi website.
img-fluid: Membuat gambar responsif agar tidak melebihi lebar wadahnya.
5. Gambar Responsif
Untuk membuat foto atau gambar responsif menggunakan Bootstrap, gunakan
class img-fluid pada elemen gambar. Class ini membuat lebar gambar maksimal
100% dari wadahnya dan tinggi gambar menyesuaikan proporsinya.
Contoh penggunaan:
<img src="gambar.jpg" class="img-fluid" alt="Gambar">
Dengan menggunakan class tersebut, gambar dapat menyesuaikan ukuran layar
perangkat tanpa melebihi lebar wadahnya dan tanpa mengubah proporsi gambar.
