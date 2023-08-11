# Hapus-File-dan-Folder-Webshell
Membersihkan folder yang sudah kena webshell [403WebShell](https://github.com/yon3zu/403WebShell/tree/main) atau sejenisnya.


1. login SSH
```
ssh -p [port] user@Alamat_IP

```
2. jalankan perintah ini:
```
find . -type d -name kjagffassay44712 -prune -exec rm -rf {} \;
find . -type d -name ccx -prune -exec rm -rf {} \;
```


folder kjagffassay44712 dan ccx adalah folder lokasi webshell, biasanya berulang.


3. cek ulang jika ada file nama  samar yg lain semisal about.php
