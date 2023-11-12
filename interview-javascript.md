# Exercise Javascript Interview

<div align="center">
  
  <h1>JS Submissions Solutions</h1>
</div>

##### 1. Tulislah fungsi isPalindrom menerima string sebagai argument. Fungsi ini membersihkan string dari karakter non-alfanumerik, mengubahnya menjadi huruf kecil, dan kemudian memeriksa apakah string yang dibalik sama dengan string aslinya


```javascript
function isPalindrom(str) {
  //code
  return
}
isPalindrom('katak')); // expected true
isPalindrom('racecar')); // expected true
isPalindrom('ini terbalik') //expected false
```

<details><summary><b>Solution</b></summary>

```javascript
function isPalindrom(str) {
  str = str.toLowerCase();
  const alphanumericsChars = 'abcdefghijklmnopqrstupwxyz0123456789';

  let cleanStr = '';
  for (let i = 0; i < str.length; i++) {
    if (alphanumericsChars.includes(str[i])) {
      cleanStr += str[i];
    } else {
      alert('ini bukan palindrom');
    }
  }
  return cleanStr === cleanStr.split('').reverse().join('');
}

console.log(isPalindrom('katak'));

cara lain:
// pakai regex
function isPalindrom(str) {
  // Menghapus karakter non-alfanumerik dan mengonversi ke huruf kecil
  str = str.replace(/[^a-zA-Z0-9]/g, '').toLowerCase();

  // Memeriksa apakah string yang dibalik sama dengan string aslinya
  return str === str.split('').reverse().join('');
}
```

</details>

---

##### 2. Tulislah fungsi atau perulangan untuk Fibonacci 

```javascript
function generateFibonnacci(n) {

  //code
  return
}
console.log(generateFibonnacci(10)) expected 0,1,1,2,3,5,8,13
```

<details><summary><b>Solution</b></summary>

```javascript
function generateFibonnacci(n) {
  let num_Fibonannacci = [];
  let n1 = 0;
  let n2 = 1;

  for (let i = 0; i <= n; i++) {
    num_Fibonannacci.push(n1);
    let total = n1 + n2;
    n1 = n2;
    n2 = total;
  }

  return num_Fibonannacci;
}
console.log(generateFibonnacci(10))

cara lain:
// pakai spread operator dan perulangan
let num_Fibonannacci = [];
let n1 = 0;
let n2 = 1;

for (let i = 0; i <= 10; i++) {
  if (i === 0 || i === 1) {
    num_Fibonannacci = [...num_Fibonannacci, i];
  } else {
    let total = n1 + n2;
    num_Fibonannacci = [...num_Fibonannacci, total];
    n1 = n2;
    n2 = total;
  }
}
console.log(num_Fibonannacci);
```

</details>

---
##### 3. Tulislah perulangan yang memisahkan angka genap dan ganjil sampai 100

```javascript

// menggunakan if else dan spread operator
for() {

  //code
  
}
console.log({ num_Genap, num_Ganjil }); num_genap : 0,2,4,6,8,.., num_ganjil: 1,3,5,7,9,11,13,..
```

<details><summary><b>Solution</b></summary>

```javascript

// menggunakan if else dan spread operator

 let num_Ganjil = [];
 let num_Genap = [];
 for (let i = 0; i <= 100; i++) {
   if (i % 2 == 0) {
     num_Genap = [...num_Genap, i];
   } else {
     num_Ganjil = [...num_Ganjil, i];
   }
 }
console.log({ num_Genap, num_Ganjil })

cara lain:
// menggunakan ternary dan method push
let num_Ganjil = [];
let num_Genap = [];
for (let i = 0; i <= 100; i++) {
  i % 2 == 0 ? num_Genap.push(i) : num_Ganjil.push(i);
}
console.log({ num_Genap, num_Ganjil })
```

</details>

---
##### 4. Tulislah perulangan menampilkan bilangan prima

```javascript

// menggunakan if else dan spread operator
for() {

  //code
  
}
console.log(num_Prima); expected 
```

<details><summary><b>Solution</b></summary>

```javascript

// menggunakan if else dan spread operator

let num_Prima = [];
for (let i = 1; i <= 100; i++) {
  let bill = 0;
  for (a = 1; a <= i; a++) {
    if (i % a == 0) {
      bill = bill + 1;
    }
  }

  if (bill == 2) {
    num_Prima = [...num_Prima, i];
  }
}

console.log(num_Prima);

``

</details>

---




