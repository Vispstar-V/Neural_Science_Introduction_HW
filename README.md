# 脑机智能导论 作业2

这是浙江大学研究生课程《脑机智能导论》作业2的代码库。

## Prerequisite

* 为了能够正常运行代码，请先执行下述命令安装相关的算法库：
  ```bash
  pip install -r requirements.txt
  ```

* 实验数据来源：https://zenodo.org/records/3854034. 请在该网站内下载好对应的数据集，存放至`data`文件夹下。本次作业使用的数据集为indy_20160407_02.mat。若要复现本实验，请执行以下命令：
  ```bash
  mkdir data
  cd data
  wget https://zenodo.org/records/3854034/files/indy_20160407_02.mat
  ```

## Contents

本仓库内包含以下内容：
* `imgs`: 实验过程中的可视化结果。
* `Neural_Decoding`: 实现卡尔曼滤波和LSTM模型的代码。代码来源：https://github.com/KordingLab/Neural_Decoding
* `task1.ipynb`: 任务1的实验代码，包括raster图、PSTH图和tuning curve的绘制。
* `task2.ipynb`: 任务2的实验代码，包括线性拟合和R2值计算。
* `task3.ipynb`: 卡尔曼滤波、LSTM模型的运动估计代码。
