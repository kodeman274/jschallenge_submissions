# JAVASCRIPT FUNDAMENTALS

<div align="center">
  <img height="60" src="https://img.icons8.com/color/344/javascript.png">
  
   <a href="https://www.jschallenger.com/">https://www.jschallenger.com/</a>
  <h1>JS Submissions Solutions</h1>
</div>

##### 1. Tulislah fungsi yang menggunakan dua bilangan (a dan b) sebagai argumen. Jumlahkan a dan b. Kembalikan hasilnya


```javascript
function myFunction(a,b) {
  //code
  return
}
myFunction(1,2) //expected 3
myFunction(1,10) //expected 11
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a,b) {
  return a + b;
}
console.log(myFunction(1,10));
```

</details>

---
##### 2. Tulis fungsi yang mengambil dua nilai, katakanlah a dan b, sebagai argumen. Mengembalikan nilai benar jika kedua nilai sama dan bertipe sama


```javascript
function myFunction(a, b) {
  //code
  return
}
myFunction(2,3) //expected false
myFunction(3,3) //expected true
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a, b) {
  return a === b;
}
console.log(myFunction(3,3));
```

</details>

---
##### 3. Tulis fungsi yang mengambil nilai sebagai argumen. Kembalikan jenis nilainya.


```javascript
function myFunction(a) {
  //code
  return
}
myFunction(1) //expected number
myFunction(false) //expected boolean
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a) {
  return typeof a;
}
console.log(myFunction(true));
```

</details>

---
##### 4. Tulis fungsi yang menggunakan string (a) dan angka (n) sebagai argumen. Kembalikan karakter ke-n dari 'a'.


```javascript
function myFunction(a, n) {
  //code
  return
}
myFunction('abcd') //expected 'a'
myFunction('zyxbwpl') //expected 'w'
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a, n) {
  return a[n-1];
}
console.log(myFunction('abcd'));
```

</details>

---
##### 5. Tulis fungsi yang menggunakan string (a) sebagai argumen. Hapus 3 karakter pertama dari a. Kembalikan hasilnya


```javascript
function myFunction(a) {
  //code
  return
}
myFunction('abcdefg') //expected 'defg'
myFunction('1234') //expected '4'
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a) {
  return a.slice(3)
}
console.log(myFunction('abcdefg'));
```

</details>

---
##### 6.Tulis fungsi yang menggunakan string sebagai argumen. Ekstrak 3 karakter terakhir dari string. Kembalikan hasilnya


```javascript
function myFunction(str) {
  //code
  return
}
myFunction('abcdefg') //expected 'efg'
myFunction('1234') //expected '4'
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(str) {
  return str.slice(-3)
}
console.log(myFunction('abcdefg'));
```

</details>

---
##### 7.Tulis fungsi yang menggunakan string (a) sebagai argumen. Dapatkan 3 karakter pertama dari a. Kembalikan hasilnya


```javascript
function myFunction(a) {
  //code
  return
}
myFunction('abcdefg') //expected 'abc'
myFunction('1234') //expected '123'
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a) {
  return a.slice(0, 3)
}
console.log(myFunction('abcdefg'));
```

</details>

---
##### 8.Tulis fungsi yang menggunakan string sebagai argumen. String berisi substring 'is'. Kembalikan indeks 'is'.


```javascript
function myFunction(a) {
  //code
  return
}
myFunction('praise') //expected '3'
myFunction('risky') //expected '1'
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a) {
 return a.indexOf('is');

}
console.log(myFunction('praise'));
```

</details>

---
##### 9.Tulis fungsi yang menggunakan string (a) sebagai argumen. Ekstrak bagian pertama a. Kembalikan hasilnya


```javascript
function myFunction(a) {
  //code
  return
}
myFunction('abcdefgh') //expected 'abcd'
myFunction('1234') //expected '12'
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a) {
 return a.slice(0, a.length / 2)

}
console.log(myFunction('abcdefgh'));
```

</details>

---
##### 10.Tulis fungsi yang menggunakan string (a) sebagai argumen. Hapus 3 karakter terakhir dari a. Kembalikan hasilnya


```javascript
function myFunction(a) {
  //code
  return
}
myFunction('abcdefgh') //expected 'abcd'
myFunction('1234') //expected '1'
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a) {
 return a.slice(0, a.length -3)

}
console.log(myFunction('abcdefgh'));
```

</details>

---

