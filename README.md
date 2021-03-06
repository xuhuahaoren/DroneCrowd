# DroneCrowd
[Paper](https://arxiv.org/pdf/1912.01811.pdf)

## Introduction
![VisDrone](https://github.com/VisDrone/DroneCrowd/blob/master/sample.png)

Since existing crowd counting datasets merely focus on crowd counting in static cameras rather than density map estimation, counting and tracking in crowds on drones, we have collected a new large-scale drone-based dataset, DroneCrowd, formed by 112 video clips with 33,600 high resolution frames (i.e., 1920x1080) captured in 70 different scenarios. With intensive amount of effort, our dataset provides 20,800 people trajectories with 4.8 million head annotations and several video-level attributes in sequences.

## Dataset

### ECCV2020 Challenge

The VisDrone 2020 Crowd Counting Challenge requires participating algorithms to count persons in each frame. The challenge will provide 112 challenging sequences, including 82 video sequences for training (2,420 frames in total), and 30 sequences for testing (900 frames in total), which are available on the download page. We manually annotate persons with points in each video frame. 

DroneCrowd (1.03 GB): [BaiduYun](https://pan.baidu.com/share/init?surl=llJZJMi2L5oUQvj31iBlfg)(code: h0j8)| [GoogleDrive](https://drive.google.com/file/d/1HY3V4QObrVjzXUxL_J86oxn2bi7FMUgd/view?usp=sharing) 

### DroneCrowd (Full Version)


## Code

Space-Time Multi-Scale Attention Network [code](https://github.com/VisDrone/DroneCrowd/tree/master/STANet)


## Citation

Please cite this paper if you want to use it in your work.
```
@article{DBLP:journals/corr/abs-1912-01811,
  author    = {Longyin Wen and
               Dawei Du and
               Pengfei Zhu and
               Qinghua Hu and
               Qilong Wang and
               Liefeng Bo and
               Siwei Lyu},
  title     = {Drone-based Joint Density Map Estimation, Localization and Tracking
               with Space-Time Multi-Scale Attention Network},
  journal   = {CoRR},
  volume    = {abs/1912.01811},
  year      = {2019},
  url       = {http://arxiv.org/abs/1912.01811},
  archivePrefix = {arXiv},
  eprint    = {1912.01811},
  timestamp = {Thu, 02 Jan 2020 18:08:18 +0100},
}
```
