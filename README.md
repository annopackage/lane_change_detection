# 基础知识
## 基础
### 笛卡尔坐标系&frenet坐标系: [[数学推导](https://www.jianshu.com/p/630c19f2bb9a)]

## 开源数据集
- HighD dataset "2018 21st International Conference on Intelligent Transportation Systems (ITSC)" [[link](https://www.highd-dataset.com/)] [[paper](https://ieeexplore.ieee.org/abstract/document/8569552)] [[github](https://github.com/RobertKrajewski/highD-dataset)] [[format](https://www.highd-dataset.com/format)]
- inD dataset [[link](https://www.ind-dataset.com/)] [[paper](https://arxiv.org/abs/1911.07602)]
- round dataset [[link](https://www.round-dataset.com/)] [[paper]()]

## 资料
- [[自动驾驶行为预测](https://zhuanlan.zhihu.com/p/158951141)]
- [[行人的行为意图建模和预测](https://zhuanlan.zhihu.com/p/86184886)]


# Lane change detection
## 关键字
- Motion forecasting/prediction
- Trajectory Prediction
- Vehicle behavior prediction
## 其他词汇
- Occupancy Grid Maps[[zhihu](https://zhuanlan.zhihu.com/p/21738718)]
- BEV(Bird's eye view)
- HD maps
- geographic coordinate system
## Paper List
- "Fast lane changing computations using polynomials" "Proceedings of the 2003 American Control Conference" (2003) [[paper](https://ieeexplore.ieee.org/abstract/document/1238912)]
- "A survey on motion prediction and risk assessment for intelligent vehicles"(2014) [[paper](https://hal.inria.fr/hal-01053736/document)]
- "Lane Change Scheduling for Autonomous Vehicles"(2016) [[paper](https://www.sciencedirect.com/science/article/pii/S2405896316302063)]
- "Lane-Change Detection Based on Vehicle-Trajectory Prediction" (IEEE Robotics and Automation Letters 2017) [[paper](https://ieeexplore.ieee.org/abstract/document/7835731)]
- "Vehicle trajectory prediction by integrating physics-and maneuver-based approaches using interactive multiple models" (IEEE Transactions on Industrial Electronics 2017) [[paper](https://ieeexplore.ieee.org/abstract/document/8186191)]
- "Probabilistic vehicle trajectory prediction over occupancy grid map via recurrent neural network" (ITSC 2017) [[paper](https://ieeexplore.ieee.org/abstract/document/8317943)]
- "Sequence-to-Sequence Prediction of Vehicle Trajectory via LSTM Encoder-Decoder Architecture"(2018 IEEE Intelligent Vehicles Symposium (IV) 2018) [[paper](https://ieeexplore.ieee.org/abstract/document/8500658)]
- "Convolutional Social Pooling for Vehicle Trajectory Prediction"(CVPR 2018) [[paper](https://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w29/Deo_Convolutional_Social_Pooling_CVPR_2018_paper.pdf)]
- "Vehicle trajectory prediction based on motion model and maneuver recognition" (2013 IROS) [[paper](https://ieeexplore.ieee.org/abstract/document/6696982)]
- "Modeling Vehicle Interactions via Modified LSTM Models for Trajectory Prediction" (IEEE Access 2019) [[paper](https://ieeexplore.ieee.org/abstract/document/8672889)]
- "Non-local Social Pooling for Vehicle Trajectory Prediction" (IEEE Intelligent Vehicles Symposium (IV) 2019) [[paper](https://ieeexplore.ieee.org/abstract/document/8813829)]
- "Argoverse: 3D Tracking and Forecasting with Rich Maps" (CVPR 2019) [[paper](https://openaccess.thecvf.com/content_CVPR_2019/html/Chang_Argoverse_3D_Tracking_and_Forecasting_With_Rich_Maps_CVPR_2019_paper.html)] [[code1](https://github.com/argoai/argoverse-api)] [[code2](https://github.com/alliecc/argoverse_baselinetracker)] [[website](https://www.argoverse.org/index.html)]
- "Deep learning-based vehicle behavior prediction for autonomous driving applications: A review" (2020 IEEE Transactions on Intelligent Transportation Systems) [[paper](https://ieeexplore.ieee.org/abstract/document/9158529)]

## 近几年进展
- "TPNet: Trajectory Proposal Network for Motion Prediction" (CVPR 2020) [[paper](https://decisionforce.github.io/TPNet/)]
- "Learning Lane Graph Representations for Motion Forecasting" (ECCV 2020) [[paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123470528.pdf)] [[code](https://github.com/uber-research/LaneGCN)]
- "TNT: Target-driveN Trajectory Prediction" (CoRL（Conference on Robot Learning）2020) [[zhihu](https://zhuanlan.zhihu.com/p/267946225)]
- "VectorNet: Encoding HD Maps and Agent Dynamics from Vectorized Representation" (CVPR 2020) [[code](https://github.com/DQSSSSS/VectorNet)] [[zhihu](https://zhuanlan.zhihu.com/p/141665706)]

## leaderboard&benchmark
- [Argoverse-Motion-Forecasting-Competition](https://eval.ai/web/challenges/challenge-page/454/leaderboard/1279#leaderboardrank-10)

## Project List
- "lane-change-prediction-lstm" [[project](https://github.com/chitianhao/lane-change-prediction-lstm)]
- "DQN" [[project](https://github.com/MaxPRon/DQN_lane_change)]


## 参考
- [paper-with-code] (https://paperswithcode.com/task/trajectory-prediction/latest)
- [轨迹预测相关资源列表](https://bbs.cvmart.net/articles/642)