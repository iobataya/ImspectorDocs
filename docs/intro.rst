============
Imspector
============

Imspectorはさまざまな顕微鏡（蛍光・共焦点・STED等）や分光器を直接制御でき、定量的なデータ解析を行うことができるソフトウェアである。
イメージの撮像、データの取得、データ解析を統合することにより、測定結果のリアルタイムでの解析や可視化ができる。

主な機能
--------

.. figure:: /images/intro/customization.jpg
   :width: 8 cm
   :align: center

   ツールバーやメニュー、ショートカットのカスタマイズ
.. Customization of toolbars, menus and shortcuts.

.. figure:: /images/intro/workspace.jpg
   :width: 8 cm
   :align: center

   「workspace」によりすべての測定条件やデータを保存
.. The workspace allows you to keep track of all your measurements.

.. figure:: /images/intro/new_device.jpg
   :width: 8 cm
   :align: center

   標準ドライバやカスタムドライバなどの追加が可能
.. Add new devices derived from standard or custom drivers.

Imspectorは4次元までのグラフや画像をデータを高速に可視化する機能を備えている。
また、各解析が容易にできる直感的なインターフェースにより、データの切り抜きやコピー、オーバーレイなどはGUIで操作できる。
切り抜き、拡大/縮小、多チャンネル表示、カスタムLUT等のツールに加え定量的な顕微鏡観察に便利なツールを備えている。
PSFの計算、線形デコンボリューション、周波数フィルタ、オフライン非線形デコンボリューションも含まれている。

.. figure:: /images/intro/parser.jpg
   :width: 8 cm
   :align: center

   ビルトインパーサーによる解析処理
.. Use the built-in parser to analyse and process your data.

.. figure:: /images/intro/analysis.jpg
   :width: 8 cm
   :align: center

   データの非線形フィッテイング、TCSPCスタックの空間的な各点における時間軸上のシグナル

内蔵されたビルトインパーサーにより、ユーザーが定義したフィルター処理、変換処理、演算処理、ユーザーの定義した関数の非線形フィッティング、種々のアルゴリズムが利用できる。

Imspectorは一般に使われているデータフォーマットの読み込み・書き出しが可能で、他のアプリケーションとの連携ができる。Origin, Photoshop, Freehand, Excelには直接コピー＆ペーストできる。

多様なハードウェアドライバが利用できる。(AIO, DIO, TCSPC, CCD camera from Apogee, Hamamatsu, PCO etc., LASER制御, ステージ制御など)

新しいハードウェアの制御機能の追加は非常に容易で、プラグインとして追加することができる。追加したハードウェアドライバは設定値を調整できるダイアログを提供する。データの読み出しは同期的・非同期的にすることができ、Imspectorは測定フローを制御し、他の装置との同期とデータ読み出しの整理、測定中の解析や可視化が可能である。

.. figure:: /images/intro/docsettings.jpg
   :width: 8 cm
   :align: center

   An intuitive GUI allows you to adjust your measurement parameters.

.. figure:: /images/intro/setasroi.jpg
   :align: center

   すべてのパラメーターはmeasurementファイルに保存される。過去の測定条件や、過去のROIなどすべてを後から読み出すことができる。

このプログラムはハードウェアドライバに定義された設定値を管理することができるので、解析や可視化も含めた測定条件をテンプレートとしてmeasurement(.msr)ファイルに保存できる。このmeasurementはいつでも呼び出して繰り返し使うことができる。測定で取得された実験データは常に測定条件と紐付けられて保存される。


すべてのデータ依存性はプログラムに保存される。もし測定中にデータが変更された場合や処理操作が行われた場合、そのデータに依存するすべてのステップは再度実行されて反映される。
さらに、データの依存性を保存されたデータからも読み出し、必要があればファイルを再読み出しする。設定やウィンドウの位置だけでなくすべての依存性が保存／読み出しできる。

.. 訳不明：It can therefore serve as a graphical　front-end for your command-line numerical analysis tools.

このドキュメントの現在の状況
---------------------------

Imspectorの多くの機能は、|MPI|の|NanoBio|_ のユーザーのアイデアによるものである。

ただ、機能のすべてがこのドキュメントに含まれているわけではなく、Imspector自体が常に開発途上でもあり、新たな機能が追加されたり古い機能が置き換わったりしている。
そのため、ドキュメント内の情報が古い場合がある。多くの機能は直感的で、その名前やツールチップから類推できるものなので、コンテキストメニューのさまざまな項目を試して欲しい。

Imspectorは|MPI| |NanoBio|_ (ドイツ・ゲッティンゲン)で開発された。

Imspectorはドキュメンテーションが追いついていない部分が常にあり、これを手伝ってくれるユーザーを歓迎する。ドキュメントはSphinx_ を使ってビルドされており、ソースフォーマットは `restructured text`_ で書かれている。ページや段落を送付することでその内容（ページや段落）がこのドキュメントに追加される。

Imspectorの引用について
----------------------

データ取得や解析にImspectorを使用して論文などで引用したい場合、次のような表記になる。
	
	| Schönle A., 2006. *Imspector Image Acquisition & Analysis Software*, v0.1
	| http://www.imspector.de

.. _Sphinx: http://www.sphinx-doc.org/en/stable/index.html

.. _`restructured text`: https://en.wikipedia.org/wiki/ReStructuredText

.. |NanoBio| replace:: department of NanoBiophotonics

.. _NanoBio: http://www.mpibpc.mpg.de/hell

.. |MPI| replace:: Max Planck Institute for biophysical Chemistry

.. _MPI: http://www.mpibpc.mpg.de/
