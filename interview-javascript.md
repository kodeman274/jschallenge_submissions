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
