# C#のPartial
partial型（C#リファレンス）  
同名のクラスを別ファイルに記述することができる。  
コンパイルされる時は１つのファイルに統合されて出力される。  

MSドキュメント  
部分型定義を使用すると、クラス、構造体、インターフェイス、またはレコーとの定義を複数のファイルに分割することができます。  
https://docs.microsoft.com/ja-jp/dotnet/csharp/language-reference/keywords/partial-type

https://youtu.be/PbtJt5tnnI8?t=137


# デザインパターン ：　オブザーバーパターン
キーワード：SubjectとObserver  
https://www.techscore.com/tech/DesignPattern/Observer.html/

---

# 緊急度と重要度を基準に齟齬との優先順位を見きわめる「時間管理のマトリックス」
||緊急度が高い|緊急度が低い|
|---|---|---|
|重要度が高い|第1領域<br>問題・課題の領域<br>納期の迫った仕事<br>顧客からのクレーム<br>重要な設備の故障<br>突発的な人員の不足<br>災害・事故への対処など|第2領域<br>質の高いの領域<br>今後に向けた準備と計画<br>リーダーなどの人材育成<br>取引先と発注先の検討<br>製品の品質改善<br>リスク対策など|
|重要度が低い|第3領域<br>見せかけの領域<br>重要ではない電話やメール<br>重要ではない打ち合わせ<br>突然の来客<br>重要でない差し迫った問題<br>効果の期待できない接待など|第4領域<br>うわさ話などの単なる暇つぶし<br>何もしない移動時間<br>何もしない待ち時間<br>将来的にプラスにならない旅費など|

https://sp-jp.fujifilm.com/future-clip/visualization/vol27.html

---

# 英単語・命名規則関連

データベースオブジェクトの命名規約  
https://qiita.com/genzouw/items/35022fa96c120e67c637

プログラミングでよく使う英単語のまとめ  
https://qiita.com/Ted-HM/items/7dde25dcffae4cdc7923

---

# 法線
normal  
曲線状の接円と接線が定義される点で接線に垂直な直線を法線という。  
平面曲線では一意に定まるが三次元では主法線（接円の面内）、陪（従）法線（同に垂直）を区別する。  
曲面の接平面と直交する直線を、面の法線といい、接点を通り接平面に含まれる任意位の直線に対する垂線という。  

---

# Sprite
スプライトは2Dグラフィックオブジェクトです。  
スプライトを用いることで、容易に2Dキャラクターオブジェクトが生成できるので、簡単に2Dゲーム等を作製することが可能です。


https://docs.unity3d.com/ja/2021.2/Manual/SpriteEditor.html

https://gimo.jp/glossary/details/sprite.html

---

# 機械学習における解釈性
|aa|aa|
|---|---|
|GLM（一般化線形回帰モデル）|aa|
|決定木|aa|
|Feature Importance|aa|
|Partial Dependence|aa|
|感応度分析|aa|

https://engineering.mercari.com/blog/entry/2019-12-24-070000/#1

https://hacarus.github.io/interpretable-ml-book-ja/interpretability-importance.html

---

Excelショートカット
|key|detail|URL|
|---|---|---|
|Ctrl + Shift + [|参照データの選択|---|
|Ctrl + Shift + ]|数式が入ったセルを選択|---|
|Ctrl + .]|---|https://www.youtube.com/watch?v=HuW7knrSzf8|
|Ctrl + Shift + \]|---|https://www.youtube.com/watch?v=MVbnZAvKDMM|


---

ツェッテルカステン  
ドイツの天才社会学者二クラス・ルーマンが発明したメモ術  


走り書きのメモは、およそ1日以内に見直して、あとで使える適切なメモに書き直す場合に限って有用なのです。  

永久に保存するメモは2種類だけ。  
文献メモ。メモが指し示している文献の本文こそが重要。  
注意を引いたアイデアについて、別の紙に短いメモをとる。  
文献の内容を詳しく書いたメモをとる。その裏面に、この内容はこの本の○ページ、これはこの本の△ページ、と書いて、読んだ内容を集める文献管理用のツェッテカステンに入れる。  

そして、文献管理用のメモをしまう前に、メモした内容を読み返し、自分の思考の流れとの関連性について検討し、それを元にメインのメモを執筆します。  
それを永久保存版のメモとして、メインのツェッテルカステンに格納しました。  

メモは「自分の言葉で書く」からこそ価値がでる。  
https://president.jp/articles/-/52864

---

禁じられた遊びは  
森羅万象に触れたことにさえ  
気づくことのできない  
知ることさえ許されない  
果ての虚無  
...今さら後悔はしない  
君に笑われたくないから  

森羅万象に触れて～驚～ 幽閉サテライト  

----

叶えたい夢がある  
譲れないその熱情  
今私を動かす  
運命さえ打ち砕く  
誰にも邪魔させない  
わかってくれなくていい  
自分で決めた道を  
ただ信じて進むだけ  

証 Amateras Records  

----

自分はどんな人間になり、何を実現させたいかを自分自身に問い続け考え続ける。

???  

----

# Pythonライブラリ
- Transformers
    - Transformersとは、最先端の自然言語（テキスト）処理を行うためのライブラリ
    - Transformersでできること
        - 分類
        - テキスト生成
        - 質疑応答
        - 要約
        - 翻訳 etc...
    - BERT, GPT-2などの最先端アルゴリズムに対応
    - https://huggingface.co/transformers/
- MediaPipe
    - MediaPipeとは、Google社が提供するストリーミングメディア（動画等）を利用した学習パイプラインを構築するためのフレームワーク
        - 機械学習パイプラインとは、データ収集→データ処理→モデル（再）学習→再学習済モデルによる推論、といった一連の処理を自動化したシステム
    - 顔の形状推定、顔検出、ハンドトラッキング、物体検出等における高精度なモデルを提供。高精度。
    - メディア周りの機械学習を実装した→MediaPipe
    - https://google.github.io/mediapipe/
- PyCaret
    - PyCaretは、たった数行で機械学習を実装できるライブラリであり、機械学習の一連の処理を自動化する「AutoML」をサポートしている
    - データの前処理自動化、モデル（アルゴリズム）の比較自動化、チューニングの自動化などを行ってくれる超便利最強ライブラリ
    - https://pycaret.org/
- FastAPI
    - FastAPIとは、Pythonの標準である型ヒントに基づいてPython3.6以降でAPIを構築するための、モダンで、高速（高パフォーマンス）な、Webフレームワーク
    - コードが直感的でわかりやすい、公式ドキュメンの情報が豊富、自動ドキュメント生成機能、バリデーション（検証）機能の実装が簡単という特徴があります
    - 初学者が、PythonでAPI開発を行うには間違いなくFastAPI一択
    - https://fastapi.tiangolo.com/ja/
- SQLModel
    - SQLModelとは、データベースを操作するためのライブラリであり、型ヒントに基づき、PydanticとSQLAlchemyを利用している
    - 直感的で使いやすく、互換性が高く、堅牢であるように設計されている
    - 比較的新しいライブラリであるが、FastAPI開発者が開発しており、FastAPIの使いやすさ、素晴らしさからも期待
    - https://sqlmodel.tiangolo.com/
