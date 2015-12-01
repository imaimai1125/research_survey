人流＆交通流＆機械学習関連の研究について，いまどういうものが流行っているのか
軽いサーベイを行ったので，備忘録
内容はまだ全く読んでないけど，サーチ数，引用数で並べてみた。
アブストからさらっと読んでみて、傾向を把握してみる．
* トップカンファのものについてはもうちょい増強してもいいのかもしれない．

## key word
- convolutional neural network
- recurrent neural network
- deep learning
- crowd dynamics 
- pedestrian
- traffic flow
- anomaly

## google scholarのキーワードサーチ結果
- 期間:2014-2015
- 対象:全般

|                | cnn  | rnn  | deep learning | spatio-temporal | machine learning | cell automaton | agent simulation | anomaly | time series | pattern recognition |
| :-:            | :--- | :-   | :-            | :-              | :-               | :-             | :-               | :-      | :-          | :-                  |
| traffic        | 1410 | 3540 | 19100         | 8620            | 16600            | 3650           | 16000            | 12600   | 57800       | 17200               |
| crowd dynamics | 305  | 587  | 16900         | 2290            | 14800            | 1070           | 6090             | 4340    | 17500       | 12100                     |
| pedestrian     | 780  | 408  | 5500          |						 2580            | 7410             | 1570           | 2910             | 1560    | 17800       | 14500                    |

 *** 
 
## 各領域において、citationが多い論文
### cnn traffic flow
- Deep architecture for traffic flow prediction: Deep belief networks with multitask learning
	- citation 8
	- http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=6786503

### cnn crowd dynamics
- Large-scale video classification with convolutional neural networks
	- citation 95
	- http://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Karpathy_Large-scale_Video_Classification_2014_CVPR_paper.pdf

### cnn pedestrian
- Simultaneous Detection and Segmentation
	- citation 97
	- http://rd.springer.com/chapter/10.1007/978-3-319-10584-0_20

### rnn traffic flow	
- Prediction of particulate matter at street level using artificial neural networks coupling with chaotic particle swarm optimization algorithm
	- citation 11
	- http://www.sciencedirect.com/science/article/pii/S0360132314001073

### rnn pedestrian
- Ten years of pedestrian detection, what have we learned?
	- citation 56
	- http://arxiv.org/pdf/1411.4304.pdf


### spatio-temporal traffic flow
- Spatio-temporal variation of urban ultrafine particle number concentrations
	- citation 10
	- http://km.aifb.kit.edu/sites/swc/2013/submissions/swc2013_submission_11.pdf
- Star-city: semantic traffic analytics and reasoning for city
	- citation 13
	- http://www.researchgate.net/profile/Inmaculada_Aguilera/publication/264460370_Spatio-temporal_variation_of_urban_ultrafine_particle_number_concentrations/links/53e382590cf2f874d20a0950.pdf
- Traffic volume forecasting based on radial basis function neural network with the consideration of traffic flows at the adjacent intersections
	- citation 4
	- http://www.researchgate.net/publication/264426964_Traffic_volume_forecasting_based_on_radial_basis_function_neural_network_with_the_consideration_of_traffic_flows_at_the_adjacent_intersections

### spatio-temporal crowd dynamics
- Measuring crowd collectiveness
	- citation 32
	- http://www.cv-foundation.org/openaccess/content_cvpr_2013/papers/Zhou_Measuring_Crowd_Collectiveness_2013_CVPR_paper.pdf
- Scene-independent group profiling in crowd
	- citation 11
	- http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=6909682&tag=1
- On measuring pedestrian density and flow fields in dense as well as sparse crowds
	- citation 5
	- http://rd.springer.com/chapter/10.1007/978-3-319-02447-9_34#page-1
- Opportunities in mobile crowd sensing
	- citation 29
	- http://ieeexplore.ieee.org/xpls/abs_all.jsp?arnumber=6871666

