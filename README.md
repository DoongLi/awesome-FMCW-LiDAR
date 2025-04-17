# Awesome FMCW-LiDAR

A curated list of FMCW-LiDAR papers and resources.

## Paper

#### Clustering

| Index | Paper Title                                                  | Date | Reference | Datasets Link                    | Device      |
| ----- | ------------------------------------------------------------ | ---- | --------- | -------------------------------- | ----------- |
| 1     | Doppler velocity-based algorithm for Clustering and Velocity Estimation of moving objects | 2022 | CVPR      | https://arxiv.org/abs/2112.12984 | custum made |

#### Object Detection

| Index | Paper Title                                                  | Date | Reference | Datasets Link                         | Device         |
| ----- | ------------------------------------------------------------ | ---- | --------- | ------------------------------------- | -------------- |
| 1     | HeLiMOS: A Dataset for Moving Object Segmentation in 3D Point Clouds From Heterogeneous LiDAR Sensors | 2024 | CVPR      | https://sites.google.com/view/helimos | Aeva Aeries II |

#### Datasets

| Index | Paper Title                                                  | Date | Reference | Datasets Link                                 | Device         |
| ----- | ------------------------------------------------------------ | ---- | --------- | --------------------------------------------- | -------------- |
| 1     | HeLiPR: Heterogeneous LiDAR Dataset for inter-LiDAR Place Recognition under Spatial and Temporal Variations | 2024 | IJRR      | https://sites.google.com/view/heliprdataset/  | Aeva Aeries II |
| 2     | HeRCULES: Heterogeneous Radar Dataset in Complex Urban Environment for Multi-session Radar SLAM | 2025 | ICRA      | https://sites.google.com/view/herculesdataset | Aeva Aeries II |


#### Point Cloud Registration

| Index | Paper Title                                                  | Date | Reference                                                    | Code                                   | Device                                       |
| ----- | ------------------------------------------------------------ | ---- | ------------------------------------------------------------ | -------------------------------------- | -------------------------------------------- |
| 1     | DICP: Doppler Iterative Closest Point Algorithm              | 2022 | RSS                                                          | https://github.com/aevainc/Doppler-ICP | Aeva Aeries I FMCW Lidar and CARLA simulator |
| 2     | Extended Object Tracking with Doppler velocity-based Point Registration | 2023 | IEEE Symposium Sensor Data Fusion and International Conference on Multisensor Fusion and Integration | NULL                                   | AEVA’s Aeries II  FMCW LiDAR                 |
|       |                                                              |      |                                                              |                                        |                                              |

#### Odometry

