
起動方法
========

コマンドラインからの起動
------------------------

Linux等のOSで一般的な、端末からのコマンド入力による操作でQtcappを起動する場合は、Qtcappの実行ファイルである "qtcapp" というコマンドを入力します。

このコマンドは、インストール先の "bin" ディレクトリに入っています。そこにパスが通っていれば、単に ::

 qtcapp

と打ち込むだけで起動します。

あるいは、Qtcappをソースからビルドした場合、実行ファイルはビルドディレクトリに生成されます。そちらの実行ファイルを直接実行することも可能です。例えば、ソースディレクトリ内の "build" というビルドディレクトリでビルドを行った場合は、端末上で以下の入力することでQtcappを起動できます。 ::

 cd [ソースディレクトリ]
 ./build/qtcapp

起動すると以下のようなQtcappのメインウィンドウが表示されます。

.. image:: images/start_0.png

コマンドライン引数による設定ファイルの指定
------------------------------------------

Qtcapp起動時に設定ファイルを読み込んだ状態にすることも可能です。これを行うためには、Qtcapp起動時にコマンドライン引数で設定ファイル（.qtc）を指定します。例えば、カレントディレクトリにある"setting1.qtc"という設定ファイルを読み込む場合は、 ::

 qtcapp setting1.qtc

といったかたちで指定すればOKです。コマンドラインに慣れていれば、この方法によって設定ファイルの読み込みを効率的に行うことができます。
