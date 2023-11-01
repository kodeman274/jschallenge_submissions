# JAVASCRIPT FUNDAMENTALS

<div align="center">
  <img height="60" src="https://img.icons8.com/color/344/javascript.png">
  
   <a href="https://www.jschallenger.com/">https://www.jschallenger.com/</a>
  <h1>JS Submissions Solutions</h1>
</div>

##### 1. Write a function that takes two numbers (a and b) as argument. Sum a and b. Return the result


```javascript
function myFunction(a, b) {
  //code
  return
}
myFunction(1,2) //expected 3
myFunction(1,10) //expected 11
```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(a, b) {
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
##### 8.Tulis fungsi yang menggunakan string sebagai argumen. String berisi substring 'adalah'. Kembalikan indeks 'adalah'.


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
