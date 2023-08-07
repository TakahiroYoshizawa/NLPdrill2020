# 環境構築
### 1.m2 macへのpython環境構築
macへのpython環境構築から実施する必要があったため、下記のサイトを参考に実施した。
> https://analytics-note.xyz/mac/python-apple-silicon/

メモ：zshファイルを変更したときは、```source ~/.zshrc```が必要。
> https://zenn.dev/otohbk_ky/articles/b9b7d26255db78

### 2.pythonのパッケージ管理
pythonのパッケージ管理は普段の仕事同様にpoetryを使って管理することにする。インストールなどは、下記のサイトを参考に実施する。
> https://kosuke-space.com/python-poetry

インストール後、コマンドのpathが通っていない問題が発生するが
```sh
export PATH="$HOME/.local/bin:$PATH"
```
でpathが通れば大丈夫。コマンドの場所確認しよう。