### spatio-temporal pedestrian
- Adaptive fusion of particle filtering and spatio-temporal motion energy for human tracking
	- citation 7
	- http://www.researchgate.net/profile/Huiyu_Zhou/publication/263857603_Adaptive_fusion_of_particle_filtering_and_spatio-temporal_motion_energy_for_human_tracking/links/54a2e1250cf257a63604dac5.pdf


### cellular automaton traffic flow 
- Event-driven queue-based traffic flow microsimulation
	- citation 40
	- http://trrjournalonline.trb.org/doi/abs/10.3141/2003-05

### cellular automaton crowd dynamics
- Towards realistic and effective Agent-based models of crowd dynamics
	- citation 10 
	- http://www.sciencedirect.com/science/article/pii/S0925231214007838
- Simulation of emotional contagion using modified SIR model: A cellular automaton approach
	- citation 4
	- http://www.sciencedirect.com/science/article/pii/S0378437114002386

### cellular automaton pedestrian
- Bridging the gap: From cellular automata to differential equation models for pedestrian dynamics
	- citation 8
	- http://www.sciencedirect.com/science/article/pii/S1877750314000738

### anomaly crowd dynamics
- Anomaly detection and localization in crowded scenes
	- citation 53
	- http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6531615
- hybrid long-range collision avoidance for crowd simulation 
	- citation 28
	- http://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6613491


### pattern recognition traffic flow
- Short-term traffic forecasting: Where we are and where we're going 
	- citation 48
	- http://www.sciencedirect.com/science/article/pii/S0968090X14000096

***

## 個人的に気になる
- Anomaly detection through spatio-temporal context modeling in crowded scenes
- Fully Convolutional Neural Networks for Crowd Segmentation
- Continuum modelling of pedestrian flows: From microscopic principles to self-organised macroscopic phenomena
- Spatio-temporal crowd density model in a human detection and tracking framework
- A floor field cellular automaton for crowd evacuation considering different walking abilities
- A simple stochastic cellular automaton for synchronized traffic flow

***

## 各学会・雑誌ごとの流行り
### CVPR
- 729 : Rich feature hierarchies for accurate object detection and semantic segmentation 
- 359 : Deepface: Closing the gap to human-level performance in face verification
- 195 : Large-scale video classification with convolutional neural networks
- 161 : Learning and transferring mid-level image representations using convolutional neural networks
- 176 : BING: Binarized normed gradients for objectness estimation at 300fps

### PRL:Physical Review Letters
- 1081 : First results from the LUX dark matter experiment at the Sanford Underground Research Facility
- 928 : Detection of B-mode polarization at degree angular scales by BICEP2
- 275 : Observation of high-energy astrophysical neutrinos in three years of IceCube data
- 270 : Observation of electron neutrino appearance in a muon neutrino beam
- 201 : Search for low-mass weakly interacting massive particles with SuperCDMS

### PRE:Physical Review E
- 68 : Degree mixing in multilayer networks impedes the evolution of cooperation
- 20 : Efficiently inferring community structure in bipartite networks
- 12 : Localization and centrality in networks
- 12 : Identification of core-periphery structure in networks
- 9 : Continuous-time random-walk approach to supercooled liquids. II. Mean-square displacements in polymer melts

### TGF:Traffic Granular and Flow
- 6 : Using bluetooth to estimate the impact of congestion on pedestrian route choice at train stations
- 2 : Pedestrian Route Choice by Iterated Equilibrium Search
- 2 : Multi-anticipative car-following behaviour: macroscopic modeling

### NIPS

- 130 : Learning deep features for scene recognition using places database
- 111 : Two-stream convolutional networks for action recognition in videos
- 78 : Deep learning face representation by joint identification-verification
- 62 : Joint training of a convolutional network and a graphical model for human pose estimation
- 43 : Depth map prediction from a single image using a multi-scale deep network


### ICML
- 583 : Learning policies for partially observable environments: Scaling up
- 283 : Efficient algorithms for minimizing cross validation error
- 222 : Hierarchical learning in stochastic domains: Preliminary results
- 125 : Learning symbolic rules using artificial neural networks
- 93 : MDL and categorical theories (continued)
