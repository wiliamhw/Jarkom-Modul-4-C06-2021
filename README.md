# Jarkom-Modul4-C06-2021

## Anggota Kelompok : 
- 05111940000004 | Nizar Mayraldo
- 05111940000087 | William Handi Wijaya
- 05111940000202 | Muhammad Naufaldillah

## Subnetting dan Routing
![messageImage_1637604249670](https://user-images.githubusercontent.com/68325900/143531414-9f16b6ac-a0df-47d9-8f12-4e4c55758e8a.jpg)
Topologi telah ditentukan, dilakukan perhitungan pembagian subnet dengan metode **Classless** yaitu:
- Metode **VLSM (Variable Length Subnet Masking)** di Cisco Packet Tracer
- Metode **CIDR (Clasless Inter Domain Routing)** di GNS3

## Perhitungan VLSM
- Melakukan Pembagian Subnet terhadap topologi.
![Perhitungan IP xlsx - Google Spreadsheet and 8 more pages - Personal - Microsoft​ Edge 11_26_2021 12_47_59 PM (2)](https://user-images.githubusercontent.com/68325900/143533230-65745c42-2240-46fd-92fa-3a75b6311bb2.png)

- Tentukan jumlah alamat IP yang dibutuhkan oleh tiap subnet dan lakukan labelling netmask berdasarkan jumlah IP.
![Captures 11_26_2021 12_58_22 PM (2)](https://user-images.githubusercontent.com/68325900/143534103-0f0e302f-e001-48d0-9534-edec644d5e64.png)
Berdasarkan total IP dan netmask yang dibutuhkan, kita dapat menggunakan netmask /19 untuk memberikan pengalamatan IP pada subnet

- Subnet besar yang dibentuk memiliki NID 10.17.0.0 dengan netmask /19. Hitung pembagian IP berdasarkan NID dan netmask menggunakan pohon subnet.
![1uBgkV-y1GKoTchP0tccAEdidXU2SGKY7fCyf2GR9](https://user-images.githubusercontent.com/68325900/143534581-1778cb01-d9f4-4199-82c5-d88a8f0f63c7.jpg)
Dari pohon subnet tersebut, akan mendapat pembagian IP sebagai berikut:
![Meet - jnz-ggzc-bpx - Google Chrome 11_26_2021 1_07_55 PM (2)](https://user-images.githubusercontent.com/68325900/143535045-285f6e33-8db2-42be-ac05-87a0cb8eaa39.png)


## Perhitungan CIDR
- Melakukan Pembagian Subnet terhadap topologi.

- Tentukan jumlah alamat IP yang dibutuhkan oleh tiap subnet dan lakukan labelling netmask berdasarkan jumlah IP.

Dari pohon subnet tersebut, akan mendapat pembagian IP sebagai berikut:
