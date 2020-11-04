=========
ツールバー
=========

Display ツールバー
-----------------

'Display'ツールバー(:ref:`fig_toolbar_display_2`)は、データの表示方法をすぐに変更できるボタンを備える。

- 表示軸ボタン

  - XY mode (1)
  - XZ Mode (2)
  - YZ Mode (3)
  - XY軸を交換して回転させる、Flip (4)

- スタック操作ボタン

- 3Dスタック1枚の表示と重ね合わせ表示を切り替える。(5)

- 全スタックの合計値で表示する。(6)
  - スタックの最大値を投影する、MIP表示 (7)

- 表示操作ボタン

- ギャラリーモード/オーバーレイモードの切り替え(8)
  - 異なるチャンネルをRGB色で表示させる。(9)
    割り当てる色やチャンネル数はPreferencesのDisplay settingsでRGB以外にも設定できる。
  - スケールバーの表示切替
  - データスタックの情報を表示する。
  - イメージサイズの変更
  
.. _fig_toolbar_display:
.. figure:: /images/ui/toolbar_display_2.png
   :width: 8 cm
   :align: center

   The 'Display' toolbar.

Filesツールバー
--------------

#. **new measurement** をデフォルトのパラメーターで作成する。(1)
#. **new measurement from a template** であり、既定のテンプレートからmeasurementを作成する。
#. measurementファイルを **open** する。msr以外のフォーマットのものもここで開くことができる。
#. measurementファイルをに名前をつけて **save** する。
#. **save**　上書き
#. 新しい **new window** を作成する。現在のmeasurement内に作成される。
#. **cuts** カット
#. **copy** コピー
#. **paste** ペースト

.. _fig_toolbar_files:
.. figure:: /images/ui/toolbar_files.png
   :width: 9 cm
   :align: center

   The 'Files' toolbar.

測定ツールバー
-------------

#. RECボタン。測定を開始する。 (:ref:`fig_toolbar_measurement`) 
#. 測定を一時停止する。
#. 現在の測定を複製する（測定条件も含めて複製される）
#. 測定を連続して行う。

.. .. note::
   If the 'overwrite warning' is activated Imspector will ask if the current measurement should be overwritten.
   **An already existing file may be overwritten!**

.. _fig_toolbar_measurement:
.. figure:: /images/ui/toolbar_measurement.png
   :width: 4.5 cm
   :align: center

   The 'Measurement' toolbar.

ズームツールバー
---------------

#. ズームボタン (:ref:`fig_toolbar_zoom`)
   - 選択範囲を拡大する (1)
   - 拡大する、**zoom in** (2)
   - 縮小する、**zoom out** (3)
#. 等倍表示にする、**Reset Zoom** (4)
#. 画像をウィンドウサイズに合わせる、**Fit to frame**
#. ウィンドウサイズを画像に合わせる、**Fit to Image**
#. アスペクト比のロック

.. _fig_toolbar_zoom:
.. figure:: /images/ui/toolbar_zoom.png
   :width: 7 cm
   :align: center

   The 'Zoom' toolbar.
