## 📣 Haloo..Dear Eco Techno Leaders
Mari kita sama-sama mempelajari environment setup untuk Data Science/AI dengan:
##### ✅ Anaconda
##### ✅ Conda
##### ✅ UV
### 🐍Apa itu ANACONDA???apakah ular anaconda yang di film-film🤔? eisss, no no no...
Anaconda adalah sebuah distribusi open-source dari bahasa pemrograman Python dan R yang dirancang khusus untuk keperluan ilmu data (data science), analisis data, komputasi ilmiah, dan pembelajaran mesin (machine learning).Anaconda adalah paket super lengkap berisi!
### ⚙️ Apa itu Conda?
Conda adalah package manager dan environment manager open-source yang digunakan terutama untuk mengelola paket dan dependensi dalam bahasa pemrograman Python (juga bisa untuk R, Ruby, Lua, dan lainnya).
##### 🎯 Mengapa Conda Penting?
##### 1. Tanpa Conda
##### 🚫 "Wah, project ini error gara-gara versinya bentrok!"
##### 🚫 "Aduh, saya install TensorFlow, yang lama jadi rusak!"
##### 2. Dengan Conda
##### ✅ "Tiap project punya dapur sendiri, aman!"
##### ✅ "Mau ganti Python versi berapa pun? Gampang!"
##### ✅ "Install banyak tools data science? Sekali klik!"
###  ⚡ Apa itu uv?
#### 🌞UV (Ultraviolet)🤣no no ya gess, yang bener itu..
### 🔍 UV (Python/Anaconda Context)
uv adalah manajer paket Python modern dan super cepat, dikembangkan dengan bahasa Rust.
Fungsinya mirip seperti pip dan venv, tetapi:
##### ⚡ Lebih cepat
##### 🔐 Bisa membuat lock file untuk kestabilan dependensi
##### 🔄 Kompatibel dengan pyproject.toml
_________________________________________________________________________________________________________________________________________________________________________________________
## Panduan untuk Pengaturan Lingkungan Anaconda, Conda, dan UV
### 🐍 Mengunduh Anaconda
##### Apa sih Anaconda itu?
Anaconda adalah “paket lengkap” Python yang udah dibekali ratusan library buat analisis data, statistik, dan komputasi ilmiah. Jadi, kamu nggak perlu ribet install satu-satu secara manual.
##### Kenapa harus pakai Anaconda?
Dengan install Anaconda, kamu langsung dapet banyak alat penting buat Data Science—kayak Jupyter Notebook, Spyder, dan library populer seperti pandas, numpy, dll.
Jadi lebih hemat waktu dan lebih aman karena semua udah diatur biar kompatibel.
##### Do's (yang sebaiknya dilakukan):
✔️ Pilih Python versi 3.12, karena ini versi terbaru dan paling kompatibel sama banyak pustaka.
##### Don'ts (yang harus dihindari):
❌ Jangan install versi 32-bit, kecuali laptop kamu memang nggak support 64-bit (rata-rata sih udah support).
##### 🪜 Langkah-langkah Mengunduh:
Buka browser, lalu kunjungi:
##### 1. Download Installer Anaconda
👉 https://www.anaconda.com/download

