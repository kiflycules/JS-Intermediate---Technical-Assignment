# Jawaban GitHub Lanjutan 
> 24 Februari 2022

1. What is the difference between git reset and git revert. When would you use one over the other?
    - Perintah git reset sering disebut sebagai perintah berbahaya yang dapat menghancurkan catatan sejarah perubahan.
Hati-hati! Perintah ini membuat kita tidak bisa kembali lagi ke masa depan. Mau tidak mau, kita harus menulis ulang sejarah.
    - Revert akan akan mengambil kondisi file yang ada di masa lalu, kemudian menggabungkannya dengan commit terakhir.


2. What is the difference between git merge and git rebase. When would you use one over the other?
    - rebase "menerapkan kembali komit di atas cabang basis lain". menulis ulang
    - merge "menggabungkan dua atau lebih sejarah pengembangan bersama-sama". sementara penggabungan mempertahankan sejarah saat itu terjadi


3. What is the difference between git stash pop and git stash apply. When would you use one over the other?
    - git stash pop membuang simpanan (paling atas, secara default) setelah menerapkannya
    - git stash apply meninggalkannya di daftar simpanan untuk kemungkinan digunakan kembali nanti (atau Anda kemudian dapat git stash menjatuhkannya).


4. What kinds of things can you do in interactive mode when rebasing?
    - Rebasing interaktif dapat digunakan untuk mengubah komit dalam banyak cara seperti mengedit, menghapus, dan meremas. Untuk memberi tahu Git tempat memulai rebase interaktif, gunakan SHA-1 atau indeks komit yang segera mendahului komit yang ingin Anda ubah.