##### 11.Tulislah fungsi yang menggunakan dua bilangan (a dan b) sebagai argumen. Kembalikan b persen dari a


```javascript
function myFunction(a, b) {
  //code
  return
}
myFunction(100, 50) //expected 50
myFunction(10 ,1) //expected 0,1
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a, b) {
 return ( a * b) / 100;

}
console.log(myFunction(100, 50));
```

</details>

---
##### 12.Tulis fungsi yang mengambil 6 nilai (a,b,c,d,e,f) sebagai argumen. Jumlah a dan b. Kemudian kurangi dengan c. Kemudian kalikan dengan d dan bagi dengan e. Terakhir, naikkan ke pangkat f dan kembalikan hasilnya. 


```javascript
function myFunction(a,b,c,d,e,f) {
  //code
  return
}
myFunction(6,5,4,3,2,1) //expected 10.5
myFunction(6,2,1,4,2,3) //expected 2744
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a,b,c,d,e,f) {
  return (((a + b - c) * d) / e) ** f;


}
console.log(myFunction(6,2,1,4,2,3))
```

</details>

---
##### 13.Tulis fungsi yang menggunakan dua string (a dan b) sebagai argumen. Jika a berisi b, tambahkan b ke awal a. Jika tidak, tambahkan sampai akhir. Kembalikan rangkaiannya


```javascript
function myFunction(a, b) {
  //code
  return 
}
myFunction('cheese', 'cake') //expected 'cheesecake'
myFunction('lips','s') //expected 'slips'
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a, b) {
  return a.includes(b) ? b + a : a + b

}
console.log(myFunction('cheese', 'cake'));
```

</details>

---
##### 14.Tulis fungsi yang menggunakan angka sebagai argumen. Jika angkanya genap, kembalikan nilai true. Jika tidak, kembalikan salah


```javascript
function myFunction(a) {
  //code
  return 
}
myFunction(10) //expected true
myFunction(-4) //expected false
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a) {
  return a % 2 === 0;

}
console.log(myFunction(10);
```

</details>

---
##### 15.Tulis fungsi yang menggunakan dua string (a dan b) sebagai argumen. Mengembalikan berapa kali a muncul di b.


```javascript
function myFunction(a, b) {
  //code
  return 
}
myFunction('m', 'how many times does the character occur in this sentence?') //expected 2
myFunction('h', 'how many times does the character occur in this sentence?') //expected 4
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a, b) {
  return b.split(a).length - 1

}
console.log(myFunction('m', 'how many times does the character occur in this sentence?'))

```

</details>

---
##### 16.Tulislah fungsi yang menggunakan angka (a) sebagai argumen. Jika a adalah bilangan bulat (tidak memiliki tempat desimal), hasilnya benar. Jika tidak, kembalikan salah.

```javascript
function myFunction(a) {
  //code
  return 
}
myFunction(4)  //expected true
myFunction(0.5)  //expected false
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a) {
  return a === Math.floor(a)
}
console.log(myFunction(4))

```

</details>

---
##### 17.Tulislah fungsi yang menggunakan dua bilangan (a dan b) sebagai argumen. Jika a lebih kecil dari b, bagilah a dengan b. Jika tidak, kalikan kedua angka tersebut. Kembalikan nilai yang dihasilkan

```javascript
function myFunction(a,b) {
  //code
  return 
}
myFunction(10, 100)  //expected 0.1
myFunction(90.45)  //expected 4050
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a, b) {
    return a < b ? a / b : a * b

}
console.log(myFunction(10, 100))

```

</details>

---
##### 18.Tulislah fungsi yang menggunakan angka (a) sebagai argumen. Bulatkan a sampai angka ke-2 setelah koma. Kembalikan angka yang dibulatkan

```javascript
function myFunction(a) {
  //code
  return 
}
myFunction(2.12397) //expected 2.12
myFunction(3.136)  //expected 3.14
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a) {
    return Number(a.toFixed(2))

}
console.log(myFunction(2.12397))

```

</details>

---
##### 19.Tulislah fungsi yang menggunakan angka (a) sebagai argumen. Pisahkan a menjadi masing-masing digit dan kembalikan dalam array.

```javascript
function myFunction(a) {
  //code
  return 
}
myFunction(10) //expected [1,0]
myFunction(931)  //expected [9,3,1]
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a) {
    return a.toString().split('').map((digit) => Number(digit))

}
console.log(myFunction(10))

```

</details>

---
