ansible-mysql57
=========

ansibleでMySQL5.7をインストールしてrootパスワードの変更を行うrole

Requirements
------------

CentOS7向け
molecule(driver=docker)で動作確認して居る

Role Variables
--------------

- mysql_root_password
rootのパスワードを指定する。これが設定されてないと動かない

Dependencies
------------

特に依存関係は無い

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - ansible-mysql57

License
-------

Apache License, Version 2.0

Author Information
------------------

https://github.com/nyomo
