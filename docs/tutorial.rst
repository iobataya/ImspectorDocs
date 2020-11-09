.. _ShortTutorial:

=====================
チュートリアル - 基本操作
=====================

これはImspectorの基本操作のチュートリアルである。データを開き、基本的な操作方法に慣れることができる。
撮像のチュートリアルは含まれない。（撮像に関しては _チュートリアルリスト を参照）


データを開く
------------

Imspectorを起動し、すでに撮像したファイルをウィンドウにドラッグする。あるいは、Fileメニューからファイルを開く。

データの表示
----------

データを開くと、ウィンドウに画像あるいはスタックが表示される。ウィンドウを大きくするとそれに伴って画像も大きくなる。操作しやすい大きさに調整する。


矩形選択
*******

画像内でマウスでドラッグすると矩形選択できる。選択部分だけを抽出したり、選択部分だけで輝度の最大・最小値をセットしたりできる。

拡大鏡
*****

ウィンドウの画像上で :kbd:`shift` キーを押しながらマウスの左ボタンを押すとカーソルの位置の画像が拡大できる。
さらに :kbd:`shift + alt` キーを使うとより大きな倍率で画像が拡大できる。

なお、ドラッグを始めた後に :kbd:`shift` キーを押すと、強制的にラインプロファイルの垂直/水平方向の選択モードに入ってしまう。

ショートカット
***********

* :kbd:`F9 / F10` カラーマップの最大値と最小値をあわせる。
  スタックビューでは、カラーマップの最大・最小値を選択した範囲での輝度の最大・最小値に合わせる。グラフビューでは、スライダーの間の最大・最小値にY軸のスケールを合わせる。
* :kbd:`Page Up / Down` スタックデータの場合、スライスをZ軸方向に動かす。
  また、 :kbd:`shift` キーを押しながらだと10スライス、 :kbd:`shift + alt` キーを押しながらだと100スライス分Z軸に沿って動かせる。
* :kbd:`ctrl + Page Up / Down` 4軸目(hidden axis)に沿ってレイヤーを動かす。
  これもスライス同様、 :kbd:`shift` キー、 :kbd:`shift + alt` キーで大きく動かせる。

グラフビュー
----------

画像内でLine Profileメニューを選択すると、任意の2点間の輝度のラインプロファイルがグラフとして現れる。
形状の計測や輝度分布の表示ができる。


ドラッグ＆ドロップ、カット、ペースト
-----------------------------

グラフ、イメージ、カラーマップはウィンドウ間でドラッグ＆ドロップができる。
:kbd:`ctrl` キーを押しながらマウスの左ボタンを押してドラッグ＆ドロップするだけである。
たとえば、カラーマップをあるウィンドウから別のウィンドウへそのまま移すことができる。
New Window (歯車のついたウィンドウアイコン)で空のウィンドウを新規に作っておき、そこへコピーして試すと良い。

* :kbd:`ctrl` ：すべてのスライス（あるいは選択した範囲）を新しいウィンドウにコピーする。
* :kbd:`ctrl + shift` ：現在のスライス(あるいは選択した範囲）を新しいウィンドウにコピーする。
* :kbd:`ctrl + alt` ：データをコピーしない。新しいウィンドウを作成する。

グラフウィンドウでは、矩形選択ではなく垂直なスライダーバーで範囲を選択する。

4次元スタックの場合は次のようなルールが適用される。

* 合計(add-up)やMIP(max intensity projection)モードの場合、すべてのレイヤーがコピーされる。
* スライス(parse-through)モードの場合、現在のレイヤーだけがコピーされる。

Change Stack Size ダイアログ
--------------------------

This dialog allows you to change the physical size, offset and pixel dimensions of the stack as well as its data type.
It can be accessed using the button at the side of the image or via the shortcut :kbd:`ctrl + t`.

.. figure:: /images/ui/change_stack_size_dialog.png
   :width: 10 cm
   :align: center

   Change Stack Size dialog.

Export Data
-----------

Data from Imspector measurements can be exported into several file formats:

- Colormap Tiff files/stacks (.tif/.tiff)
- RGB Tiff files/stacks (.tif)
- binary double files (.dbl)
- Avi files/movies (.avi)
- Visualization toolkit files (.vtk)
- MRC files (.st, .map, .ccp4, .mrc)
- ASCII data files (.dat, .asc)
- Becker&Hickl data files (.sdt)

To export data select the data Stack and select :menuselection:`File --> Export` or use the shortcut :kbd:`ctrl + e` to open the Export Data dialog.


チュートリアルリスト
----------------
* :ref:`ShortTutorial`
* :ref:`Tutorial-STED`
