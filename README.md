# 部誌作成テンプレート
これはLaTeXで複数記事を集めた部誌的なものを作成するためのテンプレートです。

[サンプルpdf](out/main.pdf)

## 準備
このテンプレートを使うには
- 完全なTeX Live環境


が必要です。macについてはHomebrewを使ってmactexをインストールしてもらえれば大丈夫です。
私はWinユーザーではないので全く保証はできませんが，Windowsについては[WSL](https://learn.microsoft.com/ja-jp/windows/wsl/install)を使ってUbuntuをインストールするのが便利らしいです。
Ubuntuならば，以下のコマンドでインストールできるらしいです。
```
#アップデートと更新
sudo apt update
sudo apt upgrade

# TeX Liveのインストール
sudo apt install texlive-full
```

こだわりがない限りはVSCodeを使って書くのが便利そうです。
私は[VSCode で最高の LaTeX 環境を作る](https://qiita.com/rainbartown/items/d7718f12d71e688f3573)という記事を参考にVSCodeでLaTeXできるようにしました。
テンプレートの中にある.latexmkrcファイルもこのサイトのものを丸パクリしています。

## 使い方
GitHubで「Use this template」をクリックして、リポジトリを作成するのが便利です。
詳しくは，[テンプレートからリポジトリを作成する](https://docs.github.com/ja/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)等を参照してみてください。




