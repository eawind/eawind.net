# eawind.net

## Hugo のセットアップ

本サイトはHugoという静的サイトジェネレーターを利用して構築しています。
公式の[クイックスタートページ](https://gohugo.io/getting-started/quick-start/)を参照して基本的なセットアップを行ってください。

## git clone と submodule の取得

ローカルで実行する方法です。
次の三つのコマンドを実行してください。

```bash
git clone https://github.com/eawind/eawind.net.git
git submodule init
git submodule update
```

## Hugoの起動

うまく行ったら次のコマンドを実行し、Hugoを起動します。

```
hugo server
```

起動したら、[http://localhost:1313/](http://localhost:1313/)をブラウザで開いて確認します。

## サイトへの反映

本リポジトリにある `master` ブランチにプッシュすることで、Netlify上にあるサイト [https://www.eawind.net/] に反映されます。
