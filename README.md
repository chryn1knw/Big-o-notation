# Sekilas Tentang Notasi O Besar
Big-O Notation adalah cara untuk mengkonversi keseluruhan langkah-langkah suatu algoritma kedalam bentuk Aljabar, yaitu dengan menghiraukan konstanta yang lebih kecil dan koefisien yang tidak berdampak besar terhadap keseluruhan kompleksitas permasalahan yang diselesaikan oleh algoritma tersebut.Big-O Notation juga sebuah cara atau metode untuk melakukan analisa terhadap sebuah algoritma pemrograman terhadap waktu eksekusi. Tentang seberapa efisien dan kompleksitas barisan kode dalam dimensi waktu.
# **Big O Notation**
1.Constant - O(1)
---
Constant artinya banyaknya input yang diberikan kepada sebuah algoritma, tidak akan mempengaruhi waktu proses (runtime) dari algoritma tersebut.
```
int n = 10;
System.out.println( n);
```
```
Output :
10
```
2.Logarithmic - O(log n)
---
Logarithmic  artinya ketika kita memberikan input sebesar n terhadap sebuah fungsi, jumlah tahapan yang dilakukan oleh fungsi tersebut berkurang berdasarkan suatu faktor.
```
for (int i = 1; i < 10; i = i * 2){
    System.out.println(i);
}
```
```
Output :
1
2
3
4
8
```
3.Linear – O(n)
---
Linear  adalah ketika runtime dari fungsi kita berbanding lurus dengan jumlah input yang diberikan.
```
for (int i = 0; i < 7 ; i++) 
{
    System.out.println(i);
}
```
```
Output :
1
2
3
4
5
6
```
4.Polynomial - O(n2)
---
Polynomial/Quadratic adalah ketika runtime dari fungsi kita adalah sebesar n2, dimana n adalah jumlah input dari fungsi tersebut.
```
for (int i = 1; i <= 2; i++) {
    for(int j = 1; j <= 4; j++) {
        System.out.println(i + " dan " + j);
    }
}
```
```
Output :
1 dan 1
1 dan 2
1 dan 3
1 dan 4
2 dan 1
2 dan 2
2 dan 3
2 dan 4
```
5.Exponential - O(2^n)
---
Exponential biasanya digunakan dalam situasi dimana kita tidak terlalu tahu terhadap permasalahan yang dihadapi, sehingga mengharuskan kita mencoba setiap kombinasi dan permutasi dari semua kemungkinan.
```
for (int i = 1; i <= Math.pow(2, 4); i++){
    System.out.println(i);
}
```
```
Output :
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
```
