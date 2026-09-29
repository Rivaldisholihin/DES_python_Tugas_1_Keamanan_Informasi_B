DES menggunakan metode kriptografi kunci simetris dengan algoritma bernama Feistel Cipher. Proses pengacakannya melibatkan beberapa tahapan terstruktur:
1. Konversi ke Biner: Data awal (plaintext) diubah menjadi blok data berukuran 64-bit (deretan angka 0 dan 1).

2. Permutasi Awal (IP): Posisi bit-bit biner tersebut diacak posisinya berdasarkan tabel standar.

3. Proses Feistel (16 Ronde): Blok data dibagi menjadi dua bagian (Kiri dan Kanan). Pada setiap ronde, bagian kanan akan diproses menggunakan fungsi matematika khusus bersama dengan kunci internal (sub-key), lalu di-XOR dengan bagian kiri. Proses ini diulang sebanyak 16 kali.

4. Substitusi (S-Box) & Permutasi (P-Box): Di dalam setiap ronde, terjadi proses substitusi (mengganti nilai bit menggunakan tabel S-Box) dan permutasi (mengacak kembali posisi bit menggunakan P-Box). Ini adalah inti dari pengacakan yang membuatnya sulit ditembus.

5. Permutasi Akhir (FP): Setelah 16 ronde selesai, posisi bit diacak kembali untuk terakhir kalinya sebelum menghasilkan teks Ter Sandi (ciphertext).


alur program : 

<img width="502" height="2052" alt="alur_DES" src="https://github.com/user-attachments/assets/be17ae0d-1cd4-4782-b9a5-e441dc1f920a" />
