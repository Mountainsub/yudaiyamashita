<!Documenttype HTML>
<style>
        body {
            background-color: #00ff00
        }
 

 </style>
<body>
<ul>
理念を持って今を生きる性格で, チャレンジ精神と好奇心の強い気質で自己研鑽しつつ生きてきました. 例として難解な内容の修士論文がきちんと書けるような人材へと自己実現です. 当初は医学部への進学を考えていましたが, 私はあくまで受験を定期テストの延長上のものと考えており,  予備校の空気感や携帯端末やインターネット発展の影響を全く考えない受験システムに嫌気がさし, 長考の末今の時代先見性があると考え数学科への進学を決意しました.　

約3年後,東日本大震災やリーマンショック後の世のあり方を考えない一部社員に幻滅し, 精神的な葛藤の上少数派の世界,大学院への進学を決意しました. 私が数学で最も得意な分野が抽象的な代数学であり, 大学院入試に受かるため一度学部課程の数学を復習し,演習を積みました.こうした紆余曲折的な挑戦や人生経験の末, 修士論文や数学のプレゼンテーションができる人間に成長できました.
</ul>
<br>
<br>
<br>
・Pheumonia[Kaggle Notebook上で稼働するPytorchによる肺炎検知アプリケーション]
<br>
<br>
<du>
Kaggle Notebook(旧Kernel)でディープラーニングを実装しました。Pytorchを主に使っていて、他にはnumpy, pandas, matplotlib, torchvision, Orderdict, tqdmをインポートしています。演算装置はGPUです。
データセットは胸部のレントゲン写真です。あらかじめ訓練データと検証データ、テストデータに分かれています。
教師あり学習になります。入力したデータに対してテンソル化して、images, labelsから学習モデルを作ることになります。最終的にNormalとPheumonia(肺炎)の可能性を棒グラフ化します。

ミニバッチ法による学習で20~30分程度で学習が完了します。インポート、ローディング、データ拡張の後に、学習を行います。
Normalを0, Pheumoniaを1としてＤataFrame化とラベリング化します。

vgg16は13層のCNNと3層の全結合層からなるライブラリであり、これを使用してモデル学習を行います。

この後は棒グラフを出力する関数を設定し、データを恣意的に選んで肺炎の可能性を棒グラフで出力します。

成果として、医学的知見がなくとも、容易に可能性を検知できる点だと考えています。
</du>
<br>
<br>
<br>
・React-Typescript-Firebase[Firestoreと連動したReact/Typescriptのユーザー認証アプリケーション]
<br>
<br>
<du>
Typescript, React, Firebaseを用いてログインなどの認証操作を行うアプリケーションを作りました。

Cloud Firestore,Authentication,Hosting機能とReact Hooks/TypeScriptを使ってToDoアプリのハンズオンを行います。具体的にはReact-router, react-dom, material-uiなどをインポートし, ReactとFirebase(Firestore)を連動して、レンダリングによりFirebaseのデータベース、Cloud Firestoreを操作し、タスク操作を行ってユーザー認証を行うようにします。

・Pytorch-CNN-Heroku 〔Pytorchによる、CIFAR-10を使った学習モデルによる画像認識アプリ〕

Pytorchを使って、データセットCIFAR-10を使った学習モデルからCNN、畳み込みニューラルネットワークで画像認識を行います。「ファイルを選択」ボタンから入力された画像データから送信ボタンを押すと、推論結果を「〇％で・・・です」のように高い確率順に3つ出力します。(蛙、飛行機、犬など)

ミニバッチ法と自分で設定した層構造によりラーニングを行います。

Anacondaで仮想環境を構築し、Herokuにてデプロイを行いました。

別件でGoogle Cloud Platformにより、仮想マシンを構築し、VMインスタンスを作成、Google App Engineでデプロイしました。
</du>
  
</body>
<!---
yudaiyamashita/yudaiyamashita is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
