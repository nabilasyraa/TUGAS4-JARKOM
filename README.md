Nama : Nabila Asyura Chandra Putri <br>
NIM : 09030582327098 <br>
Kelas : TK4C <br>
Mata Kuliah : Praktikum Jaringan Komputer <br>

# Menghitung parameter QoS (Throughput, Packet Loss, Delay, & Jitter)
## Pada praktikum ini, kita akan melakukan kegiatan anlisisis Quality of Service (QoS) menggunakan Wireshark:
### 1. Pastikan Komputer/Laptop sudah terhubung ke internet.

### 2. Buka aplikasi Wireshark, lalu pilih interface yang terhubung ke internet. 

### 3. Jalankan wireshark untuk melakukan capture packet.

### 4. Selanjutnya, lakukanlah beberapa kegiatan di Komputer/Laptop kalian seperti menonton YouTube, Upload, Download dan kegiatan yang berhubungan dengan internet lainnya selama ±5 menit.

### 5. Jika sudah ±5 menit, selanjutnya stop melakukan capturing packet dengan menekan ikon berbentuk kotak dipojok kiri atas.

### 6. Selajutnya lihat properties dari packet capture yang dilakukan. Dengan menekan Statistics > Caputre File Properties, atau dapat langsung menekan Ctrl+Alt+Shift+C pada keyboard secara bersamaan. 

### 7. Perhatikan bagian Statistics pada halaman Capture File Properties. Pada halaman ini kita dapat melakukan perhitungan Throughput, Packet Loss, Delay, dan Jitter.

### 8. Hitunglah berapa Throughput, Packet Loss, Delay, dan Jitter yang didapatkan dari Statistics Wireshark yang kalian jalankan di Komputer/Laptop masing-masing. Isi lah tabel berikut:
- Throughput

𝑇ℎ𝑟𝑜𝑢𝑔ℎ𝑝𝑢𝑡 (𝐵𝑦𝑡𝑒) 
= 𝑗𝑢𝑚𝑙𝑎ℎ 𝑑𝑎𝑡𝑎 𝑑𝑖𝑘𝑖𝑟𝑖𝑚 (𝐵𝑦𝑡𝑒𝑠)/𝑤𝑎𝑘𝑡𝑢 𝑝𝑒𝑛𝑔𝑖𝑟𝑖𝑚𝑎𝑛 𝑑𝑎𝑡𝑎 (𝑇𝑖𝑚𝑒 𝑠𝑝𝑎𝑛)
= 29,458,057/342.280
= 86,064.20766623817
= 86k

𝑇ℎ𝑟𝑜𝑢𝑔ℎ𝑝𝑢𝑡 (𝐵𝑖𝑡) 
= 𝑇ℎ𝑟𝑜𝑢𝑔ℎ𝑝𝑢𝑡 (𝐵𝑦𝑡𝑒) × 8
= 86,064.20766623817 x 8
= 688.513,6613299053
= 688k

- Packet Loss

𝑃𝑎𝑐𝑘𝑒𝑡 𝐿𝑜𝑠𝑠 
= ((𝑝𝑎𝑐𝑘𝑒𝑡 𝑑𝑎𝑡𝑎 𝑑𝑖𝑘𝑖𝑟𝑖𝑚 −𝑝𝑎𝑐𝑘𝑒𝑡 𝑑𝑎𝑡𝑎 𝑑𝑖𝑡𝑒𝑟𝑖𝑚𝑎)/𝑝𝑎𝑐𝑘𝑒𝑡 𝑑𝑎𝑡𝑎 𝑑𝑖𝑘𝑖𝑟𝑖𝑚 ) × 100
= ((30555−30551)/30555) × 100
= (4/30555) × 100
= 0.000130911 × 100
= 0.0130911
= 0.01%

- Delay

𝐷𝑒𝑙𝑎𝑦 
= 𝑡𝑜𝑡𝑎𝑙 𝑑𝑒𝑙𝑎𝑦/𝑡𝑜𝑡𝑎𝑙 𝑝𝑎𝑐𝑘𝑒𝑡 𝑑𝑖𝑡𝑒𝑟𝑖𝑚a
= 342.279757/30555
= 0.011202087 s

= 0.011202087 s × 1000
= 11.202087 ms

- Jitter

𝐽𝑖𝑡𝑡𝑒𝑟 
= 𝑡𝑜𝑡𝑎𝑙 𝑣𝑎𝑟𝑖𝑎𝑠𝑖 𝑑𝑒𝑙𝑎𝑦/𝑡𝑜𝑡𝑎𝑙 𝑝𝑎𝑐𝑘𝑒𝑡 𝑑𝑖𝑡𝑒𝑟𝑖𝑚𝑎
= 0.021693/30554
= 7.09989E-07 s

= 0.000000709989 s × 1000
= 0.000709989 ms

### 9. Setelah mendapatkan hasil perhitungan Throughput, Packet Loss, Delay, dan Jitter. Selanjutnya isilah tabel indeks yang didapatkan dari pengukuran Quality of Service (QoS):
