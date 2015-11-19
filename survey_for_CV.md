

人流感知系論文たち
引き続き傾向を探るために2014以降で。

### title of paper
興味（☆☆☆☆☆）


#### 1. category (rough)
どういう種類の研究かざっくり
#### 2. publisher/publish year / 1st author / # of citations
出版元or学会/出版年/author/引用数
#### 3. summary
要約
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
	- 割と面白そうな画像がある。　アルゴリズムはかかれてない。

#### 4. other important citations
- [23][33] 群集行動を速度ベクトル場として表現するお話
- [35] scalingのお話

***
***
## 5.Abnormal Crowd Behavior Detection using Social Force Mode
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

[17]social force model



















## 11/18 サーベイすべきリストをとりあえず列挙(読むのは11/19)

### CVPRに出ていた論文たち（内容まとめをする）

- pedestrian detection aided by deep learning semantic tasks/7
- action recognition with trajectory pooled deep-convolutional descriptors/12
- Deeply learned attributes for crowded scene understanding/1
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


