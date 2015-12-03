

人流感知系論文たち
引き続き傾向を探るために2014以降で。

## title of paper
興味（☆☆☆☆☆）
#### 1. category (rough)
#### 2. publisher/publish year / 1st author / # of citations
#### 3. summary
#### 4. other important citations

***** 
*****

## 1.Crowd Detection and Occupancy Estimation Through Indirect Environmental Measurements 
☆☆

#### 1. category (rough)
statistical analysis
#### 2. publisher publish year / 1st author / # of citations
EuCAP / 2014 / Federico Viani / 2
#### 3. summary
センサーを使ってhumidityとtemperatureの値からそのフロアのoccupancyを推測する？みたいな。
#### 4. other important citations


*****
*****

## 2.Unsupervised dense crowd detection by multiscale texture analysis
☆☆☆☆☆
#### 1. category (rough)
画像認識・人物認識

#### 2. publish year / 1st author / # of citations
Pattern Recognition Letters / Antoine Fagette / **4**
#### 3. summary
事前確率なしの状態で人物を検出できるかどうかの研究。
特徴量ベクトルを抽出してbinary classification。
K-meansに比べて混雑時の群集抽出精度はすばらしく良い。精度競争。わりと使えるかも。

#### 4. other important citations

*****
****
## 3.Social Attribute-Aware Force Model: Exploiting Richness of Interaction for Abnormal Crowd Detection
☆☆☆☆
#### 1. category (rough)
画像処理, 異常検知
#### 2. publisher/publish year / 1st author / # of citations
Transactions on circuits and systems for video tech./2015/yanhao zhang/4
#### 3. summary
- abnormal crowd behaviorを見つけたい。ミクロとマクロ両方見ながら推定しちゃおう。
- 歩行者たちは各歩行者の属性を検知しているはず。
- social semantic influence on the crowd interaction behaviorsを考慮
- social force と組み合わせるのはまだまだ現役感ある

#### 4. other important citations

****
****
## 4.cross-scene crowd counting via deep convolutional neural networks
☆☆☆☆
#### 1. category (rough)
画像処理, Deep learning
#### 2. publisher/publish year / 1st author / # of citations
CVPR/2015/Cong Zhang/4
#### 3. summary
- 特定の状況における精度を上げようという感じ。（crowd behaviorのひとつに着目）
- 交差シーンはtrainingセットがイマイチ。変わりにcrowd densityとcrowd countという点からCNNを学習させる。
	- 割と面白そうな画像がある(figure7とかはいい感じのcrowd detectionができてそう)。　アルゴリズムはかかれてない。

#### 4. other important citations
- [23][33] 群集行動を速度ベクトル場として表現するお話
- [35] scalingのお話

***
***
## 5. Abnormal Crowd Behavior Detection using Social Force Mode
☆☆☆☆☆
#### 1. category (rough)
画像認識, Social Force Model
#### 2. publisher/publish year / 1st author / # of citations
CVPR/2009/Ramin Mehran/552
#### 3. summary
- ビデオを使ってsocial force modelを考慮し、異常行動を検出する。
- 点をグリッド上に並べ、SFの流れ場みたいなのを作り、bag of wordsアプローチでフレームを分類する。
- SFMを画像認識と組み合わせることで、集団のダイナミクスを高精度に捕らえられるようになった+精度もとても良かった
- particle advection->social force ->bag of force -> anomaly detection
- social forceのベクトルを可視化して解析する手法は割と昔からありそうな予感。。調べてみよう。

#### 4. other important citations
- インパクトの大きな論文だったようなので、もう少し調べたい。（被引用の詳細など）
- [17]social force model

***
***

## 6. pedestrian detection aided by deep learning semantic tasks
☆☆☆
#### 1. category (rough)
画像認識・人物検出
#### 2. publisher/publish year / 1st author / # of citations
CVPR/2015/Yonglong Tian/7
#### 3. summary
- 人物検出。人や景色は様々な種類があるため難しい。人の持つ特徴量（バッグを持っている、男・女）などを抽出することで
より人物検出の上げようという試み。精度向上のためにはHaar,HOGなどの既存の特徴量を使うものもあるが、精度向上の最適化を行えるものではない。Deep learningを使った手法は特徴量を抽出してくれるが、二値分類しかされてないので歩行者のリッチなバリエーションに答えることは不可能だった。
- TA-CNNという手法を考案し、複数の特徴・属性を同時に考えることが可能になった。それを使うことで、人物検出の精度が向上した。

