==========
Color maps
==========

Imspectorでは'Fire'がデフォルトのカラーマップとして選択されている(:ref:`fig_colormap_fire`)。それ以外にも種々の内蔵されているカラーマップを選択できる(:ref:`fig_colormaps`)。選択されているカラーマップはmeasurementウィンドウの下部に表示されている。カラーマップの左右にはシグナルの最小値と最大値が表示されている。
スタックビューでのカラーマップはその時選択されている最小・最大値に調整される。

.. _fig_colormap_fire:
.. figure:: /images/ui/colormap_fire.jpg
   :width: 12 cm
   :align: center

   'Fire' カラーマップ

カラーマップの値は右クリックから現れるコンテキストメニューで変更できる。
.. Properties of the colormap can be changed using right-click context menu. To access this menu the active colormap has to be right-clicked.

カラーマップの変更
----------------

カラーマップ上で右クリックしてコンテキストメニューを表示する。'Colormap'メニューの中から表示させたいカラーマップを選択する。
.. Enter colormap right-click context menu. To change the colormap choose the first entry of the menu ‘Colormap' and simply select the colormap of choice.

.. _fig_colormaps:
.. figure:: /images/ui/colormaps.jpg
   :width: 14 cm
   :align: center

   内蔵されているカラーマップ

カラーマップのコピー
------------------

カラーマップはmeasurement間でコピー＆ペーストできる。

1. コピーしたいカラーマップを左クリックで選択し、 :kbd:`ctrl + c` でコピーする。コピーしたカラーマップは新しい画像の中で :kbd:`ctrl + v` でペーストする。
2. カラーマップをドラッグ＆ドロップでもコピーできる。カラーマップを選択した後、 :kbd:`ctrl + left-click` のままドラッグし、新しい画像の中へドロップする。

カラーマップでのシグナルの最大値・最小値の固定
------------------------------------------

カラーマップ上で右クリックしてコンテキストメニューを開く。'Lock'を選択すると最大値と最小値をロックできる。

.. note:: このオプションはシグナルの自動調整を防げるため、画像を連続取得している時に便利である。

カラーマップの線形・対数モード
---------------------------

Imspectorのシグナルは線形あるいは対数モードで表示できる。標準的には線形モードで表示している。
カラーマップ上で右クリックし'Logarithmic'を選択すると対数表示になる。もし対数モードになった場合にはこのコンテキストメニューに'✓'が表示される。

カラーマップの調整
----------------

シグナルの最小値・最大値の色はいくつかの方法で変更できる。
1. 最小値・最大値の数字の部分をダブルクリックし、数値を直接入力する。数値の目安は選択範囲の輝度ヒストグラム(Histogram)を表示させるとわかりやすい。
2. カラーマップ上で右クリックしてコンテキストメニューを表示し、選択範囲での最小値・最大値を適用する。
3. 選択範囲の最小値・最大値の適用はショートカットでも行える。 :kbd:`F9 / F10`.
   (:kbd:`F9`: 最大値; :kbd:`F10`: 最小値)

.. note:: The colormap must be visible at the bottom to do this.

カスタムカラーマップ
------------------

さらに、カラーマップエディタで新しいカラーマップを編集できる(:ref:`fig_colormap_custom`)。
カラーマップエディタはカラーマップ上で右クリックし、'New'を選択すると表示される。

.. _fig_colormap_custom:
.. figure:: /images/ui/colormap_custom_dialog.png
   :width: 8 cm
   :align: center

   'Colormap editor' ダイアログ

.. note:: Colormaps can be saved and loaded again.
