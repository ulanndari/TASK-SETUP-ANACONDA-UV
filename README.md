# TASK-SETUP-ANACONDA-UV
## 📣 Haloo..Dear Eco Techno Leaders
Mari kita sama-sama mempelajari environment setup untuk Data Science/AI dengan:
##### ✅ Anaconda
##### ✅ Conda
##### ✅ UV
### 🐍Apa itu ANACONDA???apakah ular anaconda yang di film-film🤔? eisss, no no no...
Anaconda adalah sebuah distribusi open-source dari bahasa pemrograman Python dan R yang dirancang khusus untuk keperluan ilmu data (data science), analisis data, komputasi ilmiah, dan pembelajaran mesin (machine learning).Anaconda adalah paket super lengkap berisi:
1. ✅ Python (bahasa pemrograman)
2. ✅ Ratusan library sains dan data science (seperti numpy, pandas, matplotlib, scikit-learn, tensorflow)
3. ✅ Conda (untuk mengelola environment & package)
4. ✅ Jupyter Notebook (untuk coding interaktif seperti catatan digital)
##### 🎯 Intinya: Begitu kamu install Anaconda, kamu siap tempur untuk coding, analisis data, machine learning, dan visualisasi!
##### 🚀 Bayangkan Ini:
Kamu adalah seorang ilmuwan data pemula.
Kamu install Anaconda, lalu...
##### 🧑‍💻 Buka Jupyter Notebook
##### 📊 Mulai olah data Excel pakai pandas
##### 📈 Bikin grafik interaktif
##### 🧠 Coba algoritma AI
Tanpa ribet install library satu per satu!
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
## Panduan Lengkap untuk Pengaturan Lingkungan Anaconda, Conda, dan UV
### Pendahuluan
##### ❓ Apa itu Panduan Ini?
Panduan ini bakal ngebantu kamu menyiapkan lingkungan kerja Python dengan dua alat keren: Anaconda dan UV.
Anaconda itu semacam “paket komplit” Python yang udah siap pakai untuk data science dan komputasi ilmiah.
Sementara UV adalah alat baru yang super cepat buat ngatur pustaka (library) dan lingkungan virtual—kayak pip, tapi lebih ngebut.
##### ❓ Kenapa Perlu Ini?
Kalau kamu suka coding buat data, AI, atau machine learning, pasti pernah ngalamin error karena pustaka nggak cocok atau versi bentrok. Nah, solusi paling aman adalah pakai lingkungan terpisah buat tiap proyek.
Dengan Anaconda, kamu nggak perlu ribet install satu-satu—semua udah ada. Dan kalau mau yang lebih ringan dan cepat, UV bisa jadi pilihan pas.
Intinya, dengan setup yang rapi, kerjaan kamu jadi lancar, bebas konflik, dan lebih fokus ke ngoding, bukan beresin error.
##### ✅ Do & Don'ts
##### Do:
👍 Ikuti setiap langkah dengan saksama biar setup-nya lancar dan nggak bikin pusing di tengah jalan.
##### Don't:
🚫 Jangan skip bagian verifikasi ya—karena bagian ini penting banget buat ngecek apakah semua udah jalan dengan benar dari awal.
##### Panduan ini bakal ngajarin kamu cara:
Install Anaconda, Atur PATH biar dikenali sistem, Hubungkan ke VS Code, Bikin lingkungan virtual pakai Conda dan UV, Setting Jupyter Notebook, Lihat perbandingan Conda vs UV, Rekomendasi pustaka penting, Dan tips buat ngatasin masalah yang sering muncul
##### 📌 Tutorial ini cocok banget buat pemula, dan fokus utamanya di Windows. Tapi tenang, kalau kamu pakai macOS atau Linux, konsepnya tetap sama—cuma butuh sedikit penyesuaian.
##### ⚠️ Catatan Penting:
Pastikan koneksi internet kamu stabil selama proses instalasi ya. Karena beberapa bagian butuh download file dari internet, jadi biar nggak gagal di tengah jalan.
#### 🐍 1.1 Mengunduh Anaconda
##### Apa sih Anaconda itu?
Anaconda adalah “paket lengkap” Python yang udah dibekali ratusan library buat analisis data, statistik, dan komputasi ilmiah. Jadi, kamu nggak perlu ribet install satu-satu secara manual.
##### Kenapa harus pakai Anaconda?
Dengan install Anaconda, kamu langsung dapet banyak alat penting buat Data Science—kayak Jupyter Notebook, Spyder, dan library populer seperti pandas, numpy, dll.
Jadi lebih hemat waktu dan lebih aman karena semua udah diatur biar kompatibel.
##### Do:
✔️ Pilih Python versi 3.12, karena ini versi terbaru dan paling kompatibel sama banyak pustaka.
##### Don't:
❌ Jangan install versi 32-bit, kecuali laptop kamu memang nggak support 64-bit (rata-rata sih udah support).
##### 🪜 Langkah-langkah Mengunduh:
Buka browser, lalu kunjungi:
##### 1. Download Installer Anaconda
👉 https://www.anaconda.com/download
![Alt](https://github.com/ulanndari/TASK-SETUP-ANACONDA-UV/blob/main/gambar.1.png?raw=true)
##### ✅ Do's:
1. Download langsung dari situs resmi Anaconda 👉 biar aman dan terjamin.
2. Simpan file installernya di folder yang gampang dicari, misalnya di Desktop atau folder Download — jadi nggak ribet pas mau install nanti.
##### ❌ Don’ts:
1. Jangan asal download dari situs lain atau link nggak jelas — bisa aja isinya virus atau installer palsu.
2. Jangan simpan file installer di folder sistem kayak C:\Windows — itu bikin ribet dan kadang butuh izin admin.
##### 🛠️ 2. Jalankan Installer Anaconda
###### Apa sih maksudnya?
Ini adalah proses menginstal Anaconda ke laptop kamu — biar Python dan semua alat bantu data science siap dipakai.
Kenapa perlu install Anaconda?
Karena Anaconda nggak cuma ngasih kamu Python, tapi juga banyak pustaka (library) penting seperti numpy, pandas, matplotlib, bahkan udah termasuk Jupyter Notebook dan Spyder IDE. Jadi kamu nggak perlu install satu-satu lagi. Hemat waktu, hemat tenaga!
##### 🪜 Langkah-langkah Instalasinya:
Klik dua kali file installer Anaconda yang udah kamu download sebelumnya.

Akan muncul wizard instalasi — tinggal klik “Next” beberapa kali.

Saat muncul pilihan:

“Add Anaconda to my PATH environment variable”
kamu boleh centang ini biar Anaconda bisa langsung dikenali lewat Command Prompt.
Tapi kalau kamu pemula dan bingung, boleh juga dilewatin (nggak dicentang). Nanti bisa tetap diakses lewat shortcut.

Klik Install, lalu tunggu prosesnya selesai. Bisa makan waktu beberapa menit tergantung spek laptop kamu.







 



