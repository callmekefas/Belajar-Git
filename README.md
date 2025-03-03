Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT
…
//membuat branch
git branch Tugas-git

//masuk ke branch
git checkout Tugas-git

//membuat file dan mengisi dengan teks
echo "halo ini git" > Tugas-git.txt

//menambahkan perubahan pada staging area dan commit
git add Tugas-git
git commit -m "Menambahkan file Tugas-git.txt"

//melakukan merge ke cabang utama
git checkout master
git merge Tugas-git

//Sinkronisasi repo local ke repo remote di GitHub. (git push)
git push -u origin Tugas-git

