# Git コンフリクト・マージ演習

mainブランチの最初のコード

```python
def greet(s):
    print(f"{s}さん、こんにちは!")
    
if __name__ == "__main__":
    greet("Taro")
```

## やりたいこと

- メッセージの英語化 (english ブランチで実施)
- パラメータ名 s を name に改善 (param ブランチで実施)

## 操作例

- english ブランチを作成し、切り替え
- greet 関数の日本語のメッセージを英語化
- コミット
- main ブランチに切り替え
- param ブランチを作成し、切り替え
- パラメータ名 s を name に変更
- コミット
- main ブランチに切り替え
- main ブランチに english ブランチをマージ
- main ブランチに param ブランチをマージ（ここでコンフリクトが発生）