| Index | Paper Title                                                  | Date | Reference | Code                                      | Device                    | Provide Open Datasets？                                      |
| ----- | ------------------------------------------------------------ | ---- | --------- | ----------------------------------------- | ------------------------- | ------------------------------------------------------------ |
| 1     | Picking Up Speed: Continuous-Time Lidar-Only Odometry using Doppler Velocity Measurements | 2023 | RAL       | https://github.com/utiasASRL/steam_icp    | Aeva Aeries I FMCW LiDAR  | [link](https://drive.google.com/file/d/1JpQNnXejow3qy1qp5tVzak9qnuFmjYHW/view) |
| 2     | Need for Speed: Fast Correspondence-Free Lidar Odometry Using Doppler Velocity | 2023 | IROS      | NULL                                      | Aeva Aeries I FMCW LiDAR  | NULL                                                         |
| 3     | FMCW-LIO: A Robust Doppler-Aided LiDAR-Inertial Odometry     | 2024 | RAL       | https://github.com/IMRL/FMCW-LIO          | Aeva Aeries II FMCW LiDAR | ToDo                                                         |
| 4     | Free-Init: Scan-Free, Motion-Free, and Correspondence-Free Initialization for Doppler LiDAR-Inertial Systems | 2024 | RAL       | https://github.com/IMRL/FreeIni           | Aeva Aeries II FMCW LiDAR | ToDo                                                         |
| 5     | Efficient Doppler LiDAR Odometry using Scan Slicing and Vehicle Kinematics | 2024 | TIM       | https://github.com/NEU-REAL/4DLO          | Dataset                   | NULL                                                         |
| 6     | [Doppler-SLAM: Doppler-Aided Radar-Inertial and LiDAR-Inertial Simultaneous Localization and Mapping](https://arxiv.org/pdf/2504.11634) | 2025 | arXiv     | https://github.com/Wayne-DWA/Doppler-SLAM | NULL                      | NULL                                                         |

#### Detection/Segmentation/Tracking

| Index | Paper Title                                                  | Date | Reference | Code | Device                                | Open Datasets |
| ----- | ------------------------------------------------------------ | ---- | --------- | ---- | ------------------------------------- | ------------- |
| 1     | Learning Moving-Object Tracking with FMCW LiDAR              | 2022 | IROS      | NULL | Guangshao 2.0 FMCW LiDAR              | NULL          |
| 2     | POD: Predictive Object Detection with Single-Frame FMCW LiDAR Point Cloud | 2025 | arXiv     | NULL | Private dataset, 128-line FMCW LiDAR. | NULL          |


#### Survey

| Index | Paper Title                                                  | Date | Reference                    | Website                                  |
| ----- | ------------------------------------------------------------ | ---- | ---------------------------- | ---------------------------------------- |
| 1     | LiDAR Odometry Survey: Recent Advancements and Remaining Challenges | 2024 | Intelligent Service Robotics | [link](https://arxiv.org/pdf/2312.17487) |
|       |                                                              |      |                              |                                          |
|       |                                                              |      |                              |                                          |

## Simulator

- CARLA simulator: https://github.com/aevainc/carla

## Application

| Index | Paper/Project Title                                          | Reference                                           | Authors | Date |
| ----- | ------------------------------------------------------------ | --------------------------------------------------- | ------- | ---- |
| 1     | Applications of Mobile LiDAR for Ultra-High Resolution and GPS-Denied Terrain Mapping in Planetary Analog Environments | 54th Lunar and Planetary Science Conference (LPSC). | NASA    | 2023 |
|       |                                                              |                                                     |         |      |
|       |                                                              |                                                     |         |      |

## FMCW-LiDAR Device

- Leishen LSLIDAR FMCW LiDAR：https://www.lslidar.com/ko/product/fmcw-lidar/
- LAMBDA INNOVISION FMCW LiDAR：https://lambda-innovision.com/%ec%a0%9c%ed%92%88%ec%86%8c%ea%b0%9c/
- Guangshao 2.0 FMCW LiDAR：http://www.laserradar.cn/
- Aeva Aeries I FMCW LiDAR：https://www.aeva.com/
- Aeva Aeries II FMCW LiDAR：https://www.aeva.com/aeries-ii/
- Aeva Atlas FMCW LiDAR:  https://www.aeva.com/atlas/
- Aeva Atlas Ultra FMCW LiDAR: https://www.aeva.com/atlas-ultra/ (will be available at 2026)
- SuZhou intellidar Scenery, Insight, Vast series FMCW LiDAR: [https://github.com/DoongLi/awesome-FMCW-LiDAR/blob/main/Doc/SuZhou-intellidar-doc.pdf](https://github.com/DoongLi/awesome-FMCW-LiDAR/blob/main/Doc/SuZhou-intellidar-doc.pdf)

## FMCW-LiDAR Parameter Setting(Lidar2IMU)

- Aeva Aeries II FMCW LiDAR：https://www.aeva.com/aeries-ii/

| Parameter       | Value  | Unit   | Description                             |
| --------------- | ------ | ------ | --------------------------------------- |
| `imu_x`         | 0.020  | meter  | X-axis offset of the IMU                |
| `imu_y`         | 0.023  | meter  | Y-axis offset of the IMU                |
| `imu_z`         | -0.037 | meter  | Z-axis offset of the IMU                |
| `imu_rot_x_deg` | 0.0    | degree | Rotation around the x-axis (in degrees) |
| `imu_rot_y_deg` | 0.0    | degree | Rotation around the y-axis (in degrees) |
| `imu_rot_z_deg` | 0.0    | degree | Rotation around the z-axis (in degrees) |


## TODO LIST

- Different models FMCW-LIDAR parameter comparison

