# javascript-tutorial
あなたのホームページは、JavaScript Tutorial 

Demo
https://koichii.github.io/javascript-tutorial/

## コメント

```javascript
// 1行コメント  

/*  
複数行コメント  
*/  
```

## 選別子（名前）
変数名や関数名などの「名前」のこと。
日本語を含む Unicode 文字が使えるが、日本語は推奨されない。  
推奨は、英文字（大文字と小文字は区別される）、&#95;（アンダースコア）、$(ダラー）で始まり、英文字、&#95;、$、数字が続く単語  
```javascript
A
i
obj
$p01
```

## 文
文 ; （セミコロン）で区切るが、省略可能   
{ 文1 ; 文2 ; ...  } （波かっこ）で複数の文を書ける

## 変数の宣言と値の代入
変数は値（または参照）の入れ物。
「この変数を使います」と宣言してから使う。
= で好きな値を入れることが出来る。
```javascript
var i ; // 「バー」（変数＝バリアブルの略）
var a1, a2, a3 ;
var x = 10 ; // var x ; x = 10 ; の２つを一回で行う
var a = 2, A = 3 ;

x = a * A ; // x は 6

x = x + 1 ; // x は 7
```

## 関数
```javascript
function KANSU( Param1, Param2) {
 ...
  return Modorichi; // 戻り値
 }
  又は
var KANSU = function( Param1 ) { ... }
  又は、アロー関数
var KANSU = ( Param1 ) => {...}

// 関数の例
function sum(p1, p2) {
  return p1 + p2;
}
var A = sum( 3, 5 ) // A に 8 が代入される
```

## 型

### 文字列
```javascript
var str = "ABC";
```

### 数値
```javascript
var num = 123;
```

### ブーリアン（真偽）
```javascript
true, false （真偽）// if (num >= 10) { ... }
null、 undefined、 0、 ''（空文字）は全て false
```

### オブジェクト
変数と関数がセットになったもの。オブジェクトの変数を「プロパティ」、オブジェクトの関数を「メソッド」と呼ぶ。
```javascript
var obj = {str: "abc", num: 543, f: function(a, b){return a + b;} }
```

.（ドット）または[]（ブラケット）でアクセスする
```javascript
obj.str // obj の str は abc
obj.f(2, 3) // obj の f メソッドを引数 2, 3 で呼び出すと、結果は 5
obj["num"]　// obj の num は 543
```

## 値と参照
数値や文字列は変数毎に『値』を保持している。コピーをすると別の値が作成される。コピーした変数の値を変更しても、元の変数の値は変わらない。
オブジェクトや関数は『参照』であり、実態は１つだけで、コピーをしても実態は増えない。コピーしたオブジェクトのプロパティ値を変えると、元のオブジェクトの値も変わっている（実態は同じものだから）。
```javascript
var a = 1; var b = a; b = 2; // a は 1 のまま
var a = {x: 1}; var b = a; b.x = 2; // a.x は 2
```

## 式


## 演算子

```javascript
(3 + 4) * 5 // 35
```

### 加減乗除
```javascript
+, -, *, /
```

### 比較
```javascript
==, !==, ===
>, >=, <=, <
```

### 論理
```javascript
&& （AND かつ）, ||（OR または）, !（NOT ではない）
```

### インクリメント、デクリメント
```javascript
++, --
```

## 条件分岐

```javascript
if (i == 10）{ // 「イフ」（もし）
  文
} else {  // 「エルス」（でなければ）
  文
}
```

## 繰り返し
```javascript
for (var i=0; i++; i<10) { // 「フォー」（～の間）
 ...
}

var i=0;
while (i < 10) { // 「ホワイル」（～する間に）
  ...
  i++;
}
```




