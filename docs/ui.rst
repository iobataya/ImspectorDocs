========================
Graphical User Interface
========================

Imspectorのグラフィカルインターフェース(GUI)は基本的な要素は次のようなものである(:ref:`fig_ui_overview`)。
一つあるいは複数の測定データは「measurement」と呼ばれるデータのかたまりに保存され、ウィンドウに表示される。
選択したウィンドウの撮像設定はリアルタイムに右側の制御ダイアログに反映される(:ref:`fig_ui_overview`)。
ライブダイアログや測定ウィンドウはワークスペース(Workspace)内でレイアウトを整理できる。
ウィンドウのレイアウトとハードウェアの設定は「workspace」ファイルで一括して保存しておける。
メニューバーも変更して保存することができる。

.. Each measurement may contain one or several measurement windows shown here in the image view (left) and the graph view (middle).
   The imaging settings are defined and shown in the live dialogs shown on the right (:ref:`fig_ui_overview`). Furthermore several drop
   down menus are available. The live dialogs and measurement windows can be arranged freely in the program workspace.
   The arrangement can be saved together with the hardware settings or as a workspace. The menu bar can be modified and saved.

.. _fig_ui_overview:
.. figure:: /images/ui/gui_overview.jpg
   :width: 14 cm
   :align: center

   Imspectorのウィンドウレイアウト例

.. toctree::
   :maxdepth: 2

   ui/colormaps
   ui/toolbars