#### 4. other important citations
[29] ConvNet : CNN for pedestrian detection

[22] Ouyang : jointly learned features and the visibly of different body parts to handle occlusion.

***
***

## 7. Deeply learned attributes for crowded scene understanding
☆☆☆
#### 1. category (rough)
人流動画DB作成。属性付与
#### 2. publisher/publish year / 1st author / # of citations
CVPR/2015/Jing Shao/1
#### 3. summary
- What/ Where/ Whyを特徴量に持つ人流データセットを構築した。
- multi-task learning deep modelを発展させた

データセットを構築したというところの評価は大きい気がする。
今後データを使いたいときに参考になるかも？
#### 4. other important citations

***
***


## 8. The walking behavior of pedestrian social groups and its impact on crowd dynamics
☆☆☆☆☆

#### 1. category (rough)
人流解析（グループ中心）
#### 2. publisher/publish year / 1st author / # of citations
PLOS ONE/2010/Mehdi Moussaid/355
#### 3. summary
- 群集の７割はグループで動いている->これらの動きを見ることは非常に重要
- 1500個のグループを見て、分析
- モデルを作って検証
	- 歩く速度と社会的な力（群集が集まる力）の間にtradeoffを確認

まさにやりたかったことに近い。逆に言えばここに書かれているもの、これをciteしている論文はよむ価値があるかも。
また、引用数も多いので、ここで書かれていることを傍証として物事を進めてもいい気がする。

#### 4. other important citations

## 9. Pedestrian group behavior analysis under different density conditions
☆☆☆☆
#### 1. category (rough)
人流解析（グループ中心）
#### 2. publisher/publish year / 1st author / # of citations
Transportation Research Procedia/2014/Francesco Zanlungo(Kyoto univ.)/2
#### 3. Background
世の中の群集の多くて85%はグループで行動しているにもかかわらず（増えてる。。。）それを考慮した群集運動の研究が少ない。
そのため、きちんと考慮することでより正確な予測が行えるようになる。
#### 4. summary
少人数グループが群集に与える影響について考察。手法は9.のものを数学的にbrush upしたものになっている。
モデルとしては非ニュートンポテンシャルを使っている。
有用性は高密度下で検討をしているところ
#### 5. other important citations

***
***
## 10. Floor Fields for Tracking in High Density Crowd
☆☆☆☆☆
#### 1. category (rough)
人流検知，動線トラッキング，画像解析
#### 2. publisher/publish year / 1st author / # of citations
Computer Vision ECCV/Saad Ali/2008//272
#### 3. background
- 群衆の中から個々の動きを追うのは非常にchallengingな問題

#### 4. summary
scene structure based force modelという手法を用いて個人のトラッキングに成功した。
3種類のfloor field

- SFF(stastic floor field)
- DFF(Dynamic floor field)
- BFF(boundary floor field)

を駆使して高密度での人流を捕らえた。（この手法自体はシミュレーションの分野で昔からあるが
、今回はCVと結びつけたところが新規性なのかな？）

#### 5. other important citations
- [10]object trackingに関するsurvey論文(2006だからちょっと古い。。。？)

***
***

## 11. From Participatory Sensing to Mobile Crowd Sensing
☆☆
#### 1. category (rough)
センシング技術
#### 2. publisher/publish year / 1st author / # of citations
IEEE/2014/Bin Guo/37
#### 3. background
社会や都市のマネジメントには、適切な意思決定をするために都市や共同体のダイナミクスをモニタリングすることが大事である。(people-centric service delivery)
今までそれはワイヤレスセンサネットワークで行おうとしていたが、範囲がカバーしきれない、取り付け・維持コストが高い、スケーラビリティが低い
#### 4. summary
Mobile Crowd Sensing(MCS)を使うことで人々の動向をセンシング。

