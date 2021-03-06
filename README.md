# Scene-LSTM


This code/implementation is available for research purposes. If you are using this code/data for your work, please cite the following paper:

> Huynh, Manh, and Gita Alaghband. "Trajectory Prediction by Coupling Scene-LSTM with Human Movement LSTM." arXiv preprint arXiv:1908.08908 (2019). **To appear in ISVC 2019.**

# This repository contains
 :heavy_check_mark: Processed data (in pixel and meter metrics) for ETH and UCY datasets. This data was also used in SGAN method.
 ```bash
 ├── data 
 │     ├── pixel/*.txt
 │     ├── meter/*.txt
  ```
 :heavy_check_mark: Scripts to convert pixel to meter and vice versa. Double check the paths to 
 homography matrices and input files.

 ```bash
 ├── data_utils
 │     ├── homography_matrix/*.txt
 │     ├── eth_utils/*.m (matlab scripts to process eth data)
 │     ├── data_utils/*.m (matlab scripts to process ucy data))
 ```
- Visualization scripts. (will be available soon) 
- My implementation for LSTM. (will be available soon).
- My implementation for Social-LSTM. (will be available soon)
- My implementation for Scene-LSTM.  (will be available soon)

# Dependencies
The code was tested on Centos 7.0 with python 3.6.8 and pytorch 1.0.0.\
The environment was setup using conda 4.5.12. Additional packages should be installed.

# Pre-trained models


