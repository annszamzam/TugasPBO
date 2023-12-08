# TugasPBO
# 1.Buatlah perulangan hingga 100 menggunakan Python dengan output sebagai berikut:

![alt](https://github.com/annszamzam/TugasPBO/blob/main/1.png?raw=true)
nama = "Annas Zam Zam"

for i in range(1, 101):
    print(i)

    # Cek jika i habis dibagi 10 dan lebih besar dari 1, untuk setiap kelipatan 10 cetak nama
    if i % 10 == 0 and i > 1:
        for _ in range(3):
            print(nama)
# Penjelasan
#kode diatas adalah sebuah program Python yang melakukan perulangan dari 1 hingga 100. Pada setiap iterasi, program memeriksa apakah nilai i habis dibagi 10 dan lebih besar dari 1. Jika kondisi tersebut terpenuhi, program akan mencetak nama "Annas Zam Zam" sebanyak tiga kali.Jadi, secara keseluruhan, program ini mencetak angka dari 1 hingga 100, dan untuk setiap kelipatan 10 (kecuali 10), nama "Annas Zam Zam" dicetak tiga kali.
# 2.Buatlah program bebas, dengan menerapkan if else pada:
 a. For Loops
 ![alt](https://github.com/annszamzam/TugasPBO/blob/main/2.png?raw=true)
  # Program dengan For Loops

  # Menerima input dari pengguna
  n = int(input("Masukkan sebuah angka: "))

  # Menggunakan for loop
  for i in range(n):
    # Cek apakah i habis dibagi 3
    if i % 3 == 0:
        print(f"{i} habis dibagi 3.")
    else:
        print(f"{i} tidak habis dibagi 3.")
# Penjelasan
#Program tersebut digunakan untuk mencetak pesan apakah setiap nilai i dari 0 hingga n-1 habis dibagi 3 atau tidak.Dengan demikian, hasil output dari program ini akan memberikan informasi tentang sisa hasil bagi setiap nilai i dengan 3 dalam rentang dari 0 hingga n-1.
 b. While Loops
# Program dengan While Loops

# Menerima input dari pengguna
n = int(input("Masukkan sebuah angka: "))

# Menggunakan while loop
i = 0
while i < n:
    # Cek apakah i habis dibagi 2
    if i % 2 == 0:
        print(f"{i} habis dibagi 2.")
    else:
        print(f"{i} tidak habis dibagi 2.")
    
    i += 1  # Tingkatkan nilai i untuk menghindari infinite loop
# Penjelasan
#Program tersebut digunakan untuk mencetak pesan apakah setiap nilai i dari 0 hingga n-1 habis dibagi 2 atau tidak menggunakan perulangan while.Dengan demikian, hasil output dari program ini akan memberikan informasi tentang sisa hasil bagi setiap nilai i dengan 2 dalam rentang dari 0 hingga n-1.
# 3.Buatlah sebuah variabel dengan tipe data array, kemudian tampilkan semua nilai dalam variabel tersebut menggunakan perulangan for
# Membuat variabel dengan tipe data array
my_array = [1, 2, 3, 4, 5]

# Menampilkan semua nilai dalam variabel menggunakan perulangan for
for value in my_array:
    print(value)
# Penjelasan 
#di atas, my_array adalah variabel dengan tipe data array yang berisi beberapa nilai. Perulangan for digunakan untuk mengakses setiap nilai dalam array, dan nilai tersebut kemudian dicetak menggunakan pernyataan print(). Hasilnya akan mencetak semua nilai dalam array satu per satu.
