# init.el


1. 素の emacs をインストールする
https://www.gnu.org/software/emacs/download.html#nonfree
```console
$ brew install --cask emacs
```

2. emacs を起動しない
※homeディレクトリ配下に `.emacs.d` が自動生成されてしまうから

3. homeディレクトリに、このリポジトリを `.emacs.d` として git clone してくる
```console
$ cd ~
$ git clone git@github.com:Ishizuka427/emacs.d.git ~/.emacs.d
```
4. emacs を起動
```console
$ emacs
```
