# Toolkit for [ApolloScape Dataset](http://apolloscape.auto/index.html)

## Introduction
This is a repo of toolkit for ApolloScape Dataset, [CVPR 2019 Workshop on Autonomous Driving Challenge](http://wad.ai/2019/challenge.html) and [ECCV 2018 challenge](http://apolloscape.auto/ECCV/index.html). It includes lanemark segmentation, online self-localization, 3D car instance understanding, Trajectory Prediction, 3D Lidar Object Detection and 3D Lidar Object Tracking and Stereo. Some example videos and images are shown below:

### Stereo estimation:
![](./examples/stereo_depth.png)

### Trajectory Prediction:
![](./examples/trajectory-prediction.gif)

### 3D Lidar Object Detection and Tracking:
![](./examples/3d-tracking.gif)

### Lanemark segmentation:
![](./examples/lanemark-segmentation.gif)

### Online self-localization:
![](./examples/self-localization.gif)

### 3D car instance understanding:
![](./examples/3d-car-instance.png)

### Data Download
```
wget https://ad-apolloscape.cdn.bcebos.com/road01_ins.tar.gz 
or
wget https://ad-apolloscape.bj.bcebos.com/road01_ins.tar.gz

wget https://ad-apolloscape.cdn.bcebos.com/trajectory/prediction_train.zip
```

Run 
```bash
pip install -r requirements.txt
source source.rc
```
to include necessary packages and current path in to PYTHONPATH to use several util functions.

Please goto each subfolder for detailed information about the data structure, evaluation criterias and some demo code to visualize the dataset.

## Citation
The apolloscape open dataset for autonomous driving and its application. [PDF](https://arxiv.org/pdf/1803.06184.pdf)

Huang, Xinyu and Wang, Peng and Cheng, Xinjing and Zhou, Dingfu and Geng, Qichuan and Yang, Ruigang

```
@article{wang2019apolloscape,
  title={The apolloscape open dataset for autonomous driving and its application},
  author={Wang, Peng and Huang, Xinyu and Cheng, Xinjing and Zhou, Dingfu and Geng, Qichuan and Yang, Ruigang},
  journal={IEEE transactions on pattern analysis and machine intelligence},
  year={2019},
  publisher={IEEE}
}
```

TrafficPredict: Trajectory Prediction for Heterogeneous Traffic-Agents. [PDF](https://arxiv.org/abs/1811.02146) [Trajectory Dataset](http://apolloscape.auto/trajectory.html) [3D Perception Dataset](http://apolloscape.auto/tracking.html)
[Website](http://gamma.cs.unc.edu/TPredict/TrafficPredict.html)

Yuexin Ma, Xinge Zhu, Sibo Zhang, Ruigang Yang, Wenping Wang, and Dinesh Manocha.

AAAI(oral), 2019

```
@inproceedings{ma2019trafficpredict,
  title={Trafficpredict: Trajectory prediction for heterogeneous traffic-agents},
  author={Ma, Yuexin and Zhu, Xinge and Zhang, Sibo and Yang, Ruigang and Wang, Wenping and Manocha, Dinesh},
  booktitle={Proceedings of the AAAI Conference on Artificial Intelligence},
  volume={33},
  pages={6120--6127},
  year={2019}
}
```



