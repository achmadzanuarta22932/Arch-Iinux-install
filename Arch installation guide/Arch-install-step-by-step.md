 ini adalah instalasi linux berdasarkan step by step dari wiki , wiki.archlinux.org 

 sebelum memulai harap bagi user pengguna untuk membackup data pada flashdisk yang tersedia karena data akan di partisi   cfdisk - , maka data akan di rewrite atau di tulis ulang yang menyebabkan partisi data dapat berubah maka data di sarankan untuk di backup pada flashdisk yang tersedia 

langkah pertama menginstall arch linux, buka browser archlinux.org dan cari bagian download kemudian, menentukan mirror dari bootsrap agar dapat mem fetch atau mengambil data dari mirror melalui kernel linux. atau meminta teman yang memiliki flashdisk yang memiliki arch-linux di dalamnya 

langkah ke  2 install rufus atau balenaEtcher kemudian run atau jalankan balenaEtcher pada laptop dan cari ; contoh Archlinux12345.ISO, kemudian pilih flashdisk ; contoh sun disk flashdisk 

#setelah pindah dan masuk ke dalam flashdisk, restart laptop dan tekan berulang, f12 untuk masok ke mode looader 
kemudian cari bootloader yang kita butuhkan boot loader tersebut ialah sun disk flash disk 

setelah masuk maka hasil tampilannya adalah tampilan kosong dengan informasi yang tidak seberapa  <img width="768" height="679" alt="image" src="https://github.com/user-attachments/assets/a1a2c30f-2641-4916-b03e-6dc3f90fe6df" />

 setelahnya kamu bisa ketik iwctl untuk mentrigger iwd wifi, device wifi list untuk list ada device apa saja, nanti muncul seperti Wlan0 maka list berhasil selengkapnya seperti ini trigger iwctl kemudian devicce wifi list, 
 outpunya keluar bisa wlan0, setelah ketika station wlan0 scan, outputnya scan wifi di sekitar area, 
 kemudian station wlan0 get-networks, kemudian station wlan0 connect "nama wifi" , kemudian di minta masukan passwordnya 

 kemudian ping google dengan ping google.com , seharusnya muncul ping dengan berkelanjutakn,
 untuk menghentikannya taham ctrl + c 

 update system cloack 
 timedatectl

 
