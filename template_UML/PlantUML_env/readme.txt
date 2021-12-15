Visual Studio CodeでPlantUML

2019.05.08
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

●Visual Studio Code のインストール
　Visual Studio Code(https://code.visualstudio.com/) を開く
　[Download for Windows] を押してインストーラーをダウンロードする
　ダウンロードしたインストーラーを実行する
　例）VSCodeSetup-1.11.1.exe

●PlantUML のセットアップ
1. Java のインストール
　PlantUML の実行には、Javaの実行環境が必要となります。
　java.com(https://java.com/ja/) を開く
　[無料Javaのダウンロード]ボタンを押す
　[同意して無料ダウンロードを開始]を押し、インストーラーをダウンロードする
　ダウンロードしたインストーラーを実行する
　例）JavaSetup8u121.exe
2. Graphviz のインストール
　PlantUML が UML を描画するために使用しているソフトウェアです。

　Graphviz - Graph Visualization Software(http://www.graphviz.org/) を開く
　Download を開く
　License ページの末尾にある[Agree]を押す
　Download ページの Windows の Stable and development Windows Install packages をクリックする
　MSIファイルを選択してインストーラーをダウンロードする
　ダウンロードしたインストーラーを実行する
　例）graphviz-2.38.msi
　インストール先を変更した場合には、環境変数"GRAPHVIZ_DOT"でパスを指定する必要があるそうです。

3. PlantUML のインストール
　Visual Studio Marketplace で PlantUML をインストールします。

　Visual Studio Code を起動する
　"Ctrl + P" と入力して、Quick Open を開く
　Quick Open に ext install plantuml と入力して、Enter キーを押す install.png
　検索結果から PlantUML を選択し、[インストール]を押す PlantUML.png
　インストール完了後に[再度読み込む]を押して Visual Studio Code を再起動する

●実行環境
Windows 10 Pro(64bit)
Visual Studio Code 1.33.1
Java SE Runtime Environment 8 Update 121
Graphviz 2.38
PlantUML 2.11.0 (plugin)

●【参考URL】セットアップ～動作確認まで
Visual Studio Code で UML を描こう！
https://qiita.com/couzie/items/9dedb834c5aff09ea7b2