1. そこにいる人達をみんなセンシング可能
1. ネットワーク・モバイルセンサの両方からデータを集める

ニンゲンと機械の知識をあわせた概念。今後のworkとしては

1. データを集めるためのframeworkをきちんと作る
1. インフラとモバイルのネットワークをうまく両方扱えるようにする。
1. センシングの分野に閉じず、様々な人とかかわりあう
1. 様々な状況に対応するために異なるシチュエーションからのデータも統合する。

概念的なお話だし、すぐ使えるかといわれると。。。
IoT的な考え方な印象なので、考え方の参考にはなるかも？

#### 5. other important citations

***
***

## 12. Action Recognition with Trajectory-Pookled Deep-Convolutional Descriptors
☆☆☆
#### 1. category (rough)
画像認識/action recognition
#### 2. publisher/publish year / 1st author / # of citations
CVPR/2015/Limin Wang/12
#### 3. background
Human action recognitionはvideo監視などへの応用・映像解析・human computer interactionなどが見込めるために最近流行しているが、
依然として現実映像に適用しようとすると難しい問題が多い。

- hand-craftedの問題点：visual representationの最適化はできない。
- deep learned featuresの問題点:時間と空間の区別を無視している。そのせいでhand-craftdデータより精度がでなかったりする。

#### 4. summary
visual representationには2大潮流がある。（Figure1のイメージがわかりやすい。)しかし、３．でも書いているようにそれぞれに問題点があるので。本研究はその2大潮流のhybridを目指した
trajectory-pooled deep-convolutional descriptor(TDD)と呼ばれる手法を用いる。（図2が全体包括の図）


#### 5. other important citations
***
***


## 13. Taking Deeper Look at Pedestrians
☆☆☆☆
#### 1. category (rough)
画像認識（CNN）
#### 2. publisher/publish year / 1st author / # of citations
CVPR/2015/Jan Hosang(Max Plank Institute)/11
#### 3. background
歩行者検出は車の安全、監視システムやロボティクスにかかわっている。今までのneuralnetを使った歩行者検出は特別な目的のデザインが多かった。
（hand-crafted features, occlusion modelingなど）

#### 4. summary
最近はAdaboostを用いた手法が盛んになっている。
本研究ではCNNのパラメータやトレーニングデータの特徴を精査し、調整することで**Caltech pedestians**というデータセットを用いたときのtop performanceを示す。

CNNの中身がどういう役割を担っているかについて調べているという感じの研究。ぱっと見人流特化でもなさそう。（データセットがpedestrianなだけでは？)
CNN関連の手法を探るときには良いかも。

#### 5. other important citations***
内容を見ればCNN関連技術の詳細がわかるかもしれない。


***
***

## 14. L_0 Regularized Stationary Time Estimation for Crowd Group Analysis
☆☆☆☆☆
#### 1. category (rough)

#### 2. publisher/publish year / 1st author / # of citations
IEEE CVPR/2014/Shuai Yi/6
#### 3. background
**surveillance**のために（この単語が歩行者検出のintroductionで良く出てくる（監視・防犯））
既存研究はcrowd内の動きのパターンや他者とのインタラクションについての研究が多かった。その一方で**止まっている**歩行者の研究はあまりやられていなかった。

止まっているグループのほうが動いているグループよりも群集に与える影響は大きいはずだ。
#### 4. summary
映像から人流を分析し、どこに人がたまりやすいか・どのくらいの時間人がたまっているかを予測する。

はじめは3D stationary time mapを時空間につくり、（時間ごとの差分を元に）解析をしていたが、精度がなかなか上がらなかった。
（figure4にchallengesが載っている）

本研究は

- ロバストなstationary group estimationについて提案した。
- sparse constraints in spatial and temporal dimensions are jointly added to construct a 3D stationery-time map
　(イマイチ意味がわからない)
- stationary groupの種類を分類した（figure. 2に詳しい)

などの新規性がある。

