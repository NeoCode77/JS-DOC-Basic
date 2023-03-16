# variabel 
**Variabel Mutable**
> varaibel mutable adalah variabel yang valuenya bisa diubah atau dinamis.
```javascript
// let [nama-variabel] = [value];

let name = "budi";
console.log("my name is",name);   // "my name is budi"

// let [nama-variabel1] = [nama-variabel2] = [nama-variabel3] = ... = [value] 
let num1 = num2 = num3 = 200;
console.log(num1,num2,num3);      // 200 200 200

// let [nama-variabel1] = [value] , [nama-variabel2] = [value] , [nama-variabel3] = [value] , ...
let buah1 = "pisang" , buah2 = "jeruk" , buah3 = "apel";
console.log(buah1,buah2,buah3);   // "pisang jeruk apel"
```

**Variabel Imutable**
> variabel imutable adalah variabel yang valuenya tidak bisa diubah atau statis.
```javascript
// const [nama-variabel] = [value];
const country = "indonesia";
console.log("I am from",country); // "I am from indonesia"

const arr = [1,2,3,4,5,6];
Object.freeze(arr);
```


**Tipe Data**
> untuk mengecek tipe data variabel menggunakan **typeof**
```javascript
let name = "budi";
let age = 20;
let maried = false;

// typeof [varibel]
console.log( typeof name );      // String
console.log( typeof age );       // Number
console.log( typeof maried );    // boolean
```
|Tipe Data|Deskripsi|
|----|----|
|Number| tipe data angka integer ( bilangan bulat ) dan float( bilangan pecahan )|
|String| tipe data text |
|array| tipe data array|
|boolean| tipe data boolean ( true dan false )|
|object| tipe data object|
|undifined| tipe data yang belum didefinisikan|

**Konversi Tipe Data**
> konversi ke string
```javascript
// String([variabel/value]);
let a = String(10);
console.log( a );
```
>konversi ke Number
```javascript
// Number( [varibel/value] )
let b = Number("501");
console.log( b );

// parseInt
let c = parseInt("124.5");
console.log( c );

// parseFloat
let d = parseFloat("12.4566");
console.log( d );
```
**Sistem Bilangan**
|type number|description|basis|range|
|:----:|----|----|----|
|0b|bilangan biner|2| 0 dan 1 |
|0o|bilangan octal|8| 0 , 1 , 2 , 3 , 4 , 5 , 6 , 7 |
|0x|bilangan hexadesimal|16| 0 , 1 , 2 , 3 , 4 , 5 , 6 , 7 , 8 , 9 , A , B , C , D , E , F |


```javascript
let biner = 0b11111111;
let octal = 0o17;
let hexadesimal = 0x14;

console.log( biner );         // 255
console.log( octal );         // 15
console.log( hexadesimal );   // 20

// parse( [variabel/value] , [basis] );
let a = parseInt( 11111111 , 2 );
let b = parseInt( 17 , 8 );
let c = parseInt( 14 , 16 );

console.log( a );         // 255
console.log( b );         // 15
console.log( c );         // 20
```

