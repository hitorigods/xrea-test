# 概要
レベルアッププログラミングの静的サイト公開の練習リポジトリです。


# プロジェクト管理

このリポジトリのタスクはプロジェクトにて管理されています。
タスクの追加・進行・完了時は、プロジェクトの更新も忘れないようにしてください。

https://github.com/hitorigods/lp-practice-static/projects/1


# サイトのURL

https://hitorigods.shop/

/public_html/hitorigods.shop/


# SSH接続
```
$ ssh hitorigods@s223.xrea.com
```

# GitでSSHのパスフレーズ入力を省略

```
$ eval `ssh-agent`
$ ssh-add '/c/Users/HIRO/.ssh/id_rsa'
```
WSL2接続の場合
```
$ ssh-add ~/.ssh/id_rsa
```

# SSH接続IP許可

https://cp.xrea.com/site/tools/

グローバルIPアドレスが変わった場合

# リリース手順

プロジェクトディレクトリで以下のコマンドを実行

```
$ sh deploy.sh
```

# グローバルIPアドレスの確認方法

https://inet-ip.info/

# GithubのグローバルIPアドレスの確認方法

https://github.com/hitorigods/lp-practice-static/runs/6000145359?check_suite_focus=true

「show global ip」タブに表示
