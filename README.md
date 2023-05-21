# TriangleChainChipperAlgorithm
Berikut adalah contoh perhitungan secara manual dengan menggunakan rumus algoritma Triangle Chain Cipher:

--- RUMUS = (n * (n + 1)) / 2 ---

Misalkan kita ingin mengenkripsi teks "hello" menggunakan metode Triangle Chain Cipher.

Pertama, kita akan mengubah setiap huruf menjadi posisi dalam alfabet (dimulai dari 0):

'h' menjadi 7
'e' menjadi 4
'l' menjadi 11
'l' menjadi 11
'o' menjadi 14
Selanjutnya, kita akan menerapkan rumus (n * (n + 1)) / 2 pada setiap posisi:

7 * (7 + 1) / 2 = 28
4 * (4 + 1) / 2 = 10
11 * (11 + 1) / 2 = 66
11 * (11 + 1) / 2 = 66
14 * (14 + 1) / 2 = 105
Kemudian, kita akan mengubah setiap posisi yang dihasilkan menjadi huruf dengan mengonversi kembali ke alfabet (mod 26):

28 % 26 = 2, sehingga menjadi huruf 'c'
10 % 26 = 10, sehingga tetap menjadi huruf 'k'
66 % 26 = 14, sehingga menjadi huruf 'o'
66 % 26 = 14, sehingga menjadi huruf 'o'
105 % 26 = 1, sehingga menjadi huruf 'b'
Jadi, hasil enkripsi dari teks "hello" menggunakan metode Triangle Chain Cipher adalah "ckoob".
