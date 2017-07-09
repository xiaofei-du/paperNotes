## Tracking Papers

### 2D Single Object Tracking (SOT)

- **RTT: Recurrently Target-Attending Tracking.** Zhen Cui, Shengtao Xiao, Jiashi Feng, Shuicheng Yan. CVPR (2016). \[[paper](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Cui_Recurrently_Target-Attending_Tracking_CVPR_2016_paper.pdf)\]
- **GOTURN: Learning to Track at 100 FPS with Deep Regression Networks.** David Held, Sebastian Thrun, Silvio Savarese. ECCV (2016). [[paper](https://arxiv.org/abs/1604.01802)]\[[project](http://davheld.github.io/GOTURN/GOTURN.html)\]\[[code](https://github.com/davheld/GOTURN)\]
- **Re3: Real-Time Recurrent Regression Networks for Object Tracking.** Daniel Gordon, Ali Farhadi, Dieter Fox. arXiv (2017). \[[paper](https://arxiv.org/abs/1705.06368)\]



### 2D Multiple Ojbect Tracking (MOT)

- **Online Domain Adaptation for Multi-Object Tracking.** Adrien Gaidon, Eleonora Vig. BMVC (2015). \[[paper](https://arxiv.org/abs/1508.00776)\]

- **Deep Tracking: Seeing Beyond Seeing Using Recurrent Neural Networks.** Peter Ondrúška and Ingmar Posner. AAAI (2016). \[[paper](https://arxiv.org/abs/1602.00991)\]\[[code](https://github.com/pondruska/DeepTracking)\]

- **End-to-end tracking and semantic segmentation using recurrent neural networks.** Peter Ondrúška, Julie Dequaire, Dominic Zeng Wang, Ingmar Posner. arXiv (2016). \[[paper](https://arxiv.org/abs/1604.05091)\]

- **Deep Tracking on the Move: Learning to Track the World from a Moving Vehicle using Recurrent Neural Networks.** Julie Dequaire, Dushyant Rao, Peter Ondrúška, Dominic Wang, Ingmar Posner. arXiv (2016). \[[paper](https://arxiv.org/abs/1609.09365)\]

- **Deep tracking in the wild: End-to-end tracking using recurrent neural networks.** Julie Dequaire, Peter Ondrúška, Dushyant Rao, Dominic Wang, Ingmar Posner. IJRR (2017). \[[paper](http://journals.sagepub.com/doi/abs/10.1177/0278364917710543)\]

- **A Multi-cut Formulation for Joint Segmentation and Tracking of Multiple Objects.** Margret Keuper, Siyu Tang, Yu Zhongjie, Bjoern Andres, Thomas Brox, Bernt Schiele. arXiv. (2016). \[[paper](https://arxiv.org/abs/1607.06317)\]

- **Multi-Person Tracking by Multicut and Deep Matching.** Siyu Tang, Bjoern Andres, Mykhaylo Andriluka, Bernt Schiele. BMTT (2016). \[[paper](https://arxiv.org/abs/1608.05404)\] :trophy:*Winner of the MOT Challenge ECCV 2016*

- **Joint Graph Decomposition and Node Labeling: Problem, Algorithms, Applications.** Evgeny Levinkov, Jonas Uhrig, Siyu Tang, Mohamed Omran, Eldar Insafutdinov, Alexander Kirillov, Carsten Rother, Thomas Brox, Bernt Schiele and Bjoern Andres. CVPR (2017). \[[paper](https://arxiv.org/abs/1611.04399)\]

- **LMP: Multiple People Tracking with Lifted Multicut and Person Re-identification.** Siyu Tang and Mykhaylo Andriluka and Bjoern Andres and Bernt Schiele. CVPR (2017). ​:trophy:​*Winner of MOT16 leaderboard*.

- **Multi-target Tracking with Strong and Weak Detections.** Ricardo Sanchez-Matilla, Fabio Poiesi and Andrea Cavallaro. BMTT (2016). \[[paper](http://www.eecs.qmul.ac.uk/~andrea/papers/2016_ECCVW_MOT_OnlineMTTwithStrongAndWeakDetections_Sanchez-Matilla_Poiesi_Cavallaro.pdf)\]

- **POI: Multiple Object Tracking with High Performance Detection and Appearance Feature.** Fengwei Yu, Wenbo Li, Quanquan Li, Yu Liu, Xiaohua Shi, Junjie Yan. BMTT (2016). \[[paper](https://arxiv.org/abs/1610.06136)\]

  ​:green_book:​_The paper points out the importance of high performance <u>detector</u> and <u>appearance feature</u>. They lead to the state-of-the-art results, even with a simple online tracker._

  - _The detector is based on Faster R-CNN, with additional training data includes ETHZ, Caltech and <u>self-collected suveillance dataset</u>._
  - _GoogLeNet-ish network is trained with multiple re-id datasets (PRW, Market-1501, VIPeR and CUHK03) using softmax and triplet loss._
  - _Simple online tracker with Kalman filter for motion prediction and Kuhm-Munkres for data association._

- **SORT:Simple Online and Realtime Tracking.** Alex Bewley, Zongyuan Ge, Lionel Ott, Fabio Ramos, Ben Upcroft. ICIP (2016). \[[paper](https://arxiv.org/abs/1602.00763)\]\[[code](https://github.com/abewley/sort)\]

  ​:green_book:​ *The online tracking framework in the paper focuses on frame-to-frame predication and association. It leverages the state-of-the-art detection results, and combines with a classic, simple yet efficient online tracking framework using Kalman filter as motion model and Hungarian alforithm for data asscociation.*

  - _Note that the appearance features are ignored in tracking to avoid adding overhead into the framework._
  - _The paper identifys the <u>detection quality</u> as a key factor incluencing the tracking performance. So rather than aiming to design a tracking framework which is robust to deteciton errors, it chooses to explore the power of advanced CNN to solve the detection problem directly._ 
  - _The simplicity of the design leads to <u>super fast speed</u>: 260Hz._  

- **DeepSORT: Simple Online and Realtime Tracking with a Deep Association Metric.** Nicolai Wojke, Alex Bewley, Dietrich Paulus. arXiv. (2017). \[[paper](https://arxiv.org/abs/1703.07402)\]\[[code](https://github.com/nwojke/deep_sort)\]

- **Online Multi-Target Tracking Using Recurrent Neural Networks.** Anton Milan, S. Hamid Rezatofighi, Anthony Dick, Ian Reid and Konrad Schindler. AAAI (2017). \[[paper](http://www.milanton.de/files/aaai2017/aaai2017-anton-rnntracking.pdf)\]\[[poster](http://www.milanton.de/files/aaai2017/aaai2017-anton-rnntracking-poster.pdf)\]\[[code](https://bitbucket.org/amilan/rnntracking)\]

- **Multiple Object Tracking: A Literature Review.** Wenhan Luo, Junliang Xing, Anton Milan, Xiaoqin Zhang, Wei Liu, Xiaowei Zhao and Tae-Kyun Kim. arXiv (2017). [[paper](https://arxiv.org/abs/1409.7618)]   

- **Tracking the Trackers: An Analysis of the State of the Art in Multiple Object Tracking.** Laura Leal-Taixé, Anton Milan, Konrad Schindler, Daniel Cremers, Ian Reid, Stefan Roth. arXiv (2017). \[[paper](https://arxiv.org/abs/1704.02781)\]




### 2D Pose Tracking

- **ArtTrack: Articulated Multi-person Tracking in the Wild.** Eldar Insafutdinov, Mykhaylo Andriluka, Leonid Pishchulin, Siyu Tang, Evgeny Levinkov, Bjoern Andres, Bernt Schiele. CVPR (2017). \[[paper](https://arxiv.org/abs/1612.01465v3)\]

- **PoseTrack: Joint Multi-Person Pose Estimation and Tracking.** Umar Iqbal, Anton Milan, Juergen Gall. CVPR (2017). \[[paper](http://pages.iai.uni-bonn.de/iqbal_umar/PoseTrack/PoseTrack_cvpr17.pdf)\]\[[project](http://pages.iai.uni-bonn.de/iqbal_umar/PoseTrack/)\]




### 3D MOT



### Others

- **Video Segmentation via Object Flow.** Yi-Hsuan Tsai, Ming-Hsuan Yang, Michael J. Black.  CVPR (2016). \[[paper](http://files.is.tue.mpg.de/black/papers/TsaiCVPR2016.pdf)\]\[[project](https://sites.google.com/site/yihsuantsai/research/cvpr16-segmentation)\]\[[video](https://www.youtube.com/watch?v=rlMXSrSHCZQ)\]\[[code](https://github.com/wasidennis/ObjectFlow)\]
- **Optical Flow in Mostly Rigid Scenes.** Jonas Wulff, Laura Sevilla-Lara, Michael J. Black. CVPR (2017). \[[paper](http://files.is.tue.mpg.de/black/papers/MRFlow.pdf)\]\[[video](https://www.youtube.com/watch?v=7hrTYWfgZF8&feature=youtu.be)\]
- **Video Propagation Networks.** Varun Jampani, Raghudeep Gadde, Peter V. Gehler. CVPR (2017). \[[paper](https://varunjampani.github.io/papers/jampani17_VPN.pdf)\]\[[project](https://varunjampani.github.io/vpn/)\]\[[code](https://github.com/varunjampani/video_prop_networks)\]

### Highlights

- [**Anton Milan**](http://www.milanton.de/)
- [**Workshop on Benchmarking Multi-target Tracking (BMTT)**](https://motchallenge.net/workshops/bmtt-pets2017/)
- **[Perceiving Systems at Max Planck Institue for Intelligent Systems](https://ps.is.tuebingen.mpg.de/publications)**

