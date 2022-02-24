# Jawabanya

> 24 Februari 2022

1. Fork repository GitHub https://github.com/impactbyte/tech4impact-students-bio.git menggunakan akun Github kamu
    - [Link Fork github](https://drive.google.com/drive/folders/1eeNzWeaU8dBxzxfJ5pDOiU7B7sHHgqVC)

2. Clone remote repository dari hasil fork tersebut. Jangan clone dari repository originalnya.
    - [Link clone remote](https://drive.google.com/drive/folders/1eeNzWeaU8dBxzxfJ5pDOiU7B7sHHgqVC)

3. Buatlah branch baru dengan nama lengkap kamu. Misalnya david-winalda. Jangan melakukan perubahan pada branch master.
    - git branch m-zulkifli

4. Checkout ke dalam branch tersebut yang telah kamu buat
    - git checkout m-zulkifli

5. Buatlah 1 file format .md dengan nama lengkap kamu. Contoh davidwinalda.md
    - touch mzulkifli.md

6. Isi file tersebut davidwinalda.md dengan konten di bawah ini:

Nama Lengkap: David Winalda
Umur: 27
Pesan yang ingin disampaikan: Semangat untuk kamu yang disana sedang berjuang

- [link pengisian dengan nano](https://drive.google.com/drive/folders/1eeNzWeaU8dBxzxfJ5pDOiU7B7sHHgqVC)


7. Masukkan file .md tersebut ke dalam staging area
    - git add mzulkifli.md


8. Commit dengan memberikan pesan nama file .md kamu
    - git commit -m " add mzulkifli.md file"
    - git push origin m-zulkifli ---> agar branch muncul di github sebelum di merge/di gabungkan dengan branch master

9. Merge branch yang telah kamu buat ke dalam branch master
    - git merge m-zulkifli

10. Push ke dalam branch master
    - git push origin master

11. Lakukan pull request dari GitHub Repository yang telah kamu fork untuk digabungkan ke dalam branch master pada GitHub Repository aslinya.
    - [link full req](https://drive.google.com/drive/folders/1eeNzWeaU8dBxzxfJ5pDOiU7B7sHHgqVC)