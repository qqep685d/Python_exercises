![ゲノム解析のためのPython練習帳](https://github.com/qqep685d/MyIMGs/blob/master/logo/python_exercises.png?raw=true "logo")

# I-2-1. 変数、データ型
## Exercise 5: データ型を変換する
### チャレンジ問題

次のプログラムは、データ型が適切でないため、上手く動きません。  
「データ型の変換」する関数を使い、プログラムを直してください。

### 解答例
```python
# 円の面積を求める

r = '12'       # 半径
pi = '3.14'  # 円周率π

r = int(r)  # 文字列型 => 整数型
pi = float(pi) # 文字列型 => 浮動小数点数型

S = r * r * pi  # 面積

print(S)
```
