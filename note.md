**Cara push ke git**

```bash
git push origin main
```
sesuaikan dengan nama branchnya disini memakai main (disini tuh sudah dibuat reponya dulu)

**Cara pull ke git**

```bash
git pull
```
jika branch cuma satu maka langsung saja, nanti otomatis akan mereplace file lokal dengan yang di remote

**Cara membuat branch**
```bash
git branch nama_branch
```

**Cara pindah branch**
```bash
git checkout nama_branch
```

**Cara membuat dan pindah branch sekaligus**
```bash
git checkout -b nama_branch
```

**Cara merge branch**
```bash
git merge nama_branch
```
pastikan ada di branch yang ingin di yang menjadi wadah merge

**Cara melihat log git**
```bash
git log --oneline --decorate --graph --all
```
akan menampilkan history branch modified dan merge