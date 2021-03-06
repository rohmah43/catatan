# Memahami Cara Kerja Internet

Internet, kependekan dari interconnection-networking, adalah sistem yang berfungsi untuk memindahkan informasi dari satu komputer ke komputer lain menggunakan protokol TCP/IP (aturan dan standar yang dipergunakan antar mesin untuk saling berkomunikasi). 

## IP Address
Misalnya, laptop dan smartphone kamu terhubung dengan Wifi. Wifi terhubung dengan ISP. Dan ISP tersebut terhubung juga dg ISP lain.

Setiap peralatan yang terhubung dengan internet mempunyai alamat yang unik. Alamat tersebut berupa deretan angka, misalnya: Komputer A punya alamat IP 192.168.4.12 dan Laptop B punya alamat IP 192.168.4.13. Dengan alamat inilah mereka saling berkomunikasi.

## DNS
Biasanya orang kesulitan mengingat angka. Dengan DNS (Domain Name Server), angka-angka tersebut, dikaitkan dengan nama-nama yang unik (tidak boleh sama).

Misalnya: 
- google.com mempunyai IP Address: 172.217.194.113.
- yahoo.com mempunyai IP Address: 72.30.35.10

## Contoh kasus
Misalnya komputer kamu (IP Address 192.168.100.2) ingin mengakses http://example.com menggunakan browser, maka DNS server yang terhubung dengan komputer kamu (sebut saja DNS A), akan mencari tahu nama google.com itu terkait dengan IP address berapa. 

Jika belum memiliki datanya, maka DNS A akan bertanya pada DNS server lain (sebut saja DNS B). Ketika DNS B sudah memberikan respon balik, maka DNS A segera mengirimkan jawaban pada komputer kamu, bahwa google.com punya alamat IP 10.10.10.2. Dengan alamat IP inilah komputer kamu terhubung dengan komputer `example.com`.

Komputer kamu via browser lalu meminta `example.com` untuk mengirim sebuah halaman website. Maka server `example.com` pun mengirim data menggunakan bahasa HTTP. 

Secara singkat, data itu kemudian dipecah menjadi paket-paket kecil. Komputer khusus yang disebut router, kemudian memindahkan paket-paket tersebut melalui jalur-jalur yang paling cepat. 

Ketika paket-paket itu sudah sampai ke laptop kita, TCP merakit kembali paket-paket itu menjadi data utuh.

[![Image](https://img.youtube.com/vi/zhlMLRNY5-4/0.jpg)](https://www.youtube.com/watch?v=zhlMLRNY5-4&t=10s)

## Selanjutnya

Berikut ini adalah video yang berisi penjelasan singkat tentang cara kerja internet. Kontributornya berasal dari profesional yang bekerja di perusahaan-perusahaan terkenal.

- [What is the internet?](https://www.youtube.com/watch?v=Dxcc6ycZ73M)
- [The Internet: Wires, Cables & Wifi](https://www.youtube.com/watch?v=ZhEf7e4kopM)
- [The Internet: IP Addresses & DNS](https://www.youtube.com/watch?v=5o8CwafCxnU)
- [The Internet: HTTP & HTML](https://www.youtube.com/watch?v=kBXQZMmiA4s)
- [The Internet: Packets, Routing & Reliability](https://www.youtube.com/watch?v=AYdF7b3nMto)
- [The Internet: How Search Works](https://www.youtube.com/watch?v=LVV_93mBfSU)
- [The Internet: Encryption & Public Keys](https://www.youtube.com/watch?v=ZghMPWGXexs)
- [The Internet: Cybersecurity & Crime](https://www.youtube.com/watch?v=AuYNXgO_f3Y)
- [Images, Pixels and RGB](https://www.youtube.com/watch?v=15aqFQQVBWU)

