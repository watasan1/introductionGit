# introductionGit

## Command Line とは

コマンドラインとは、コンピュータの操作をキーボード入力の文字でコマンドを入力して行います。

コマンドは、コマンドプロンプトやターミナルと呼ばれるインターフェースを使いコンピュータを操作します。

## Shell(シェル)とは

シェルとは、コマンドラインによってユーザーの命令をOSの心臓部であるカーネルに伝えてくれる仲介役です。

一般的なシェルにはいくつか種類があります。

1. Bash Unix系のOSで利用されるシェルで、ターミナルの`$`がBashを指します。

2. Zsh (Z Shell)ZshはBashの上位互換で、Bashのコマンドが利用できます。最近のmacOSに利用されています。 ターミナルの `%` がZshを指します。

3. Windows PowerShell(pwsh) では、 Windowsのコマンドラインで利用されていて、`>` のあとにコマンドを入力します。
windows Power Shell を省略として本記事では、`pwsh`とします。

## Command Line 基礎

### ディレクトリの作成

フォルダー = ディレクトリ　です。

mkdir コマンド で、ディレクトリの作成をすることができます。(pwsh・Bash)

```Bash・pwsh
$ mkdir <作成したいディレクトリ名>
```

### ディレクトリの移動

cd (change directory) のあとに移動したいディレクトリ名を指定すると指定したディレクトリ名に移動できます。

```bash
$ cd <移動したいディレクトリ名>
```

* ホームディレクトリ(ルートディレクトリ)に移動する

ホームディレクトリとは、ユーザーごとに割り当てられたディレクトリで、そのユーザーのファイルや設定が格納される場所です。

一般的なユーザーのホームディレクトリは、

* macOS

```bash
/home/ユーザー名
```

* windows

```
C:\Users\ユーザー名
```

ホームディレクトリに移動するコマンドは、

```Bash・pwsh
$ cd ~
```

一つ上のディレクトリに移動するコマンド

```Bash・pwsh
$ cd ..
```
### ディレクトリ内のファイルとディレクトリを表示する

* pwsh

```pwsh
> dir
```

* bash

```bash
$ ls
```

オプション

```bash
$ ls -all
```



### 空のテキストファイルの作成

* New-Item コマンド (pwsh)

```pwsh
> New-Item <作成したいファイル名>
```

* touch コマンド (Bash) 

```Bash
$ touch <作成したいファイル名>
```

### カレントディレクトリの確認

タイトルは適切です。pwdなどのコマンドを使った実際の確認方法を説明しましょう。

### ファイル・ディレクトリの削除

タイトルは適切です。学習者が注意すべきことや注意事項を強調しましょう。

### 便利なコマンド

タイトルは適切です。各項目に関連するコマンドやショートカットを説明しましょう。

* ディレクトリを作成してそのあと作成したディレクトリに移動する

* カレントディレクトリからエクスプローラーや、ファインダーを表示する

* VSCode を　表示する

## Git

### Git　をローカルにインストール

タイトルは適切です。手順をステップバイステップで説明しましょう。

* Windows

[https://git-scm.com/download/win](https://git-scm.com/download/win)

* macOS 

### GitHub　のユーザーアカウントを作成する

タイトルは適切です。新しいGitHubユーザーのための手順を提供しましょう。

### Git のユーザーをローカル環境に登録する

タイトルは適切です。学習者がGitを正しく設定するのに役立つ情報を提供しましょう。

### GitHubにSSH接続する

タイトルは適切です。SSHキーの生成とGitHubへの接続手順を明確に説明しましょう。

* 公開鍵と秘密鍵を作成する
* 公開鍵をGitHubに登録する
* configファイルを作成する
* GitHubの接続確認をする

### Gitで管理したくないファイルを指定する

タイトルは適切です。.gitignore ファイルの作成と使用方法について説明しましょう。

### Gitを使ってみる(ローカル)

タイトルは適切です。実際のGitの使用手順を詳細に説明しましょう。

1. ワーキングディレクトリ(フォルダ)を作成する
2. Gitリポジトリを作成する
3. ワーキングディレクトリで作業をする
4. ステージングエリア(インデックス)に登録する
5. コミットする

### 過去のファイルと比較する

タイトルは適切です。コミット間の変更を比較する方法を説明しましょう。

### コミットログ（履歴）を表示

タイトルは適切です。コミット履歴を表示するコマンドとオプションについて説明しましょう。

### リセット系

タイトルは適切です。git resetやgit revertなどのコマンドについて説明しましょう。

## GitHubと連携して利用してみる

タイトルは適切です。GitHubとの連携に関する実践的な手順を提供しましょう。
以上の提案を考慮して、教材の各章をより詳細かつわかりやすく構築していくことが重要です。学習者がスムーズにGitとGitHubをマスターできるように工夫しましょう。

### GitHub上でリモートリポジトリを作成する

### GitHub上のリモートリポジトリをローカルにクローンする

### ブランチを作成する

### プルリクエストする

### マージする


