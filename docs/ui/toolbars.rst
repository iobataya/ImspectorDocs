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

- 最初のボタン： **new measurement** をデフォルトのパラメーターで作成する。
- ２番目： **new measurement from a template** であり、既定のテンプレートからmeasurementを作成する。
- ３番目： measurementファイルを **open** する。msr以外のフォーマットのものもここで開くことができる。
- ４番目： measurementファイルをに名前をつけて **save** する。
- ５番目： **save**　上書き
- The sixth button of the file toolbar creates a **new window** within the current measurement.
- The seventh button of the file toolbar **cuts** out the selected data window. The data is purged to the clipboard.
- The eighth button of the file toolbar **copies** the selected data to the clipboard.
- The ninth button of the file toolbar **pastes** the selected data window to the measurement or graph window.

.. _fig_toolbar_files:
.. figure:: /images/ui/toolbar_files.png
   :width: 9 cm
   :align: center

   The 'Files' toolbar.

Measurement toolbar
-------------------

- The first button of the 'Measurement' toolbar (:ref:`fig_toolbar_measurement`) is the 'REC' button. It starts a measurement with the given parameters.
- The second button of the 'Measurement' toolbar pauses a measurement at the point when it is pressed.
- The third button of the 'Measurement' toolbar clones a measurement including the imaging parameters.
- The fourth button of the 'Measurement' toolbar is labeled 'Auto repetition'. When pressed, the measurement is continued until being stopped.

.. note::
   If the 'overwrite warning' is activated Imspector will ask if the current measurement should be overwritten.
   **An already existing file may be overwritten!**

.. _fig_toolbar_measurement:
.. figure:: /images/ui/toolbar_measurement.png
   :width: 4.5 cm
   :align: center

   The 'Measurement' toolbar.

Zoom toolbar
------------

- The first three buttons of the 'Zoom' toolbar (:ref:`fig_toolbar_zoom`) are similar to the ones known from Windows applications: **zoom to selection, zoom in, zoom out**.
- The fourth button of the 'Zoom' toolbar ('Reset Zoom') zooms the data to a scale where one pixel on the screen equals one pixel in the measurement.
- The fifth button of the 'Zoom' toolbar enlarges the measurement window to the size of the shown data (containing the zoom factor).
- The sixth button of the 'Zoom' toolbar shrinks the measurement window to the size of the shown data (containing the zoom factor).
- The seventh button of the 'Zoom' toolbar locks the dimensions of shown data.

.. _fig_toolbar_zoom:
.. figure:: /images/ui/toolbar_zoom.png
   :width: 7 cm
   :align: center

   The 'Zoom' toolbar.
