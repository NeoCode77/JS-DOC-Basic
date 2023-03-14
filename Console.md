# Console
____
> **Console.Log** digunakan untuk mencetak sebuah pesan atau data.

```javascript
console.log( [massage] );
```
|parameter|deskripsi|
|----|----|
|massage|pesan yang akan di print|
```javascript
console.log("hello world");
console.log("my name is NeoCode");
```
______
> **Console.Assert** digunakan untuk mencetak pesan ketika statment bernilai ***false***.
```javascript
console.assert( [statment] , [massage] );
```
|parameter|deskripsi|
|----|----|
|statment|pengondisian jika bernilai false|
|massage|pesan yang akan diprint|
```javascript
let a = 9;
console.assert( a > 10, "a kurang dari 10" );           // output : "a kurang dari 10"
```
