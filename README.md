BrowserQuest
============

BrowserQuest is a HTML5/JavaScript multiplayer game experiment.


Documentation
-------------

Documentation is located in client and server directories.


説明
----

このBrowserQuestは、SOFTLAYERで動作する様に、修正したものです。


サーバーサイトのインストール方法
--------------------------------

必要なNode.jsのパッケージの取り込み

    # git clone https://github.com/takara9/BrowserQuest
    # cd BrowserQuest
    # npm install -d

次の設定ファイルを必要に応じて編集します。TCPポート番号:8000で通信できれば、
このまま変更せずに利用できます。

    # vi BrowserQuest/server/config_local.json


サーバーの起動方法
------------------

    # nodejs server/js/main.js



クライアントのセットアップ
--------------------------

シェルの実行で、サーバーのIPアドレスを埋め込みます。

    # cd BrowserQuest/bin
    # ./sl_setup


ブラウザからのアクセス方法
--------------------------

以下のURLアドレスで、プレイできます。

http://サーバーIPアドレス/client/








License
-------

Code is licensed under MPL 2.0. Content is licensed under CC-BY-SA 3.0.
See the LICENSE file for details.


Credits
-------
Created by [Little Workshop](http://www.littleworkshop.fr):

* Franck Lecollinet - [@whatthefranck](http://twitter.com/whatthefranck)
* Guillaume Lecollinet - [@glecollinet](http://twitter.com/glecollinet)
=======
# BrowserQuest
HTML5 WebSocket Game
>>>>>>> f7fc9479d39e1b66808db7447ff052fadc8b9a1f
