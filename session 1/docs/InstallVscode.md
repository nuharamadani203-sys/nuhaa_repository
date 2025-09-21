# Cara Instal Vscode
## 1. Buka Firefox
Cari panduan instalasi VSCode

## 2. Perbarui Sistem
Buka **Terminal**, lalu salin dan tempel perintah berikut untuk memperbarui paket sistem.
*sudo apt update* dan *sudo apt upgrade -y* Kemudian klik enter dan masukkan password jika diminta 

## 3. Install Dependensi
Salin perintah ini: *sudo apt install software-properties-common apt-transport-https wget -y*, lalu tempel di **Terminal** dengan klik **Ctrl+Shift+V** 

## 4. Tambahkan Kunci Repository
Salin perintah ini: *wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -*, kemudian tempel di **Terminal** dengan klik **Ctrl+Shift+V** 

## 5. Tambahkan Repository VSCode
Salin perintah ini: *sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"*, dan tempel di **Terminal** dengan klik **Ctrl+Shift+V** untuk menambahkan repository VSCode ke sistem

## 6. Perbarui Daftar Paket
Salin perintah ini: *sudo apt update* dan tempel di **Terminal** dengan **Ctrl+Shift+V** untuk memperbarui daftar paket.

## 7. Instal VSCode
Terakhir, salin perintah ini: *sudo apt install code* dan tempel di **Terminal** dengan **Ctrl+Shift+V** untuk memulai instalasi VSCode

## 8. Jalankan VSCode
Setelah instalasi selesai, ketik *code* di **Terminal** lalu klik enter untuk membuka aplikasi VSCode


note: *Jika ada pilihan y/n maka ketik y lalu klik enter*