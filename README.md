
# Solidity Development Using Foundry On Kali Linux Virtual Machine

Tutorial ini dibuat untuk menjadi salah satu opsi menggunakan foundry di Sistem Operasi Windows Menggunakan Virtual Box 

# Kebutuhan 
7zip atau Winrar
Install Oracle Virtual Box 
Downnload 
https://download.virtualbox.org/virtualbox/7.1.4/VirtualBox-7.1.4-165100-Win.exe

Download Kali Linux Virtual Box
https://www.kali.org/get-kali/#kali-virtual-machines
Pilih Virtual Box


## Installation
Instal Virtual Box Hingga Selesai
Buka Virtual Box 
Setelah Image Kali Linux Selesai di Download
Extract File Tersebut
Pada Tampilan Awal Virtual Klik "ADD" tombol Berlogo + (plus)
Cari File yang di extract sebelum nya
klik add
Setelah di tambahkan Jalan Virtual Box Tunggu Proses Mengimport OS Kali Linux Hingga Selesai
setelah Selesai masuk Ke OS 
Dengan User kali dan password kali

## Foundry Instalation 
Buka Terminal

ketikan perintah
`` sudo su

masukan password user kali linux anda
`` apt-get update

untuk update repository dari kali linux 
tunggu hingga selesai

`` apt-get install rustup 


`` rustup update stable 


lalu install foundry
To install Foundryup, open your terminal and run the following command:

``curl -L https://foundry.paradigm.xyz | bash

untuk menggunakan foundry 
``mkdir nama-folder
`` cd nama-folder
`` forge init
`` code .

Foundry akan siap digunakan di vscode 



