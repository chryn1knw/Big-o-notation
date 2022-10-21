# __Notasi Big-O__
1. O(1) — Constant 
Constant Time artinya banyaknya input yang diberikan kepada sebuah algoritma, tidak akan mempengaruhi waktu proses (runtime) dari algoritma tersebut.

2. O(log n) — Logarithmic
 Logarithmic Time artinya ketika kita memberikan input sebesar n terhadap sebuah fungsi, jumlah tahapan yang dilakukan oleh fungsi tersebut berkurang berdasarkan suatu faktor.

3. O(n) — Linear
Linear Time adalah ketika runtime dari fungsi kita berbanding lurus dengan jumlah input yang diberikan.

4. O(n2) — Quadratic
Quadratic Time adalah ketika runtime dari fungsi kita adalah sebesar n2, dimana n adalah jumlah input dari fungsi tersebut.

5. (2n) —Exponential
Exponential Time biasanya digunakan dalam situasi dimana kita tidak terlalu tahu terhadap permasalahan yang dihadapi, sehingga mengharuskan kita mencoba setiap kombinasi dan permutasi dari semua kemungkinan.

## **Contoh Notasi Big-O**
**Linear Time – O(n)**
---
Linear Time adalah ketika runtime dari fungsi kita berbanding lurus dengan jumlah input yang diberikan.
```
for (int i = 0; i < 7 ; i++) 
{
    System.out.println(i);
}
```
```
Output :
0
1
2
3
4
5
6
```
