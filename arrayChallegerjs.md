# JAVASCRIPT ARRAY

<div align="center">
  <img height="60" src="https://img.icons8.com/color/344/javascript.png">
  
   <a href="https://www.jschallenger.com/">https://www.jschallenger.com/</a>
  <h1>JS Submissions Solutions</h1>
</div>

##### 1. Tulis fungsi yang menggunakan array (a) dan nilai (n) sebagai argumen. Kembalikan elemen ke-n dari 'a'


```javascript
function myFunction(a, n) {
  //code
  return
}
myFunction([1,2,3,4,5],3) //expected 3
myFunction([10,9,8,7,6],5) //expected 6
```

<details><summary><b>Solution</b></summary>

```javascript

function myFunction(a,n) {
 return n >= 1 && n <= a.length ? a [n-1] : undefined;

// cara sederhana
return a[n-1]
  return
}

console.log(myFunction([1,2,3,4,5],3);
```

</details>

---

</details>

##### 2.Tulis fungsi yang menggunakan array (a) sebagai argumen. Hapus 3 elemen pertama 'a'. Kembalikan hasilnya


```javascript
function myFunction(a) {
  //code
  return
}
myFunction([1,2,3,4]) //expected 4
myFunction([10,9,8,7]) //expected 7
```

<details><summary><b>Solution</b></summary>

```javascript

function myFunction(a) {
    return a.slice(3);
}

console.log(myFunction([1,2,3,4]))
```

</details>

---
##### 3.Tulis fungsi yang menggunakan array (a) sebagai argumen. Ekstrak 3 elemen terakhir 'a'. Kembalikan array yang dihasilkan

```javascript
function myFunction(a) {
  //code
  return
}
myFunction([1,2,3,4]) //expected [2,3,4]
myFunction([10,9,8,7]) //expected [9,8,7]
```

<details><summary><b>Solution</b></summary>

```javascript

function myFunction(a) {
  return a.slice(-3);

}

console.log(myFunction([1,2,3,4]))
```

</details>

---
##### 4.Tulis fungsi yang menggunakan array (a) sebagai argumen. Ekstrak 3 elemen pertama 'a'. Kembalikan array yang dihasilkan

```javascript
function myFunction(a) {
  //code
  return
}
myFunction([1,2,3,4]) //expected [1,2,3]
myFunction([10,9,8,7]) //expected [10,9,8]
```

<details><summary><b>Solution</b></summary>

```javascript

function myFunction(a) {
  return a.slice(0,3);

}

console.log(myFunction([1,2,3,4]))
```

</details>

---
##### 5.Tulis fungsi yang menggunakan array (a) dan angka (n) sebagai argumen. Ini harus mengembalikan n elemen terakhir dari a.

```javascript
function myFunction(a,n){
  //code
  return
}
myFunction([1, 2, 3, 4, 5], 2) //expected [4,5]
myFunction([1, 2, 3], 6) //expected [ 1, 2, 3 ]

```

<details><summary><b>Solution</b></summary>

```javascript

function myFunction(a,n) {
  return n >= a.length ? a : a.slice(-n)

}
// cara sederhana
return a.slice(-n)

console.log(myFunction([1,2,3,4]))
```

</details>

##### 6.Tulis fungsi yang menggunakan array (a) dan nilai (b) sebagai argumen. Fungsi tersebut harus menghapus semua elemen yang sama dengan 'b' dari array. Kembalikan array yang difilter.

```javascript
function myFunction(a,b){
  //code
  return
}
myFunction([1, 2, 3, ], 2) //expected [1,3[
myFunction([1, 2, '2'],'2') //expected [ 1, 2[

```

<details><summary><b>Solution</b></summary>

```javascript

function myFunction(a,b) {
  return a.filter((el) => el !== b)

}

console.log(myFunction([1, 2, '2'],'2'))
```

</details>

---
##### 7.Tulis fungsi yang menggunakan array (a) sebagai argumen. Mengembalikan jumlah elemen dalam a.

```javascript
function myFunction(a){
  //code
  return
}
myFunction([1,2,2,4]) //expected 4
myFunction([1,2,2,4]) //expected 3

```

<details><summary><b>Solution</b></summary>

```javascript

function myFunction(a) {
   return a.length;

}

console.log(myFunction([1,2,2,4]))
```

</details>

---
##### 8.Tulis fungsi yang menggunakan array angka sebagai argumen. Mengembalikan jumlah nilai negatif dalam array.

```javascript
function myFunction(a){
  //code
  return
}
myFunction([1,-2,2,-4]) //expected 2
myFunction([0,9,1]) //expected 0

```

<details><summary><b>Solution</b></summary>

```javascript

function myFunction(a) {
 let count = 0;
  for (let i = 0; i < a.length; i++) {
    if (a[i] < 0) {
      count++;
    }
  }
  return count;

}
//cara sederhana
   return a.filter((el) => el < 0).length;


console.log(myFunction([1,-2,2,-4]))
```

</details>

---
##### 9.Tulis fungsi yang menggunakan array string sebagai argumen. Urutkan elemen array berdasarkan abjad. Kembalikan hasilnya.

```javascript
function myFunction(arr){
  //code
  return
}
myFunction(['b', 'c', 'd', 'a']) //expected ['a', 'b', 'c', 'd']
myFunction(['z', 'c', 'd', 'a', 'y', 'a', 'w']) //expected ['a', 'a', 'c', 'd', 'w', 'y', 'z']


```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(arr) {
  return arr.sort()

}

console.log(myFunction(['b', 'c', 'd', 'a'])
```

</details>

---
##### 10.Tulis fungsi yang menggunakan array angka sebagai argumen. Ini harus mengembalikan array dengan angka-angka yang diurutkan dalam urutan menurun.


```javascript
function myFunction(arr){
  //code
  return
}
myFunction([1,3,2]) //expected [3,2,1]
myFunction([4,2,3,1]) //expected [4,3,2,1]

```

<details><summary><b>Solution</b></summary>

```javascript
function myFunction(arr) {
  return arr.sort(function(a, b) {
   return b-a;
  });
return arr;
}

//cara sederhana
  return arr.sort((a, b) => b - a)

console.log(myFunction([1,3,2]) 
```

</details>

---
