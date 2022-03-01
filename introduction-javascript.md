## Soal 1
Apa yang akan terjadi jika kita mengakses nilai dari sebuah variabel yang tidak didefinisikan?
 
- a. akan mengembalikan nilai undefined
- b. akan mengembalikan nilai null
- c. akan mengembalikan nilai NaN
- d. akan mengembalikan nilai 0
- e. akan mengembalikan nilai -0

## Soal 2
Apa yang akan terjadi jika kita kode berikut dijalankan?
```js
if(1+1 === 2){
  console.log("1+1 is equal to 2");
}
```
 
- a. akan mengembalikan nilai undefined
- b. akan mencetak "1+1 is equal to 2"
- c. akan mencetak "1+1 is not equal to 2"
- d. error: SyntaxError: Unexpected token '='
- e. error: SyntaxError: Unexpected token ';'

## Soal 3
Pilihlah yang benar untuk menampilkan "coding" dari function berikut.
```js
const asrul = {
  name: "Asrul",
  age: 21,
  job: "student",
  hobbies: ["coding", "reading", "gaming"]
}
function getHobbies(hobbies, position = 0){
  return hobbies[position];
}
console.log(getHobbies(asrul.hobbies, -1))
```

- a. return hobbies.map(hobby => `${hobby}`)
- b. console.log(getHobbies(asrul.hobbies))
- c. console.log(getHobbies(asrul.hobbies, 1))
- d. console.log(getHobbies(asrul.hobbies, 2))
- e. console.log(getHobbies(asrul.hobbies, 3))

## Soal 4 
Berdasarkan soal diatas, kita bisa mengakses nilai dari sebuah array dengan menggunakan index. 
Apa yang akan terjadi jika kita mengakses `console.log(getHobbies(asrul.hobbies, -1))`?
 
- a. akan mengembalikan nilai null
- b. akan mengembalikan error: RangeError: Invalid array index
- c. akan mengembalikan error: TypeError: undefined is not an array
- d. akan mengembalikan error: TypeError: undefined is not a function
- e. akan mengembalikan nilai undefined

## Soal 5
Bagaimana cara membuat sebuah function yang menerima parameter berupa number dan 
mengembalikan urutan bilangan dari 0 sampai dengan parameter tersebut?

