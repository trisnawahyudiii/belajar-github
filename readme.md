# Alur Kerja Git

1. Git init - inisiasi git dalam folder 
```bash
git init
```

2. buat file html
```
touch index.html
```

3. cek perubahan dengan git status
```
git status
```
4. pindahkan perubahan ke staging area
```bash
git add <nama file>
atau
git add .
```
5. commit perubahan 
```bash 
git commit -m "<pesan commit disini>"
```
6. tambahkan remote repository
```bash
git remote add origin https://github.com/trisnawahyudiii/belajar-github.git
```
7. push ke repository
```
git push <nama remote repository> <nama branch yang akan di push>
```
