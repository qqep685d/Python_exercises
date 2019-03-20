![ゲノム解析のためのPython練習帳](https://github.com/qqep685d/MyIMGs/blob/master/logo/python_exercises.png?raw=true "logo")

# I-2-2. 文字列、数値、真偽値
## Exercise 2: 文字列を繋げる<a name="ex2"></a>

Exercise 1で実行してもらったように、「文字列 + 数値」ではエラーが生じました。

では、「文字列 + 文字列」にするとどうなるでしょうか？  
次のプログラムを書いて実行してみてください。

```python
# 以下の<文字列1>と<文字列2>は自分で書いてください。
print(<文字列1>　+ <文字列2>)
```

### 解答例
`文字列型　+ 文字列型`を実行すると、文字列を連結させることができます。

```python
print('abc' + '123') # 出力 => abc123
```

ついでに、これもぜひ試してみてください。
```python
print('abc' * 3)
```
