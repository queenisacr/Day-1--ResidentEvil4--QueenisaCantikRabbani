# Dokumentasi Workshop: Building with AI, Managing Change with GitHub # 

Pemateri:Nugi Farhan(Senior Product Designer)

## A. Materi/Topik yang dibahas hari ini.
1. Prompt engineering = membuat dan mengembangkan sesuatu dengan AI
2. Git dan GitHub = manajemen perubahan dan kolaborasi
3. Setup git, VS code, dan SSH Key
4. Praktik = membuat Student Task Planner dan belajar mengunggahnya ke github.
6. Menjelaskan bagaimana prompt AI yang lebih spesifik menghasilkan hasil yang lebih baik.
7. Membedakan Git dan GitHub.
8. Mengidentifikasi repository, commit, branch, dan pull request.
9. Melakukan version controlling.

## B. Catatan/rangkuman materi hari ini ##
- Prompt adalah instruksi atau masukan yang diberikan ke model ai untuk mendapatkan hasil tertentu. Bentuknya bisa pertanyaan, kata kunci, instruksi rumit, atau potongan kode.
- Prompt engineering adalah cara merancang instruksi agar ai memberi jawaban yang tepat, relevan, dan layak digunakan.
- Context is key =  prompt "Create student task planner" menghasilkan jawaban yang umum, sedangkan prompt dengan konteks lengkap menghasilkan hasil yang jauh lebih sesuai yang kita inginkan.
- Struktur prompt yang baik = Role, Task, Context, Format.
- Taktik prompt = gunakan kata kerja yang jelas, tentukan panjang dan format output, tentukan target audiens, sertakan fakta dan data relevan, rujuk sumber/dokumen tertentu, dan definisikan istilah penting.
- Keuntungan = meningkatkan performa model, mengurangi bias dan respons yang offensive, meningkatkan kontrol dan predictability, serta pengalaman pengguna yang lebih baik.
# Tentang Git dan Github #
- Git adalah distributed version control system(DVCS) yang melacak siapa, kapan, dan apa yang diubah pada suatu file. Dibuat oleh Linus Torvalds pada tahun 2005.
Alur kerja Git:
  - Working directory: salinan satu versi proyek yang sedang dikerjakan.
  - Staging area (index): menyimpan informasi perubahan yang akan masuk ke commit berikutnya.
  - git directory (repository): tempat Git menyimpan metadata dan database objek proyek.

Git vs GitHub
Git : Sistem version control terdistribusi untuk melacak dan mengelola perubahan kode secara lokal 
GitHub :  Platform berbasis web untuk menyimpan repository Git secara online dan mendukung kolaborasi.

Perintah Git penting
git init=Memulai repository baru 
git add=Memindahkan file ke staging area
git commit -m "pesan" = Menyimpan perubahan ke repository 
git remote add <nama> <url>= menghubungkan repository lokal ke remote 
git push origin main  = Mengirim perubahan ke GitHub
git pull origin main = Mengambil dan menggabungkan perubahan dari GitHub 
git clone "url" = Menyalin repository dari GitHuInstall Git, cek dengan git --version
-Atur identitas: git config --global user.name dan user.email
Install VS Code dan cek dengan code --version
Buat SSH key dengan ssh-keygen -t ed25519 , tambahkan ke GitHub, lalu verifikasi dengan ssh -T git@github.com

## poin poin
- Prompt yang spesifik dan berkonteks menghasilkan jawaban AI yang lebih baik.
- Git bekerja secara lokal, sedangkan GitHub adalah tempat menyimpan dan berkolaborasi secara online.
- Staging area memungkinkan kita memilih perubahan mana yang masuk ke commit.
- SSH key membuat koneksi ke GitHub aman tanpa perlu memasukkan password setiap kali.