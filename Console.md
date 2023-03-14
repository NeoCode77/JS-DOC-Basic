# 01 - Console
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
______
> **Console.Clear** digunakan untuk membersihkan console atau terminal.
```javascript
console.clear();
```
______
> **Console.Table** digunakan untuk menampilkan data array atau object dengan table.
```javascript
console.table( [array/object] );
```
|parameter|deskripsi|
|----|----|
|array/object|variabel yang berupa array dan object|
```javascript
let arr = [11,12,13,14,15,16,17];
let obj = { "name" : "budi","age":20 };

console.table(arr);
console.table(obj);
```
______
> **Console.Time** digunakan untuk memulai perhitungan waktu menjalankan program.
```javascript
console.time( [label] );
```
|parameter|deskripsi|
|----|----|
|label|label perhitungan|
```javascript
console.time("forloop");

for(let i = 0 ; i < 1000 ; i++){
  console.log(i);
}
```
____
> **Console.timeEnd** digunakan untuk menghentikan dan menampilkan perhitungan waktu menjalankan program.
```javascript
console.timeEnd( [label] ):
```
|parameter|deskripsi|
|----|----|
|label|label perhitungan|

```javascript
console.time("forloop");

for(let i = 0 ; i < 1000 ; i++){
  console.log(i);
 }
 
 console.timeEnd("forloop");
```


