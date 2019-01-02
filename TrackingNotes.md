## Object Tracking

## Datasets

### 2D Single Object Tracking (SOT)

- [**VOT Challenges (2013-2017)**](http://www.votchallenge.net/index.html)

  > The VOT challenges provide the visual tracking community with a precisely defined and repeatable way of comparing short-term trackers as well as a common platform for discussing the evaluation and advancements made in the field of visual tracking.

- [**Visual Tracker Benchmark (OBT)**](http://cvlab.hanyang.ac.kr/tracker_benchmark/index.html)

  > The full benchmark contains 100 sequences from recent literatures and code of the benchmark evaluation of online visual tracking algorithms..

  - **Online Object Tracking: A Benchmark.** Yi Wu, Jongwoo Lim and Ming-Hsuan Yang. CVPR (2013). \[[paper](http://faculty.ucmerced.edu/mhyang/papers/cvpr13_benchmark.pdf)\]
  - **Ojbect Tracking Benchmark.** Yi Wu, Jongwoo Lim and Ming-Hsuan Yang. PAMI (2015). \[[paper](http://faculty.ucmerced.edu/mhyang/papers/pami15_tracking_benchmark.pdf)\] 



### 2D Multiple Ojbect Tracking (MOT)

- [**EPFL Dataset (2008)**](http://cvlab.epfl.ch/data/pom/#terrace)

  > Multi-camera Pedestrian Videos: All of the sequences feature several synchronised video streams filming the same area under different angles.

- [**ETHZ Sequences (2008)**](https://data.vision.ee.ethz.ch/cvl/aess/dataset/) 

  > Robust Multi-Person Tracking from Mobile Platforms

- [**TUD Datasets (2010)**](https://www.d2.mpi-inf.mpg.de/node/428)

  > The dataset "TUD Multiview Pedestrians" was used to evaluate single-frame people detection and viewpoint estimation. The "TUD Stadmitte" sequence was used to demonstrate 3D pose estimation performance in real-world street conditions.

- [**KITTI Ojbect Tracking (2012)**](http://www.cvlibs.net/datasets/kitti/eval_tracking.php)

  > The object tracking benchmark consists of 21 training sequences and 29 test sequences. The goal in the object tracking task is to estimate object tracklets for the classes 'Car' and 'Pedestrian'.	

  - **Are we ready for Autonomous Driving? The KITTI Vision Benchmark Suite.** Andreas Geiger, Philip Lenz and Raquel Urtasun. CVPR (2012). \[[paper](http://www.cvlibs.net/publications/Geiger2012CVPR.pdf)\]

- [**MOT Benchmark (2015-2017)**](https://motchallenge.net/)

  > This benchmark contains video sequences in unconstrained environments filmed with both static and moving cameras.

  - **MOTChallenge 2015: Towards a Benchmark for Multi-Object Tracking.** Laura Leal-Taixé, Anton Milan, Ian Reid, Stefan Roth, and Konrad Schindler. arXiv (2015). [[paper](https://arxiv.org/abs/1504.01942)\]
  - **MOT16: A Benchmark for Multi-Object Tracking.** Anton Milan, Laura Leal-Taixé, Ian Reid, Stefan Roth, and Konrad Schindler. arXiv (2016). [[paper](https://arxiv.org/abs/1603.00831)\]

- [**DukeMTMCT (2016)**](https://motchallenge.net/data/DukeMTMCT/)

  > This dataset is a new, manually annotated, calibrated, multi-camera data set recorded outdoors on the Duke University campus with 8 synchronized cameras.

  - **Performance Measures and a Data Set for Multi-Target, Multi-Camera Tracking.** Ergys Ristani, Francesco Solera, Roger S. Zou, Rita Cucchiara, and Carlo Tomasi. arXiv (2016). \[[paper](https://arxiv.org/abs/1609.01775)\]

- [**PETS (2009-2017)**](https://motchallenge.net/data/PETS2017/)

  > Low-density detection, tracking and video analysis.

  - **PETS 2014: Dataset and Challenge.** Luis Patino and James Ferryman. AVSS (2014). \[[paper](http://ieeexplore.ieee.org/document/6918694/)\]\[[dataLink](http://www.cvg.reading.ac.uk/PETS2014/)\]
  - **PETS 2016: Dataset and Challenge.** Longzhen Li, Tahir Nawaz and James Ferryman. AVSS (2015). \[[paper](http://ieeexplore.ieee.org/document/7301741/)\]\[[dataLink](http://www.cvg.reading.ac.uk/PETS2015/)\]
  - **PETS 2016: Dataset and Challenge.** Luis Patino, Tom Cane, Alain Vallee and James Ferryman. CVPR (2016). \[[paper](http://www.cv-foundation.org/openaccess/content_cvpr_2016_workshops/w20/papers/Patino_PETS_2016_Dataset_CVPR_2016_paper.pdf)\]\[[dataLink](http://www.cvg.reading.ac.uk/PETS2016/)\]



### 2D Pose

- [**PoseTrack (2017)**](https://posetrack.net/)

  > PoseTrack is a new large-scale benchmark for multi human pose estimation and tracking in video. We provide a publicly available training and validation set as well as an evaluation server for benchmarking on a held-out test set.

- [**Human Skeletal System Keypoints Detection (2017)**](https://challenger.ai/competition/keypoint?lan=en)

### 3D MOT

- [**MOT Benchmark (2015)**](https://motchallenge.net/data/3D_MOT_2015/)

  > This benchmark contains video sequences with available camera calibration, enabling tracking in world coordinates.

- [**WILDTRACK**](http://cvlab.epfl.ch/data/wildtrack) \[[paper](https://arxiv.org/abs/1707.09299)\]

  > The dataset brings multi-camera detection and tracking methods into the wild. It meets the need of the deep learning methods for a large-scale multi-camera dataset of walking pedestrians, where the cameras’ fields of view in large part overlap. Its high precision joint calibration and synchronization shall allow for development of new algorithms that go beyond what is possible with currently available data-sets.

### 3D Pose

- [**TUD Datasets (2010)**](https://www.d2.mpi-inf.mpg.de/node/428)

  > The "TUD Stadmitte" sequence was used to demonstrate 3D pose estimation performance in real-world street conditions.

## Papers

### 2D Single Object Tracking (SOT)

- [RTT: Recurrently Target-Attending Tracking](http://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Cui_Recurrently_Target-Attending_Tracking_CVPR_2016_paper.pdf). CVPR (2016).
- [GOTURN: Learning to Track at 100 FPS with Deep Regression Networks](https://arxiv.org/abs/1604.01802). ECCV (2016). \[[project](http://davheld.github.io/GOTURN/GOTURN.html)\]\[[code](https://github.com/davheld/GOTURN)\]
- [Re3: Real-Time Recurrent Regression Networks for Object Tracking](https://arxiv.org/abs/1705.06368). arXiv (2017).
- [Fully-Convolutional Siamese Networks for Object Tracking](https://arxiv.org/abs/1606.09549). ECCV (2016). \[[project](https://www.robots.ox.ac.uk/~luca/siamese-fc.html)\]
- [End-to-end Representation Learning for Correlation Filter Based Tracking](https://arxiv.org/abs/1704.06036). CVPR (2017) \[[project](http://www.robots.ox.ac.uk/~luca/cfnet.html)\]



### 2D Multiple Ojbect Tracking (MOT)

- **Online Domain Adaptation for Multi-Object Tracking.** Adrien Gaidon, Eleonora Vig. BMVC (2015). \[[paper](https://arxiv.org/abs/1508.00776)\]

- **Deep Tracking: Seeing Beyond Seeing Using Recurrent Neural Networks.** Peter Ondrúška and Ingmar Posner. AAAI (2016). \[[paper](https://arxiv.org/abs/1602.00991)\]\[[code](https://github.com/pondruska/DeepTracking)\]

- **End-to-end tracking and semantic segmentation using recurrent neural networks.** Peter Ondrúška, Julie Dequaire, Dominic Zeng Wang, Ingmar Posner. arXiv (2016). \[[paper](https://arxiv.org/abs/1604.05091)\]

- **Deep Tracking on the Move: Learning to Track the World from a Moving Vehicle using Recurrent Neural Networks.** Julie Dequaire, Dushyant Rao, Peter Ondrúška, Dominic Wang, Ingmar Posner. arXiv (2016). \[[paper](https://arxiv.org/abs/1609.09365)\]

- **Deep tracking in the wild: End-to-end tracking using recurrent neural networks.** Julie Dequaire, Peter Ondrúška, Dushyant Rao, Dominic Wang, Ingmar Posner. IJRR (2017). \[[paper](http://journals.sagepub.com/doi/abs/10.1177/0278364917710543)\]

- **A Multi-cut Formulation for Joint Segmentation and Tracking of Multiple Objects.** Margret Keuper, Siyu Tang, Yu Zhongjie, Bjoern Andres, Thomas Brox, Bernt Schiele. arXiv. (2016). \[[paper](https://arxiv.org/abs/1607.06317)\]

- **Multi-Person Tracking by Multicut and Deep Matching.** Siyu Tang, Bjoern Andres, Mykhaylo Andriluka, Bernt Schiele. BMTT (2016). \[[paper](https://arxiv.org/abs/1608.05404)\] :trophy:*Winner of the MOT Challenge ECCV 2016*

- **Joint Graph Decomposition and Node Labeling: Problem, Algorithms, Applications.** Evgeny Levinkov, Jonas Uhrig, Siyu Tang, Mohamed Omran, Eldar Insafutdinov, Alexander Kirillov, Carsten Rother, Thomas Brox, Bernt Schiele and Bjoern Andres. CVPR (2017). \[[paper](https://arxiv.org/abs/1611.04399)\]

- **LMP: Multiple People Tracking with Lifted Multicut and Person Re-identification.** Siyu Tang and Mykhaylo Andriluka and Bjoern Andres and Bernt Schiele. CVPR (2017). \[[paper](http://openaccess.thecvf.com/content_cvpr_2017/papers/Tang_Multiple_People_Tracking_CVPR_2017_paper.pdf)\] :trophy:*Winner of MOT16 leaderboard*. 

- **Multi-target Tracking with Strong and Weak Detections.** Ricardo Sanchez-Matilla, Fabio Poiesi and Andrea Cavallaro. BMTT (2016). \[[paper](http://www.eecs.qmul.ac.uk/~andrea/papers/2016_ECCVW_MOT_OnlineMTTwithStrongAndWeakDetections_Sanchez-Matilla_Poiesi_Cavallaro.pdf)\]

- **POI: Multiple Object Tracking with High Performance Detection and Appearance Feature.** Fengwei Yu, Wenbo Li, Quanquan Li, Yu Liu, Xiaohua Shi, Junjie Yan. BMTT (2016). \[[paper](https://arxiv.org/abs/1610.06136)\]\[[Q&A](https://www.zhihu.com/question/40545681)\]

  ​:green_book:​ _The paper points out the importance of high performance <u>detector</u> and <u>appearance feature</u>. They lead to the state-of-the-art results, even with a simple online tracker._

  - _The detector is based on Faster R-CNN, with additional training data includes ETHZ, Caltech and <u>self-collected suveillance dataset</u>._
  - _GoogLeNet-ish network is trained with multiple re-id datasets (PRW, Market-1501, VIPeR and CUHK03) using softmax and triplet loss._
  - _Simple online tracker with Kalman filter for motion prediction and Kuhm-Munkres for data association._

- **SORT:Simple Online and Realtime Tracking.** Alex Bewley, Zongyuan Ge, Lionel Ott, Fabio Ramos, Ben Upcroft. ICIP (2016). \[[paper](https://arxiv.org/abs/1602.00763)\]\[[code](https://github.com/abewley/sort)\]

  ​:green_book: *The online tracking framework in the paper focuses on frame-to-frame predication and association. It leverages the state-of-the-art detection results, and combines with a classic, simple yet efficient online tracking framework using Kalman filter as motion model and Hungarian alforithm for data asscociation.*

  - _Note that the appearance features are ignored in tracking to avoid adding overhead into the framework._
  - _The paper identifys the <u>detection quality</u> as a key factor incluencing the tracking performance. So rather than aiming to design a tracking framework which is robust to deteciton errors, it chooses to explore the power of advanced CNN to solve the detection problem directly._ 
  - _The simplicity of the design leads to <u>super fast speed</u>: 260Hz._  

- **DeepSORT: Simple Online and Realtime Tracking with a Deep Association Metric.** Nicolai Wojke, Alex Bewley, Dietrich Paulus. arXiv. (2017). \[[paper](https://arxiv.org/abs/1703.07402)\]\[[code](https://github.com/nwojke/deep_sort)\]

- **Online Multi-Target Tracking Using Recurrent Neural Networks.** Anton Milan, S. Hamid Rezatofighi, Anthony Dick, Ian Reid and Konrad Schindler. AAAI (2017). \[[paper](http://www.milanton.de/files/aaai2017/aaai2017-anton-rnntracking.pdf)\]\[[poster](http://www.milanton.de/files/aaai2017/aaai2017-anton-rnntracking-poster.pdf)\]\[[code](https://bitbucket.org/amilan/rnntracking)\]

- **Multiple Object Tracking: A Literature Review.** Wenhan Luo, Junliang Xing, Anton Milan, Xiaoqin Zhang, Wei Liu, Xiaowei Zhao and Tae-Kyun Kim. arXiv (2017). [[paper](https://arxiv.org/abs/1409.7618)]   

- **Tracking the Trackers: An Analysis of the State of the Art in Multiple Object Tracking.** Laura Leal-Taixé, Anton Milan, Konrad Schindler, Daniel Cremers, Ian Reid, Stefan Roth. arXiv (2017). \[[paper](https://arxiv.org/abs/1704.02781)\]

- [Single-camera and Inter-camera Vehicle Tracking and 3D Speed Estimation Based on Fusion of Visual and Semantic Features](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w3/Tang_Single-Camera_and_Inter-Camera_CVPR_2018_paper.pdf). CVPRW (2018). \[[code](https://github.com/zhengthomastang/2018AICity_TeamUW)\]

- [Customized Multi-Person Tracker](http://homes.esat.kuleuven.be/~liqianma/pdf/ACCV18_Customized_Multi-Person_Tracker.pdf). ACCV (2018). 




### 2D Pose Tracking

- [ArtTrack: Articulated Multi-person Tracking in the Wild](https://arxiv.org/abs/1612.01465v3). CVPR (2017).

- [PoseTrack: Joint Multi-Person Pose Estimation and Tracking](http://pages.iai.uni-bonn.de/iqbal_umar/PoseTrack/PoseTrack_cvpr17.pdf). CVPR (2017). \[[project](http://pages.iai.uni-bonn.de/iqbal_umar/PoseTrack/)\]




### 3D MOT

[Iacopo Masi](http://www.micc.unifi.it/masi/)

### Others

1. **Video Segmentation via Object Flow.** Yi-Hsuan Tsai, Ming-Hsuan Yang, Michael J. Black.  CVPR (2016). \[[paper](http://files.is.tue.mpg.de/black/papers/TsaiCVPR2016.pdf)\]\[[project](https://sites.google.com/site/yihsuantsai/research/cvpr16-segmentation)\]\[[video](https://www.youtube.com/watch?v=rlMXSrSHCZQ)\]\[[code](https://github.com/wasidennis/ObjectFlow)\]
2. **Optical Flow in Mostly Rigid Scenes.** Jonas Wulff, Laura Sevilla-Lara, Michael J. Black. CVPR (2017). \[[paper](http://files.is.tue.mpg.de/black/papers/MRFlow.pdf)\]\[[video](https://www.youtube.com/watch?v=7hrTYWfgZF8&feature=youtu.be)\]
3. **Video Propagation Networks.** Varun Jampani, Raghudeep Gadde, Peter V. Gehler. CVPR (2017). \[[paper](https://varunjampani.github.io/papers/jampani17_VPN.pdf)\]\[[project](https://varunjampani.github.io/vpn/)\]\[[code](https://github.com/varunjampani/video_prop_networks)\]

## Highlights

- [**Anton Milan**](http://www.milanton.de/)
- [**Nicolai Wojke**](https://github.com/nwojke)
- [**Workshop on Benchmarking Multi-target Tracking (BMTT)**](https://motchallenge.net/workshops/bmtt-pets2017/)
- [**Perceiving Systems at Max Planck Institue for Intelligent Systems**](https://ps.is.tuebingen.mpg.de/publications)
- [**Institute of Computer Graphics and Vision at TU Graz**](https://www.tugraz.at/institute/icg/research/team-bischof/lrs/downloads/)
- [**Computer Vision Group at RWTH Aachen University **](https://www.vision.rwth-aachen.de/)

