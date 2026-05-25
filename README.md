# DarkSOT-Dataset
To advance nighttime UAV tracking research, we present DarkSOT, a dedicated benchmark dataset consisting of 268 annotated video sequences for low-light algorithm development and evaluation. Each sequence is annotated with 12 challenging attributes. The dataset includes nine common target categories: Pedestrian, Tricycle, Bicycle, Bus, Truck, Awning-tricycle, Motorcycle, Car, and Van. All data were captured using a DJI M30T UAV platform under varied real-world nighttime conditions, with flight altitudes ranging from 10 to 100 meters and camera pitch angles between 15 and 90 degrees. This ensures rich diversity in viewpoint and scene content. The dataset is divided into 192 training sequences and 76 testing sequences with no scene overlap, covering all target categories. It provides a comprehensive and reproducible benchmark for the community. 

# Download DarkSOT
DarkSOT Dataset.z01<br>
链接: https://pan.baidu.com/s/13JjFf1s_2p6RP4kfOXhuyQ?pwd=t1e9 提取码: t1e9 <br>
DarkSOT Dataset.zip<br>
链接: https://pan.baidu.com/s/1V7iEUvswyv4RfvVpM8MvNA?pwd=9pn3 提取码: 9pn3 

# Target Classes and Application Scenarios
In alignment with the object category definitions from the VisDrone dataset, nine representative 
target classes were selected: People, Tricycle, Bicycle, Bus, Truck, Awning-tricycle, Motor, Car, 
and Van(shown in Fig. 1.).

<div align="center">
  <img src="2category.png" width="700" alt="Fig. 1. Nine Target Classes">
  <p><em>Fig. 1. Nine representative objects. (a) People; (b) Awning tricycle; (c) Bicycle; (d) Bus; (e) Car; (f) Motor; (g) tricycle; (h) truck; (i) van.</em></p>
</div>

Each video sequence was annotated according to its corresponding object class. Fig. 2 summarizes 
the distribution of object categories in our dataset...

<div align="center">
  <img src="3categorypie.png" width="500" alt="Fig. 2. Category Distribution">
  <p><em>Fig. 2. Proportional distribution of nine object categories in the DarkSOT dataset.</em></p>
</div>

To ensure coverage of diverse nighttime conditions, six representative application scenarios were 
selected (Fig. 3)...

<div align="center">
  <img src="4scene.png" width="700" alt="Fig. 3. Six Application Scenarios">
  <p><em>Fig. 3. Six representative nighttime scenes. (a) Urban streets; (b) Urban arterial roads; (c) Campus grounds; (d) Grade-separated interchanges; (e) Pedestrian overpasses; (f) Rural areas.</em></p>
</div>

# Citing DarkSOT
@INPROCEEDINGS{darksot,<br>
  author={Chen, Yanyan and Fu, Ruigang and Song, Yu and Zhong, Ping},<br>
  title={TAE: Target-Aware Enhancer for Nighttime UAV Tracking},<br>
  booktitle={IEEE International Conference on Image Processing (ICIP)},<br>
  year={2026},<br>
  publisher={IEEE}<br>
}
