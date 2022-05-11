# ObjectDetectionBoundingBox

Jalankan kode program secara berurutan dari file:

1. Image_Collection.ipynb
2. Manual_XML_to_CSV.ipynb
3. Manual_Model_Creation.ipynb

---

## 1. Image_Collection.ipynb

-   Jalankan cell secara berurutan
-   Pada bagian 2, jangan lupa mengubah class sesuai dengan yang dibutuhkan
-   Pada bagian 4, dilakukan capture image dengan menggunakan webcam, dengan waktu yang terbatas. **Dapat diubah pada time.sleep nya**
-   Pada bagian 5 akan dilakukan proses crop yang nantinya akan menghasilkan bounding box. Pada bagian ini akan muncul GUI, pilih direktori file penyimpanan fotonya lalu lakukan crop / sesuaikan bounding box nya dengan **hold w** lalu arahkan pakai mouse. Jika proses crop salah bisa tekan **_esc_**. Setelah proses crop selesai jangan lupa **_ctrl + s_** untuk menyimpan file xml nya.
-   Lalu eksekusi kode seperti biasa
-   Bagian 7 opsional.

## 2. Manual_XML_to_CSV.ipynb

-   Tujuannya untuk mengubah file xml yang barus saja dibuat ke dalam bentuk csv
-   Eksekusi kode seperti biasa

## 3. Manual_Model_Creation.ipynb

-   Tujuannya untuk membuat model machine learning yang mendeteksi "thumbsup", "thumbsdown", dan "jutsu"
-   Model masih overfitting karena sample data sangat sedikit.
-   Eksekusi kode seperti biasa

## 4. Mobilenet_Model_Creation.ipynb

-   Membuat model dari pretrained model dengan mobilenet
-   cara pakainya, setelah ipynb nomor 1 sudah dieksekusi maka bisa jalan (semoga :D) karena ada banyak error di bagian verifikasi

---