![Alt](https://github.com/ulanndari/TASK-SETUP-ANACONDA-UV/blob/main/gambar.1.png?raw=true)

##### ✅ Do's (Yang Sebaiknya Dilakukan):
1. Download langsung dari situs resmi Anaconda 👉 biar aman dan terjamin.
2. Simpan file installernya di folder yang gampang dicari, misalnya di Desktop atau folder Download — jadi nggak ribet pas mau install nanti.
##### ❌ Don’ts (Yang Sebaiknya Dihindari):
1. Jangan asal download dari situs lain atau link nggak jelas — bisa aja isinya virus atau installer palsu.
2. Jangan simpan file installer di folder sistem kayak C:\Windows — itu bikin ribet dan kadang butuh izin admin.
### 🛠️ Jalankan Installer Anaconda
###### Apa sih maksudnya?
Ini adalah proses menginstal Anaconda ke laptop kamu — biar Python dan semua alat bantu data science siap dipakai.
Kenapa perlu install Anaconda?
Karena Anaconda nggak cuma ngasih kamu Python, tapi juga banyak pustaka (library) penting seperti numpy, pandas, matplotlib, bahkan udah termasuk Jupyter Notebook dan Spyder IDE. Jadi kamu nggak perlu install satu-satu lagi. Hemat waktu, hemat tenaga!
###### 🪜 Langkah-langkah Instalasinya:
1. Klik dua kali file installer Anaconda yang udah kamu download sebelumnya.
2. Akan muncul wizard instalasi — tinggal klik “Next” beberapa kali.
   
   ![Alt](https://github.com/ulanndari/TASK-SETUP-ANACONDA-UV/blob/main/gambar.4.png?raw=treu)
   
3. Saat muncul pilihan:
   
   ![Alt](https://github.com/ulanndari/TASK-SETUP-ANACONDA-UV/blob/main/gambar.5.png?raw=treu)
   
   “Add Anaconda to my PATH environment variable”
 4. Klik Install, lalu tunggu prosesnya selesai. Bisa makan waktu beberapa menit tergantung spek laptop kamu.
##### ✅ Do’s (Yang Sebaiknya Dilakukan):
1. Gunakan pengaturan default aja kalau kamu nggak yakin mau ubah apa — ini udah paling aman dan direkomendasikan.
2. Centang opsi “Add to PATH” kalau kamu pengin bisa akses Anaconda langsung dari Command Prompt atau terminal di mana saja.
##### ❌ Don’ts (Yang Sebaiknya Dihindari):
1. Jangan instal Anaconda ke folder sistem kayak C:\Windows atau C:\Program Files (x86) — bisa bikin error atau butuh izin admin.
2. Jangan klik cancel di tengah proses instalasi, apalagi pas udah jalan setengah. Bisa bikin file jadi setengah jadi dan error pas dijalankan.
### 3. ✅ Verifikasi Anaconda Sudah Terpasang dan Bisa Diakses
##### Apa sih maksudnya?
Di sini kita mau cek dulu, apakah Anaconda udah beneran ke-install dan bisa dijalankan lewat terminal atau command prompt. Ibaratnya, ini kayak test drive buat lihat apakah semuanya oke sebelum lanjut ke langkah berikutnya.
##### Kenapa perlu dicek?
Biar kamu nggak kena masalah di tengah jalan, misalnya conda nggak dikenali atau Python-nya belum aktif. Verifikasi ini bakal kasih tahu apakah semua udah beres atau masih ada yang perlu dibenerin.
##### 🪜 Langkah-langkahnya Gampang Banget:
1. Buka Command Prompt
(klik Start → ketik "cmd" → Enter)
2. Tekan Enter.
3. jika muncul sesuatu seperti ini:
   
   ![Alt](https://github.com/ulanndari/TASK-SETUP-ANACONDA-UV/blob/main/gambar.6.png?raw=true)

   berarti Anaconda kamu udah sukses ke-install dan siap dipakai! 🎉
##### ❗Kalau Nggak Muncul?
1. Coba restart laptop dulu, terus ulangi langkah di atas.
2. Kalau tetap nggak muncul, mungkin opsi PATH-nya belum dicentang waktu instalasi. Tapi tenang, masih bisa diatur nanti secara manual.
##### ✅ Do’s (Yang Perlu Dilakukan):
1. Buka terminal baru dulu (jangan pakai yang lama) setelah instalasi selesai — biar pengaturan PATH yang baru kebaca dengan benar.
2. Pastikan perintah jalan tanpa error, dan muncul versi conda — itu tandanya Anaconda udah siap dipakai.
##### ❌ Don’ts (Yang Harus Dihindari):
Jangan cuek kalau ada error atau nggak muncul apa-apa. Itu bisa jadi tanda ada yang salah pas instalasi. Lebih baik dicek sekarang daripada nanti pusing pas lagi butuh.
### 🛠️ Cara Menambahkan Anaconda ke PATH (Biar Bisa Diakses dari Mana Aja)
Kadang setelah instalasi, Anaconda belum otomatis bisa dipanggil dari terminal atau CMD. Nah, di sinilah kita tambahkan sendiri ke PATH, supaya conda dan python bisa langsung dikenali dari mana saja.
##### 🪜 Langkah-langkah di Windows:
1. Tekan  Windows + R, ketik sysdm.cpl, tekan Enter.
2. Buka tab "Advanced", lalu klik tombol "Environment Variables…"
3. Di bagian bawah (System variables), cari dan klik Path, lalu klik Edit.
4. Klik New, lalu tambahkan dua baris ini (ganti NAMA_ANDA dengan nama user di laptop kamu):
   
   ![Alt](https://github.com/ulanndari/TASK-SETUP-ANACONDA-UV/blob/main/gambar.7.png?raw=true)
   
##### ✅ Do’s (Yang Sebaiknya Dilakukan):
1. Tutup dulu terminal/CMD yang lama, terus buka yang baru setelah kamu ubah PATH — biar setting barunya kebaca dengan benar.
2. Kalau masih belum bisa, coba restart laptopnya. Kadang Windows baru ngeh setelah di-restart.
##### ❌ Don’ts (Yang Harus Dihindari):
1. Jangan asal hapus isi PATH lain — itu bisa bikin program penting lain di laptop kamu jadi nggak jalan.
2. Edit variabel lingkungan dengan hati-hati, karena ini menyangkut sistem. Kalau ragu, sebaiknya dicatat dulu isi PATH sebelumnya sebelum mengubah.
### 6. 🛠️ Membuat Lingkungan Conda
##### 📌 Apa itu Lingkungan Conda?
Lingkungan Conda adalah ruang kerja virtual yang terisolasi untuk Python dan paket-paket yang digunakan dalam proyek tertentu.
##### ❓ Kenapa Perlu Lingkungan Conda?
1. Mencegah konflik versi paket antar proyek
2. Memastikan stabilitas dan kompatibilitas
3. Memudahkan pengelolaan dependensi
##### ✅ Do's (yang sebaiknya dilakukan):
1. Beri nama atau lokasi environment yang relevan dengan proyek
2. Simpan environment di dalam folder proyek untuk portabilitas
##### ❌ Don’ts (yang harus dihindari):
1. Jangan buat di direktori acak yang tidak ada hubungannya dengan proyek
2. Jangan campur environment proyek A dengan proyek B
##### 🪜 Langkah-langkah Praktis:
1. Buka Terminal di VS Code
2. Tekan Ctrl + ` (tanda backtick di bawah tombol Esc)
3. Jalankan perintah berikut untuk membuat environment:
##### conda create -p venv python=3.12
Catatan:
1. -p venv artinya membuat environment di folder ./venv dalam proyek kamu
2. python=3.12 menentukan versi Python yang digunakan
Saat muncul pertanyaan:
Proceed ([y]/n)?
##### ➡️ Ketik y lalu tekan Enter

![Alt](https://github.com/ulanndari/TASK-SETUP-ANACONDA-UV/blob/main/gambar.11.png?raw=true)

##### Setelah selesai, aktifkan environment dengan:
conda activate ./venv
##### Prompt terminal akan berubah menjadi:
(venv) C:\Users\ACER\ghost_intellix>

![Alt](https://github.com/ulanndari/TASK-SETUP-ANACONDA-UV/blob/main/gambar.10.png?raw=true)

Artinya environment berhasil diaktifkan.
### ⚡ Menginstal UV (Ultra Cepat!)
#### Apa sih UV itu?
UV itu alat buat ngatur paket dan lingkungan, kayak pip + venv, tapi kecepatannya ngebut karena dibuat pakai Rust. Cocok banget buat proyek yang punya banyak pustaka (dependensi).
#### Kenapa pakai UV?
Karena UV bikin proses install jadi jauh lebih cepat. Apalagi kalau proyek kamu besar, ini hemat waktu banget.
##### ✅ do's (Lakukan ini):
Pastikan kamu sudah keluar dari environment Conda dulu sebelum pakai UV (biar gak bentrok).
##### ❌ don'ts Jangan lakukan ini:
Jangan pakai UV buat install paket-paket khusus Conda, karena UV jalan pakai pip, bukan conda.
##### 🚶‍♂️Langkah-langkah Instalasi UV:
1. Pastikan environment Conda udah dinonaktifkan:
Ketik dulu:
###### conda deactivate
Kalau udah, prompt bakal balik ke direktori biasa.
2. Install UV:
Ketik di terminal atau CMD:
###### pip install uv
Tunggu sampai muncul tulisan:
###### Successfully installed uv-0.7.12
Artinya UV berhasil dipasang 🎉
##### 🗂️ Tentang Folder ghost_intellixuv
Nanti kita bakal pakai perintah uv init buat bikin folder baru bernama ghost_intellixuv.
##### 📌 Catatan penting:
1. Kamu nggak perlu bikin folder itu manual.
2. UV akan otomatis bikin folder dan isi dasarnya waktu kamu jalanin uv init.
3. Setelah itu, kamu bisa ketik:
###### dir
buat lihat apakah folder ghost_intellixuv udah muncul.
#### 🧪 Membuat & Mengaktifkan Lingkungan UV
##### Apa sih maksudnya?
Lingkungan virtual (virtual environment) itu kayak “dunia kecil” khusus buat proyek kamu. Semua pustaka yang diinstal akan disimpan di situ — jadi nggak nyampur sama proyek lain.
##### Kenapa penting?
Biar tiap proyek punya ruang sendiri dan gak bikin konflik, apalagi kalau beda versi pustaka.
##### ✅ do's (Lakukan ini):
Aktifkan environment sebelum install paket.
##### ❌ don'ts (Jangan lakukan ini):
Jangan utak-atik folder .venv secara manual, biarin UV yang ngurus.
##### 🚀 Langkah-langkah Bikin dan Aktifkan Environment
##### 1. Ketik:
###### uv venv
##### 2. Aktifkan:
###### .venv\Scripts\activate
Prompt berubah ke (ghost_intellixuv) C:\Users\NAMA_ANDA\ghost_intellix\ghost_intellixuv>.
3. Ciri-ciri environment sudah aktif:
Prompt di terminal bakal berubah, misalnya jadi:
###### (ghost_intellixuv) C:\Users\NAMA_ANDA\ghost_intellix\ghost_intellixuv>
Nah, kalau udah kayak gitu, berarti kamu siap lanjut install paket dan mulai ngoding! 😎
#### 📦 Menginstal Paket dengan UV
##### Apa sih ini?
UV itu punya fitur keren buat install paket super cepat lewat perintah mirip pip. Tapi di UV, kita pakenya uv add.
##### Kenapa pakai UV?
Karena UV install paketnya kilat banget, terutama kalau paketnya besar kayak pandas, numpy, atau matplotlib. Cocok buat kamu yang gak mau nunggu lama! ⚡
##### ✅ do's (Lakukan ini):
Install paket pakai uv add (bukan pip install).
##### ❌ don'ts (Jangan lakukan ini):
Jangan campur UV dan pip dalam proyek yang sama, nanti bisa bikin konflik dependensi.
##### 🚀 Langkah-langkah Install Paket:
1. Pastikan environment kamu aktif dulu (lihat ada tanda (ghost_intellixuv) di terminal).
Ketik perintah:
###### uv add pandas
2. output seperti
   
![Alt](https://github.com/ulanndari/TASK-SETUP-ANACONDA-UV/blob/main/gambar.13.png?raw=true)

##### 📝 Catatan Penting:
UV jauh lebih cepat dibanding pip, apalagi kalau kamu install paket yang punya banyak “anak paket” alias dependency tree yang besar — contohnya pandas, scikit-learn, atau tensorflow.
##### 💡 Jadi kalau proyekmu makin kompleks, UV justru makin terasa manfaatnya: lebih cepat, lebih efisien, dan tetap rapi..
##### 🚶‍♂️Langkah Menonaktifkan:
1. Di terminal, ketik:
###### .venv\Scripts\deactivate
2. Setelah itu, prompt akan berubah kembali seperti semula, misalnya:
###### C:\Users\NAMA_ANDA\ghost_intellix\ghost_intellixuv>
Artinya kamu sudah keluar dari lingkungan virtual UV.
###### ✨ Sekarang kamu udah tahu cara masuk dan keluar dari environment. Rapi, aman, dan siap untuk proyek berikutnya!
### 📓 Membuat Notebook di VS Code
##### Apa sih notebook itu?
Notebook (dengan ekstensi .ipynb) itu semacam dokumen interaktif buat nulis kode Python, catatan, dan grafik — semuanya dalam satu tempat. Biasanya dipakai buat eksplorasi data, visualisasi, atau eksperimen model AI.
##### Kenapa pakai notebook?
Karena enak banget! Kamu bisa nulis kode, langsung jalanin, dan lihat hasilnya tanpa pindah-pindah jendela. Cocok buat analisis data atau ngulik kode.
##### ✅ do's (Lakukan ini):
Simpan notebook langsung di dalam folder proyek kamu.
##### ❌ don'ts (Jangan lakukan ini):
Jangan buat notebook di luar environment virtual, nanti gak bisa akses paket-paket proyek.
1. Di VS Code, buat folder 1-Langchain.
2. Klik kanan → New File → test.ipynb.
#### Memilih Kernel
##### Apa: Kernel menentukan lingkungan Python untuk notebook.
##### Kenapa: Kernel yang benar memastikan akses ke paket proyek.
##### Do's: Verifikasi kernel sesuai lingkungan.
##### Don'ts: Jangan gunakan kernel sistem default.
#### Langkah-langkah:
1. Klik pemilih kernel di kanan atas notebook.
2. Pilih .venv (Python 3.12.7) ghost_intellixuv\.venv\Scripts\python.exe.
3. Alternatif: Ctrl+Shift+P → "Select Kernel".
##### ✨ Sekarang kamu bisa nulis kode, uji langsung, dan bikin visualisasi tanpa ribet!
⚖️ Perbandingan Conda vs UV
🔍 Apa itu?
Conda dan UV adalah dua alat manajemen paket dan environment di Python, namun ditujukan untuk kebutuhan yang berbeda.

![Alt](https://github.com/ulanndari/TASK-SETUP-ANACONDA-UV/blob/main/gambar.14png?raw=true)

🎯 Kenapa Perlu Dibandingkan?
Karena pilihan alat akan memengaruhi kecepatan kerja, kompatibilitas paket, dan manajemen proyek. Menggunakan alat yang sesuai bisa menghemat waktu dan menghindari konflik antar dependensi.
## Daftar Paket yang Direkomendasikan
##### Apa: Paket penting untuk Data Science, Machine Learning, dan AI.
##### Kenapa: Memastikan alat yang diperlukan tersedia.
##### Do's: Perbarui versi paket secara berkala.
##### Don'ts: Jangan instal paket yang tidak diperlukan.
#### Langkah-langkah:
1. Buat requirements.txt:
   
![Alt](https://github.com/ulanndari/TASK-SETUP-ANACONDA-UV/blob/main/gambar.16.png?raw=true)

2. Instal:
###### uv add -r requirements.txt
3. atau
###### pip install -r requirements.txt
#### 🛠️ Panduan Pemecahan Masalah di Anaconda
##### 🔧 Masalah 1: conda Tidak Dikenali di Terminal
Gejala:
###### 'conda' is not recognized as an internal or external command
Penyebab:
###### PATH Anaconda belum terdaftar di sistem.
##### Solusi:
1. Pastikan Anaconda sudah diinstal.
2. Tambahkan PATH secara manual (jika belum otomatis):
3. Buka System Properties → Environment Variables.
4. Di bagian “System variables”, cari Path → klik Edit.
5. Tambahkan jalur berikut:
###### C:\Users\NAMA_ANDA\anaconda3
###### C:\Users\NAMA_ANDA\anaconda3\Scripts
6. Jalankan perintah:
###### conda init cmd.exe
7. Tutup dan buka kembali terminal.
##### 🔧 Masalah 2: Script execution is disabled (saat aktivasi environment)
Gejala:
###### File C:\... activate.ps1 cannot be loaded because running scripts is disabled
#### Penyebab:
PowerShell tidak mengizinkan eksekusi skrip.
##### Solusi:
Jalankan PowerShell sebagai Administrator.
#### Ketik:
##### Set-ExecutionPolicy RemoteSigned
Ketik Y untuk mengonfirmasi.
### Kesimpulan
1. Anaconda = “semua‑dalam‑satu” untuk data science; instal sekali, langsung jalan.
2. Conda = motor di balik Anaconda; andal untuk kelola paket lintas‑bahasa & environment terisolasi.
3. UV = solusi modern yang super cepat & ringan ketika Anda hanya butuh Python wheels dari PyPI.
### Pilihan cepat:
1. Data/ML berat & paket C/CUDA → Conda/Anaconda
2. Proyek Python murni & butuh kecepatan → UV
