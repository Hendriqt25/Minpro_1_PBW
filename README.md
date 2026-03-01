# Mini Project 1 PBW

## Deskripsi Web

Project Website ini dirancang untuk sebagai portofolio pribadi yang bertujuan untuk menampilkan informasi mengenai identitas diri, pengalaman organisasi, keahlian, serta sertifikat yang telah didapat.

##  Tampilan Website Portofolio 

### Tampilan Utama ( Hero Section )

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/22c27eab-05fa-42bd-b4d9-f6efd2ac177a" />

Pada halaman utama, website portofolio ini menampilkan nama lengkap, foto profil, role, deskripsi singkat dan tombol untuk menuju ke linkdln.

<img width="1891" height="88" alt="image" src="https://github.com/user-attachments/assets/a8b97590-3475-4790-b856-eaad9f3b5a19" />

Kemudian bisa diliat pada navbar diatas memliki 4 menu navigasi nya yaitu home, about me, certificates dan profil yang memiliki tujuan masing masing ketika diklik.

### Tampilan About Me ( About Me Section )

<img width="1919" height="1062" alt="image" src="https://github.com/user-attachments/assets/acd87919-21a3-4e8f-87f9-6117d3ee5582" />

Pada tampilan About Me, menampilkan deskripsi diri, daftar skill dengan progress bar dan daftar pengalaman yang sudah dijalani

### Tampilan Certificates ( Certificates Section )

<img width="1919" height="583" alt="image" src="https://github.com/user-attachments/assets/a9d33560-2da0-4667-aef5-48a17c38a3a9" />

Pada tampilan Certificates, menampilkan daftar sertifikat yang sudah diakui dan sudah diselesaikan dalam bentuk card. Dalam masing-masing cartnya memuat foto gambar, judul, instansi dan tahun pelaksanaannya.


## Penjelasan Code untuk setiap section/fitur

### Head

<img width="1165" height="280" alt="image" src="https://github.com/user-attachments/assets/f956022d-634e-469c-bd8a-bc0706fe4fb3" />

Pada head ini berfungsi utnuk struktur awal html dan sebagai mengatur identitas halaman, menghubungkan bootstrap, dan menghubungkan file CSS eksternal untuk mengatur tampilan website contoh pada gambar diatas indentitas/title webside bernama portofolio - Hendriii dan bagain mengimput library CSS dan bootstrap.

### Body

<img width="416" height="99" alt="image" src="https://github.com/user-attachments/assets/55a42494-e047-4bac-8863-2800a2e854dd" />

Pada body ini merupakan bagian utama dokumen html. Dilihat pada digambar atas menggunakan "id=app" berfungsi pada vue.js dalam mengatur data seperti nama, skill, pengalaman, dan sertifikat.

### Navbar

<img width="961" height="713" alt="image" src="https://github.com/user-attachments/assets/26de14a8-647f-4bae-bbf3-e75377d183cb" />

pada navbar ini merupakan navbar responsif dengan brand/judul "Portofolio" serta 4 menu navigasi yaitu Home, About, Certificates, dan Profil yang memiliki tujuan masing masing jika diklik. 

### Hero

<img width="1076" height="687" alt="image" src="https://github.com/user-attachments/assets/7afc16fa-9c83-47b7-af9b-d9b5736fa0db" />

pada hero ini menggunakan bootstrip dengan layout dua kolom dimana sisi kiri menampilkan indetitas diri yaitu nama, role, dll sedangkan sisi kanan menampilkan foto profil

<img width="717" height="196" alt="image" src="https://github.com/user-attachments/assets/f0902b5b-ec50-46cc-9948-9c11cb1c3be0" />

pada variabel "{{ name }}" berfungsi untuk mengubah nama sesuai data yang diberikan pada vue. kemudian pada "{{ role }}" berfungsi menampilkan posisi atau bidang keahlian, sedangkan "{{ description }}" berfungsi untuk menampilkan deskripsi singkat mengenai profil pengguna.

### About Me

<img width="1027" height="831" alt="image" src="https://github.com/user-attachments/assets/3a749f8a-009a-4700-8f44-a8555839b3c8" />

Pada About Me ini berfungsi menampilkan profil lengkap, pengalaman, dan skill dengan progress bar. 

<img width="814" height="466" alt="image" src="https://github.com/user-attachments/assets/8020633a-9c65-4f74-af13-b6e61ec2e51a" />

pada "v-for="skill in skills" :key="skill.name""berfungsi mengulang setiap skill yang ada di data vue dan menampilkan nama serta persentase skillnya. kemudian pad a":style="{ width: skill.level + '%' }"" berfungsi Mengatur lebar progress barnya dan pada "{{ skill.level }}%" berfungsi menampilkan angka persentase di dalam progress bar.

### Certificates 

<img width="751" height="342" alt="image" src="https://github.com/user-attachments/assets/38221ea0-42ae-464b-aec5-e76f30224abb" />

Pada Certificates ini berfungsi menampilkan daftar sertifikat dalam bentuk card.

pada "<div class="card" v-for="cert in certificates" :key="cert.title">" berfungsi mengulang data pada vue dan dibuatkan satu card. kemudian pada "{{ cert.title }}" berfungsi menampilkan nama atau judul sertifikat secara otomatis. dan Pad "{{ cert.organization }} - {{ cert.year }}" berfungsi menampilkan informasi tambahan seperti nama instansi dan tahun.

### Vue  

<img width="1329" height="843" alt="image" src="https://github.com/user-attachments/assets/16cfa7a2-7df4-4047-bd77-aebdbc052d44" />

Pada aplikasi Vue, Seluruh data pada gambar diatas akan ditampilkan di website dengan memanggil menggunakan tanda {{ }} atau v-for.

### Footer

<img width="473" height="100" alt="image" src="https://github.com/user-attachments/assets/99b7f0b3-094a-4f41-ad55-ab792679586c" />

Pada footer ini berfungsi menampilkan informasi hak cipta(copyright) tahun 2026 sebagi penutup dari website.

## Teknologi yang digunakan 

- HTML
- CSS
- BOOTSTRAP
- VUE.JS


