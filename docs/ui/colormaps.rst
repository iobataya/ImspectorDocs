==========
Color maps
==========

Imspectorでは'Fire'がデフォルトのカラーマップとして選択されている(:ref:`fig_colormap_fire`)。それ以外にも種々の内蔵されているカラーマップを選択できる(:ref:`fig_colormaps`)。選択されているカラーマップはmeasurementウィンドウの下部に表示されている。カラーマップの左右にはシグナルの最小値と最大値が表示されている。
スタックビューでのカラーマップはその時選択されている最小・最大値に調整される。


  In Imspector the colormap ‘Fire' is typically selected (:ref:`fig_colormap_fire`). Furthermore a variety of built-in colormaps can be chosen (:ref:`fig_colormaps`)
　　The active colormap is displayed at the bottom of the measurement window. On the left and right bottom of the colormap,
　　the minimum and maximum gray value is given. In a stack view the colormap is adjusted to the maximum/minimum of the current selection.

.. _fig_colormap_fire:
.. figure:: /images/ui/colormap_fire.jpg
   :width: 12 cm
   :align: center

   'Fire' カラーマップ

カラーマップの値は右クリックから現れるコンテキストメニューで変更できる。
  Properties of the colormap can be changed using right-click context menu. To access this menu the active colormap has to be right-clicked.

カラーマップの変更
----------------

カラーマップ上で右クリックしてコンテキストメニューを表示する。'Colormap'メニューの中から表示させたいカラーマップを選択する。
  Enter colormap right-click context menu. To change the colormap choose the first entry of the menu ‘Colormap' and simply select the colormap of choice.

.. _fig_colormaps:
.. figure:: /images/ui/colormaps.jpg
   :width: 14 cm
   :align: center

   内蔵されているカラーマップ

カラーマップのコピー
------------------

カラーマップはmeasurement間でコピー＆ペーストできる。
  Colormaps can be copied between measurements using standard Windows shortcuts.

1. コピーしたいカラーマップを左クリックで選択し、 :kbd:`ctrl + c` でコピーする。コピーしたカラーマップは新しい画像の中で :kbd:`ctrl + v` でペーストする。
2. カラーマップをドラッグ＆ドロップでもコピーできる。カラーマップを選択した後、 :kbd:`ctrl + left-click` のままドラッグし、新しい画像の中へドロップする。

   1. The colormap has to be selected using left-click and is copied using :kbd:`ctrl + c`. Then insert the copied colormap
   into the new image using :kbd:`ctrl + v`
   2. Alternatively, the colormap can be copied using drag and drop. To this end, the active colormap has to be selected
   using :kbd:`ctrl + left-click`, drag to the new image and drop it.


カラーマップでのシグナルの最大値・最小値の固定
------------------------------------------

カラーマップ上で右クリックしてコンテキストメニューを開く。'Lock'を選択すると最大値と最小値をロックできる。

.. note:: このオプションはシグナルの自動調整を防げるため、画像を連続取得している時に便利である。

カラーマップの線形・対数モード
---------------------------

Imspectorのシグナルは線形あるいは対数モードで表示できる。標準的には線形モードで表示している。
カラーマップ上で右クリックし'Logarithmic'を選択すると対数表示になる。もし対数モードになった場合にはこのコンテキストメニューに'✓'が表示される。
  In Imspector gray values can be represented in a linear or logarithmic mode. Typically the colormap is set to a linear mode.
  To change the colormap mode to logarithmic scale, please enter colormap right-click context menu and click 'Logarithmic'.
  If the logarithmic mode is active, a tick is shown in front of this entry.

カラーマップの調整
----------------

シグナルの最小値・最大値の色はいくつかの方法で変更できる。
1. 最小値・最大値の数字の部分をダブルクリックし、数値を直接入力する。数値の目安は選択範囲の輝度ヒストグラム(Histogram)を表示させるとわかりやすい。
2. カラーマップ上で右クリックしてコンテキストメニューを表示し、選択範囲での最小値・最大値を適用する。
3. 選択範囲の最小値・最大値の適用はショートカットでも行える。 :kbd:`F9 / F10`.
   (:kbd:`F9`: 最大値; :kbd:`F10`: 最小値)
  1. The respective value can be accessed and changed after double-clicking the value at the bottom of the colormap.
  2. The values can be adjusted to the minimum/maximum gray value of the image or a selected region in the colormap right-click context menu.
  3. The values can be adjusted to the minimum/maximum gray value of the image or a selected region by pressing :kbd:`F9 / F10`.
     (:kbd:`F9`: maximum value; :kbd:`F10`: minimum value).

.. note:: The colormap must be visible at the bottom to do this.

カスタムカラーマップ
------------------

さらに、カラーマップエディタで新しいカラーマップを編集できる(:ref:`fig_colormap_custom`)。
カラーマップエディタはカラーマップ上で右クリックし、'New'を選択すると表示される。
  In addition, new colormaps can be created using a colormap editor (:ref:`fig_colormap_custom`). To create a custom colormap, the colormap
  editor has to be opened. To this end, the colormap context has to be opened by right-clicking the active colormap.
  Then select 'New'.

.. _fig_colormap_custom:
.. figure:: /images/ui/colormap_custom_dialog.png
   :width: 8 cm
   :align: center

   'Colormap editor' ダイアログ

.. note:: Colormaps can be saved and loaded again.
