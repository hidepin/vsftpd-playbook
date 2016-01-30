vsftpd-playbook
============================================================

# 概要

vsftpdの設定
common-ansible-roleにより基本設定を実施
設定変更したファイルと変更前のファイルをバックアップを取得。
設定変更後再起動を実行。

- CentOS6

# 設定

    common_ntp_server     # ntpサーバ
    common_user.name      # 作成するユーザ名
    common_user.passsword # 作成するユーザのパスワード(ハッシュ値)
    common_user.uid       # 作成するユーザのuid
    common_user.group     # 作成するユーザのgroup名
    common_user.gid       # 作成するユーザのgid

# 依存関係

- common-ansible-role

# TODO

  - CentOS7対応
