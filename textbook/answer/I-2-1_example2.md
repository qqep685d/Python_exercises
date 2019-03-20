![ゲノム解析のためのPython練習帳](https://github.com/qqep685d/MyIMGs/blob/master/logo/python_exercises.png?raw=true "logo")

# I-2-1. 変数、データ型
## Exercise 2: 変数を使ってみる2

まずは下のセルのプログラムを見てください。  
4行とも`print(9 演算子 7)`の形です。

```python
print(9 + 7)
print(9 - 7)
print(9 * 7)
print(9 / 7)
```

もし、すべての`9`を`100`に、すべての`7`を`24`に置き換えたい場合、
現状ではそれぞれの数字をひとつずつ変更しなければなりません。

変数を使って、より良いプログラムをに変更してみてください。

### 解答例
必ず同じ値を入れる場所がプログラム中に複数箇所ある場合、変数を使うことで、そのプログラムの利便性や保守性が改善します。

```python
a = 9
b = 7

print(a + b)
print(a - b)
print(a * b)
print(a / b)
```
