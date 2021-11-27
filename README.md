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
1. Melakukan Pembagian Subnet terhadap topologi.
![Perhitungan IP xlsx - Google Spreadsheet and 8 more pages - Personal - Microsoft​ Edge 11_26_2021 12_47_59 PM (2)](https://user-images.githubusercontent.com/68325900/143533230-65745c42-2240-46fd-92fa-3a75b6311bb2.png)

2. Tentukan jumlah alamat IP yang dibutuhkan oleh tiap subnet dan lakukan labeling netmask berdasarkan jumlah IP.
Berdasarkan total IP dan netmask yang dibutuhkan, kita dapat menggunakan netmask /19 untuk memberikan pengalamatan IP pada subnet.  
![Tabel subnet](https://user-images.githubusercontent.com/52129348/143670721-da130247-709b-4bab-b73a-51a5d4dec226.png)  

3. Subnet besar yang dibentuk memiliki NID 10.17.0.0 dengan netmask /19. Hitung pembagian IP berdasarkan NID dan netmask menggunakan pohon subnet.
![1uBgkV-y1GKoTchP0tccAEdidXU2SGKY7fCyf2GR9](https://user-images.githubusercontent.com/68325900/143534581-1778cb01-d9f4-4199-82c5-d88a8f0f63c7.jpg)

4. Dari pohon subnet tersebut, akan mendapat pembagian IP sebagai berikut:
![Meet - jnz-ggzc-bpx - Google Chrome 11_26_2021 1_07_55 PM (2)](https://user-images.githubusercontent.com/68325900/143535045-285f6e33-8db2-42be-ac05-87a0cb8eaa39.png)

### Hasil
![SS PKT VLSM](https://user-images.githubusercontent.com/52129348/143670777-0a285924-c1e5-4c36-9814-c21e30442aac.png)  
![SS VLSM Route Check](https://user-images.githubusercontent.com/52129348/143670786-19622d5c-b7fc-4973-8de4-29a99c642cff.png)
[Link Video Pengecekan Rute](https://www.youtube.com/watch?v=VQ4zUI2XL3o)

## Perhitungan CIDR
1. Melakukan Pembagian Subnet terhadap topologi.
![subnetting](https://user-images.githubusercontent.com/55136116/143671389-4c932f60-5645-40c0-a8d8-4cb348d669c1.jpg)

2. Tentukan jumlah alamat IP yang dibutuhkan oleh tiap subnet dan lakukan labelling netmask berdasarkan jumlah IP.
![akhir](https://user-images.githubusercontent.com/55136116/143684441-8e57dd0a-0d2b-4c69-92f8-1695c8797454.jpg)
![image](https://user-images.githubusercontent.com/55136116/143671504-710ece8e-74be-4e5b-be69-471ad86098b8.png)

3. Subnet besar yang dibentuk memiliki NID 10.17.0.0 dengan netmask /16. Hitung pembagian IP berdasarkan NID dan netmask menggunakan pohon subnet
![Untitled](https://user-images.githubusercontent.com/55136116/143671430-cbe5bd4e-9a91-4b52-bec8-ab58592954c7.jpg)

4. Dari pohon subnet tersebut, akan mendapat pembagian IP sebagai berikut:
![image](https://user-images.githubusercontent.com/55136116/143671456-9368e8ce-576a-4c1a-bd90-a674f9957c5b.png)

## Kendala
* Kesulitan saat menentukan static routing yang tepat di bagian VLSM.
* Gagal saat melakukan ping dan routing pada gns.
