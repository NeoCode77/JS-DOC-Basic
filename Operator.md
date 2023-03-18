# OPERATOR
> **Operator Aritmatika** digunakan untuk melakukan operasi matematika.

|operator|description|
|----|----|
|+|plus|
|-|minus|
|*|times|
|/|divine|
|%|mod|
|**|power|
```javascript
let a = 5;
let b = 2;

console.log(a + b);     // 5 + 2 = 7
console.log(a - b);     // 5 - 2 = 3
console.log(a * b);     // 5 x 2 = 10
console.log(a / b);     // 5 : 2 = 2.5
console.log(a % b);     // 5 % 2 = 1
console.log(a ** b);    // 5 ^ 2 = 25
```
> **Operator Komparasi** digunakan untuk melakukan perbandingan dan menghasilakn boolean ( true dan false ).

|operator|description|
|----|----|
|==|equal|
|===|strict equal|
|>|greater|
|<|less|
|>=|greater equal|
|<=|less equal|
|!=|not equal|
```javascript
let a = 5;
let b = "2";

console.log(a == b);    // false
console.log(a === b);   // false
console.log(a > b);     // true
console.log(a < b);     // false
console.log(a >= b);    // true
console.log(a <= b);    // false
console.log(a != b);    // true
```

 > **Operator logika** digunakan untuk melakukan perbandingan dua atau lebih kondisi dan menghasilakn boolean ( true dan false ).

|operator|description|
|----|----|
|&&|and|
| \|\| |or|
|!|not|

```javascript
console.log( true && true );      // true
console.log( true && false );     // false
console.log( false && true );     // false
console.log( false && false );    // false

console.log( true || true );      // true
console.log( true || false );     // true
console.log( false || true );     // true
console.log( false || false );    // false

console.log( !true );     // false
console.log( !false );    // true
```

> **Operator IN** adalah operator yang menghasilkan true jika sebuah property ada dalam object.
```javascript
// [property] in [object]

let obj = {
    "name"  : "budi",
    "age"   : 20
}

console.log( "name" in obj );     // true
console.log( "age" in obj );      // true
console.log( "gender" in obj );   // false
```

> **Operator Ternary** adalah operator yang akan menghasilkan value pertama jika kondisi true.
```javascript
// [condtion] ? [value-1] : [value-2]

let nilai = 79;
let hasil = nilai >= 75 ? "LULUS" : "TIDAK LULUS";
console.log(hasil);        // "LULUS"

let umur = 18;
let category = umur > 80 ? "LANSIA" : umur > 25 ? "DEWASA" : umur > 12 ? "REMAJA" : "ANAK-ANAK";
console.log(category)      // "REMAJA"
```

> **Operator Nullish** adalah operator yang akan menghasilkan value default jika variabel bernilai null atau undifined.
```javascript
// [variabel] ? [value-default]

let a = null;
let result = a ?? "hello world";
console.log( result )     // "hello world"
```

> **Operator chaining** adalah operator yang digunakan untuk mengecek ada tidaknya property pada object secara aman.
```javascript
// [object]?.[property]?.[property]?. ... .[property]

let person = {
    "name"  : "budi",
    "age"   : 20
}


console.log( person.history.education );      // error
console.log( person?.history?.education );    // undifined
``` 