発想は面白いのでもう少しちゃんと読んでみるべきな気がしている。
止まっているではなく、急いでいる・そうでないなどの分類もできるやも。

#### 5. other important citations
[16] 止まっているグループがtraffic patternに多大な影響を及ぼしていることに言及した論文

***
***
## 15. Group Affiliation Detection Using Model Divergence
#### 1. category (rough)
センシング, クラスタリング（グループ）
#### 2. publisher/publish year / 1st author / # of citations
DGAD/2014/Dawd Gordon/3
#### 3. background
人は公共エリアで過ごす時間の70%を他の人と一緒にすごしている。
グループを理解することはいろいろなところでメリットがある([10])
ニンゲンがグループというものをどういう風に認知して、グループを形成するかを理解し、グループの振る舞いをdetectするのが目的。

#### 4. summary
心理学的な知見を生かしてグループがどういう風に振舞うのかの特徴を考えていく。モデルの評価にP2P assesmentを用いて、similarityを
計算していく(Divergence Based Affiliation Detection)。モデルには、ガウス分布を用いたもの(DBAD-P)と、観測のヒストグラムを使うもの（DBAD-H)を用いた。

結果として、P2P social procimity between individualsを少ないパラメータを使うことで推測できた。


#### 5. other important citations
結構心理的なお話をしてくれているものも多かったりする？？？ので、そういう要素を取り入れるときには便利かも。
現象理解のための論文なのかな？理解するメリットは他論文**[10]**に書かれているらしいのでチェックしておく。



******
***
## 16. aaa
#### 1. category (rough)
#### 2. publisher/publish year / 1st author / # of citations
#### 3. background
#### 4. summary
#### 5. other important citations
***
***
## 17. aaa
#### 1. category (rough)
#### 2. publisher/publish year / 1st author / # of citations
#### 3. background
#### 4. summary
#### 5. other important citations
***
***
## 18. aaa
#### 1. category (rough)
#### 2. publisher/publish year / 1st author / # of citations
#### 3. background
#### 4. summary
#### 5. other important citations
***
***
## 19. aaa
#### 1. category (rough)
#### 2. publisher/publish year / 1st author / # of citations
#### 3. background
#### 4. summary
#### 5. other important citations
***
## 20. aaa
#### 1. category (rough)
#### 2. publisher/publish year / 1st author / # of citations
#### 3. background
#### 4. summary
#### 5. other important citations
## 11/19 サーベイすべきリストをとりあえず列挙(読むのは11/30)

### CVPRに出ていた論文たち（内容まとめをする）

- action recognition with trajectory pooled deep-convolutional descriptors/12
- 
-
- taking a deeper look at pedestrians/11
- Histograms of oriented gradients for human detection/12728??

###検索ワード　group detection crowd で関連しそうな話題（最近の＆impact大きそうなの中心）

-　Dynamic phase and group detection in pedestrian crowd data using multiplex visibility graphs/0
-　Sparse people group and crowd detection using spatial point statistics in airborne images/0
-　Crowd Detection in Airborne Images using SpatialPoint Statistics/0
- From Participatory Sensing to Mobile Crowd Sensing /37
- Group Affiliation Detection Using Model Divergence for Wearable Devices/3
- Pedestrian detection and tracking through hierarchical clustering/0
- Profiling stationary crowd groups/2
- L0 regularized stationary time estimation for crowd group analysis/5
- Macroscopic analysis of crowd motion in video sequences/0
- Crowd Fraud Detection in Internet Advertising/1
- Crowd analysis in non-static cameras using feature tracking and multi-person density/0
- Automatically Detecting the Small Group Structure of a Crowd/63
- Detection and Tracking of Shopping Groups in Stores /92
- Reduced-Complexity Detection Algorithms for Systems Using Multi-Element Arrays /114
- Group Detection for Synchronous Gaussian Code-Division Multiple-Access Channels /224
- Crowd detection in video sequences/51
- Crowd Detection with a Multiview Sampler/33
- Crowd detection from still images/39
- Real-time crowd detection based on gradient magnitude entropy model/0


