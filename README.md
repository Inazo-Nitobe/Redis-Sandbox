Redisの練習のための仮想環境です。
Redisサーバとクライアント、
PHPからのRedisの操作ができる環境を用意しています。
### セットアップ手順

#### vagrantを起動する
`$ vagrant up`

#### playbookを実行する
`$ ansible-playbook -i hosts bootstrap.yml`

#### 注意点
ホストのIPアドレスは192.168.33.12としているが、
変更したい場合は最初にVagrantfileとhostsに記載している内容を変更しておくこと。

