# javascript-tutorial
あなたのホームページは、JavaScript Tutorial 

Demo
https://koichii.github.io/javascript-tutorial/

## コメント
// 1行コメント  
/*  
複数行コメント  
*/  

## 変数
日本語を含む Unicode 文字が使えるが推奨されない。  
推奨は、英文字（大文字と小文字は区別される）、_（アンダースコア）、$(ダラー）で始まり、英文字、_、$、数字が続く単語  

var 変数名  
let 変数名 //ブロックスコープにより他から壊されにくい  
const 変数名 // 定数。壊されない  


## 関数
function 関数名() { ... }
  又は
var 関数名 = function() { ... }
  又は、アロー関数
var 関数名 = () => {...}

## 型

### 文字列
var str = "ABC";

### 数値
var num = 123;

### ブーリアン
true, false （真偽）// if (num >= 10) { ... }
null、 undefined、 0、 ''（空文字）は全て false

### オブジェクト
var obj = {str: "abc", num: 543, f: function(a, b){return a + b;} }

.（ドット）または[]（ブラケット）でアクセスする
obj.str // abc
obj["num"]　// 543

## 文
; （セミコロン）で区切るが、省略可能
{} で複数の文を書ける

## 式


## 演算子

(3 + 4) * 5 // 35

### 加減乗除
+, -, *, /

### 比較
==, !==, ===
>, >=, <=, <

### 論理
&& （AND かつ）, ||（OR または）, !（NOT ではない）

### インクリメント、デクリメント
++, --

## 条件分岐

if (i == 10）{
  文
} else {  // エルス、でなければ
  文
}

## 繰り返し

for (var i=0; i++; i<10) {
}

var i=0;
while (i < 10) {
  ...
  i++;
}





