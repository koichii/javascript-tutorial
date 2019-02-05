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

## 変数
日本語を含む Unicode 文字が使えるが推奨されない。  
推奨は、英文字（大文字と小文字は区別される）、_（アンダースコア）、$(ダラー）で始まり、英文字、_、$、数字が続く単語  
```javascript
var 変数名  
let 変数名 //ブロックスコープにより他から壊されにくい  
const 変数名 // 定数。壊されない  
```

## 関数
```
function 関数名() { ... }
  又は
var 関数名 = function() { ... }
  又は、アロー関数
var 関数名 = () => {...}
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

### ブーリアン
```javascript
true, false （真偽）// if (num >= 10) { ... }
null、 undefined、 0、 ''（空文字）は全て false
```

### オブジェクト
```javascript
var obj = {str: "abc", num: 543, f: function(a, b){return a + b;} }
```

.（ドット）または[]（ブラケット）でアクセスする
```javascript
obj.str // abc
obj["num"]　// 543
```

## 文
; （セミコロン）で区切るが、省略可能   
{} で複数の文を書ける

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
if (i == 10）{
  文
} else {  // エルス、でなければ
  文
}
```

## 繰り返し
```javascript
for (var i=0; i++; i<10) {
}

var i=0;
while (i < 10) {
  ...
  i++;
}
```




