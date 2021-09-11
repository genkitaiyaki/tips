# コミットメッセージ形式

## 概要

コミットメッセージはある程度ルールを設けた方が良い。
ルールは様々なものがあるが、angularの形式が良さげな気がする。

> <https://github.com/angular/angular/blob/master/CONTRIBUTING.md#-commit-message-format>

以下、必要な部分を和訳して抜粋しつつ個人の主観を交えて記載していく。

## コミットメッセージ構成

angularのコミットメッセージはheader, body, footerで構成される。

```<TEXT>
<header>
<空行>
<body>
<空行>
<footer>
```

`header`コメントは全てのコミットで必須。

記載フォーマットは[Commit Message Header](#commit-header)に準拠しなければならない。

`body`コメントは"docs"以外のコミットで必須。

少なくとも20文字以上記載しなければならない。[Commit Message Body](#commit-body)に準拠しなければならない。

`footer`コメントはオプション。書いても書かなくてもいい。

記載する場合は[Commit Message Footer](#commit-footer)に準拠しなければならない。

