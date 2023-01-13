# Function / Fungsi

fungsi mempunyai struktur seperti dibawah ini :
```
def functionname( parameters ):
   "function_docstring"
   function_suite
   return [expression]
```

lebih lengkap mengenai function bisa dilihat di tautan berikut https://www.tutorialspoint.com/python/python_functions.htm


contoh fungsi sederhana untuk menjumlahkan parameter `a` dan `b`

```
def tambah(a,b):
    c=a+b
    return c
```

output dari memanggil function diatas kira-kira seperti dibawah ini :
```
print(tambah(9,5))
14
```

---
---

# Latihan Soal
## Soal 1
Buatlah fungsi untuk menghitung berdasarkan 2 parameter:
- Penjumlahan
- Pengurangan
- Perkalian
- Pembagian

## Soal 2
Tampilkan hasil penjumlahan, pengurangan, perkalian dan pembagian yang menggunakan fungsi-fungsi yang sudah dibuat sebelumnya, nilai dari parameter bebas saja untuk antum tentukan sendiri.

## Soal 3
**JUMLAHKAN !** hasil fungsi perkalian dengan hasil fungsi pembagian dan masukkan kedalam variable `x`, lalu tampilkan variable `x` tersebut