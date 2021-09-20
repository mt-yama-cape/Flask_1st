# Flask Hello World 検証 APP

## インストールパッケージ

`pipenv install flask`

## PJ 初期化

```bash
pipenv install
pipenv install --dev
```

## 実装 URL

| URL               | 内容                                                        |
| ----------------- | ----------------------------------------------------------- |
| /                 | hello world                                                 |
| /temp             | render_template()実行時にテンプレート html にパラメータ渡し |
| /hoge/{name}      | URL 文字列をパラメータとして解釈、受け取り。                |
| /fuga?name={val}> | GET のパラメータとして受け取り。                            |
| /postinput        | フォーム から POST                                          |
| /json             | json 返し                                                   |
