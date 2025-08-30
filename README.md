# PyCaretBook

「PyCaretで学ぶ 機械学習入門」サポートページ

https://www.amazon.co.jp/dp/4863544278/

# 注意点

## PyCaret のバージョン
- 執筆時点では、PyCaret の バージョン `3.0.4` を用いていました
- もし、最新版の PyCaret でエラーがでる場合は、以下のようにバージョンを下げてインストールしてください

```
!pip install pycaret==3.0.4
```

# 書籍修正点

- 修正点があれば、こちらに追記していきます
- もし、読んでいて誤字や分かりづらい点などあれば、https://www.c-r.com/contact/index からご連絡ください

## P.74 コード誤字

```python
model2.fit(X, y)
```
とありますが、正しくは以下です。

```python
model2.fit(X2, y)
```

## P.158 pandasのインポート漏れ

プログラム冒頭に以下のようにpandasのインポート処理を追加してください

```python
import pandas as pd
```

## P.164 pandasのインポート漏れ

プログラム冒頭に以下のようにpandasのインポート処理を追加してください

```python
import pandas as pd
```

## P.172 pandasのインポート漏れ

プログラム冒頭に以下のようにpandasのインポート処理を追加してください

```python
import pandas as pd
```

## P.250 Flaseという誤字

混同行列の説明中に、「Flase Negative」と記載の個所がありますが、正しくは「False Negative」 です。

## P.288 finalize_model() 関数の説明文での誤字

finalize_model() 関数の説明文で、「テストデータを含むすべデータ」と記載の個所がありますが、正しくは「テストデータを含むすべてのデータ」 です。

## P.289 finalize_model() 関数の説明文での誤字

finalize_model() 関数の説明文で、「テストデータを含むすべデータ」と記載の個所がありますが、正しくは「テストデータを含むすべてのデータ」 です。
