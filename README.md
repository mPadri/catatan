### Dasar-dasar GIT

#### Membuat Repository Baru
- buat repo baru pada halaman github
- copy link pada https yang ada pada tombol "clone or download" berwarna hijau
- buka terminal arahkan path ke tempat dimana ingin menyimpan repo
- ketik git clone `https://github.com/namauser/namarepo.git`
- ketik git remote -v `untuk cek nama remote`
- cd namarepo untuk masuk ke folder tersebut
- buka folder tersebut di text editor dan buat file baru `README.md` atau jika sudah ada bisa di edit tulisannya dengan apapun lalu save
- kembali ke terminal lagi
- ketik git add .
- ketik git commit -m "isi catatan bebas"
- ketik git push `<nama remote> <nama branch>`
> contoh : git push origin master
> note: default branch master

*selesai...*

#### Cara buat branch

> git branch `<nama branch>`
> git checkout `<nama branch>` >> "*pindah branch*" 

*atau*

> git checkout -b `<nama branch>` >> "*membuat dan pindah branch*"

#### Cara melihat daftar branch
> git branch >> "*nama yang ada tanda * tempat kita berada*"

#### Cek status remote
> git remote -v
#### Cara add dan delete remote
> git remote add `<nama remote>` `<link repository>` >> *tambah remote*

> git remote rm `<nama remote>` >> *hapus remote*