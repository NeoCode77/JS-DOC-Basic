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
