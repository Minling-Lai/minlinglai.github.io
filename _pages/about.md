---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Currently, I am a research student at Guangdong University of Technology. My current research interest is computer vision， specifically studying image noising for rain, fog, and snow.  I have published over 6 papers in international journals Zone 2-3.



# 📝 Publications/已发表论文


  
<img align="left" src='images/1-s2.jpg' width="260" />

[Spatial feature point measurement on large-curved surfaces: A portable mobile measurement method based on monocular multi-angle point](https://www.sciencedirect.com/science/article/pii/S1110016822005841)

**Minling Lai**, Huiling Tang, Qilin Bi,ZhenYu Tang/**赖敏玲（一作）**，唐惠玲，毕齐林，唐振宇

**Abstract:** This research introduces a precise and efficient detection method for feature-points distance measurement on the curved surface of large components based on tightly-coupled visual- Inertial measurement unit (referred to as IMU) such as forging, bridge, underwater pier, nuclear power and others manufacturing and quality monitoring sceneries. Basic algorithms and mathematical principles of the tightly-coupled monocular camera-IMU combined positioning module are utilized and real-time estimation model of the relative spatial attitude of the camera in the time domain is proposed. We study the calibration algorithm and mathematical principles of monocular camera external parameters during the measurement process and establish the estimation model of the relative spatial pose of the imaging surface and the object surface. The distance calculation model of the point to be measured on the space surface is established by fusing the camera's internal and external imaging parameters, imaging features and the theory of no distortion of the camera's optical axis. The distance measurement experiment device and the measurement system frame are constructed. The measurement results are validated by comparison against auxiliary target, image stitching and other measurement methods data. The target error within 20 m measured by the proposed method is controlled within 10 mm.

  
<img align="left" src='images/1-s3.jpg' width="270" />

[Method for detecting surface defects of underwater buildings: Binocular vision based on sinusoidal grating fringe assistance](https://www.sciencedirect.com/science/article/pii/S1110016823005938)

Qilin Bi; **Minling Lai**; Jindong Yu; Zhengyu Tang; Xianbin Teng; Youjie Lu; Jiashu Zou/毕齐林，**赖敏玲（通讯）**，余金栋，唐振宇，藤宪斌，吕有界，邹佳书

**Abstract:** In underwater building-surface defect detection, high pressure, cold and other underwater factors will cause harm to frogmen, sonar and other detection techniques contain limited information and accuracy is difficult to meet the demand. In view of the above disadvantages, a sine stripe-assisted visual detection method of underwater building surface-defects is proposed. By generating a fixed sine stripe by program and projected it on the surface of the underwater building, and then control a binocular CCD to acquire six frames of sinusoidal stripes with different phases in one sampling period. Experiment results show that the error of our method does not exceed 0.5 mm and the reconstruction efficiency is not less than 5 m2/s in the 3D dimensional measurement of the defects on the surface of the submerged building body.

<img align="left" src='images/1-s4.jpg' width="270"/>

[Ship Collision Avoidance Navigation Signal Recognition via Vision Sensing and Machine Forecasting](https://ieeexplore.ieee.org/document/10164232)

 Qilin Bi; Miaohui Wang; Yijing Huang; **Minling Lai**; Zhijun Liu; Xiuying Bi/毕齐林，王妙辉，黄依静，**赖敏玲**，刘志军，毕修颖

**Abstract:** Ship collision avoidance (SCA) is an important technique in the field of decision-making in marine navigation. Although some promising solutions have been developed recently, there is still the lack of low-cost and reliable sensing equipment. Inspired by the low-cost of camera sensors and the success of machine learning, this paper designs a vision-based method to recognize ships and their micro-features for SCA navigation planning. Firstly, we develop a vision-based bearing, distance and velocity model based on a wide-field optical imaging system. Secondly, optical information is used to construct the micro-characteristic imaging model of ship navigation signals. Thirdly, we have solved the problem between a large field-of-view (FOV) and high-resolution imaging in vision-based marine navigation. Finally, an improved Adaboost algorithm is designed for the intelligent recognition of an open-sea target (ship types and light patterns). The proposed method has been verified by extensive experiments in a practical environment, and the results show that it can effectively and efficiently identify the navigation signal of a target ship.

  
<img align="left" src='images/1-s8.jpg' width="250"/>

[Precise Inspection of Geometric Parameters for Polyvinyl Chloride Pipe Section Based on Computer Vision](https://iieta.org/journals/ts/paper/10.18280/ts.380608)

Qilin Bi; **Minling Lai**; Huiling Tang; Yanyao Guo; Jinyuan Li; Xinhong Zeng; Zhijun Liu/毕齐林，**赖敏玲（通讯）**，唐惠玲，郭雁瑶，李金源，曾新红，刘志军

**Abstract:** The precise inspection of geometric parameters is crucial for quality control in the context of Industry 4.0. The current technique of precise inspection depends on the operation of professional personnel, and the measuring accuracy is restricted by the proficiency of operators. To solve the defects, this paper proposes a precise inspection framework for the geometric parameters of polyvinyl chloride (PVC) pipe section (G-PVC), using low-cost visual sensors and high-precision computer vision algorithms. Firstly, a robust imaging system was built to acquire images of a PVC pipe section under irregular illumination changes. Next, an engineering semantic model was established to calculate G-PVC like inner diameter, outer diameter, wall thickness, and roundness. After that, a region-of-interest (ROI) extraction algorithm was combined with an improved edge operator to obtain the coordinates of measured points on PVC end-face image in a stable and precise manner. Finally, our framework was proved highly precise and robust through experiments.


  
<img align="left" src='images/1-s6.jpg' width="220"/>

[Towards Automatic Surface Inspection for S-PVC Using a Composite Vision-based Method](https://opg.optica.org/ao/abstract.cfm?URI=ao-59-4-1008)

Qilin Bi; Miaohui Wang; **Minling Lai**; Jiaxin Lin; Jialin Zhang; Xiaoguang Liu/毕齐林，王妙辉，**赖敏玲**，林佳新，张嘉陵，刘晓光


**Abstract:** Appearance defect inspection is crucial for quality control in the context of Industry 4.0. This research introduces a joint surface defect inspection and classification framework for polyvinyl chloride (PVC) pipe based on the low-cost visual sensors and high-efficiency computer vision algorithms. First, we build a robust imaging system to acquire the surface of PVC (S-PVC) by considering its characteristics and the illumination condition into the modeling process. Second, we adopt the region of interest method to eliminate the background interference captured in the S-PVC imaging and design an efficient S-PVC defect inspection and classification method. Third, we build an automatic machine prototype to evaluate the efficiency of the proposed method. Experimental results demonstrate that our framework has the advantages of low latency, high precision, and robustness.


  
<img align="left" src='images/1-s7.jpg' width="280"/>

[A Seamlessly Switch Method of Double Frequency Ship Electricity Grid from Shore Electricity Grid](https://www.semanticscholar.org/paper/A-Seamlessly-Switch-Method-of-Double-Frequency-Ship-Xiao-Lai/3d03cab764c94727e9f432ea1c697bc7da1c11c8?utm_source=direct_link)

Lemin Xiao; **Minling Lai**; Qilin Bi/肖乐明，**赖敏玲**，毕齐林

**Abstract:** In this work, the seamlessly switch systems between shore electricity and ship electricity of dual frequency mode (50Hz-60Hz and 50Hz-50Hz) is proposed. It is mainly used in the power supply of ships (Abbreviated as SEG) which stay in the port, and the problem that the grid needs to be disconnected when the ship is provided with electricity from the shore electricity is resolved. Firstly, the phase locked loop (Abbreviated as PLL) control model is established in seamlessly switch systems between shore electricity and ship electricity of dual frequency mode. Secondly, the V/f control model of seamlessly switch systems is established, and the frequency (f) follow is implemented in seamlessly switch systems combined with the phase locked loop control model. At last, the P/Q control model of seamlessly switch systems is proposed. The load power is transferred from the ship's generator to the shore electricity grid combined with phase locked loop control model. The power supply between shore electricity which is 50Hz and ship electricity which is 50Hz or 60 Hz is achieved according to the grid technology research.
  
# 📝 Project/项目

- Dec,2022-Jun,2023                                              [**Development of visual recognition rake operation and maintenance system/基于双目视觉的耙齿磨损识别**](https://github.com)      

**Description**: In order to replace the low time resistance of manual operation and overcome the disadvantages of over-reliance on operation experience, the industrial camera and the corresponding algorithm are used to replace the manual cumbersome operation. The system mainly uses the principle of binocular imaging to realize the three-dimensional point cloud reconstruction of the working rake teeth. The main functions of the designed system include camera correction, image correction and matching, 3D point cloud reproduction of rake teeth, and visualization of wear fluctuations.




- Jan,2021-Jul,2021                                              [**Egg yolk quality identification/鸭蛋黄芯的质量检测**](https://github.com)     

**Description**: Existing egg yolk core selection mainly relies on experienced manual selection, in order to overcome the disadvantages of manual selection, the use of vision technology to achieve the detection of egg core. The project uses the color component information of the egg core as a network input to achieve accurate detection of various types of defects in the egg core, and the system can basically do the detection of defects covering the types of defects in the egg core.
  


-  Jan,2020-Oct,2020                                             [**Identification and positioning of translucent infusion tubes/半透明滴漏管的重定位识别**](https://github.com)     

**Description**: Relying on vision technology to realize the packaging process of industrial bubble valves, overlapping bubble valves interfere with the positioning, thus affecting the selection of the robotic arm, this project combines information entropy to realize the positioning of overlapping bubble valves.


-  Jan,2018-Mar,2019                                             [**PVC Pipe End Face Size - Visual Measurement System for Apparent Defects/PVC管材的端面尺寸-表面缺陷检测复合系统**](https://github.com)     

**Description**:Pipe surface, end-face size is the detection of PVC pipe is qualified indicators, alternative to manual inspection of vision technology is to achieve intelligent detection of one of the means of pipe, the system covers the detection of pipe surface defects, bubbles, scratches, and end-face size of the intelligent detection.
                     


# 📖 Educations/教育经历
- *2021.07 - 2023.12 (now)*, M.S.degree,Electronic Science and Technology,Guangdong University of Technology. 
- *2016.09 - 2020.06*, B.s.degree,Ship and Ocean Engineering Program,Guangzhou Maritime University.


-*2021.09~2024.07*              广东工业大学                    电子科学与技术              工学硕士（学术型）

  **成绩**：3.5/4.0
  
  **所获荣誉**：2023年学业奖学金一等奖；2022年学业奖学金一等奖；2021年学业奖学金二等奖。

  
-*2016.09~2020.07*              广州航海学院                    船舶与海洋工程                     工学学士       

  **成绩**：3.5/4.0
  
  **所获荣誉**：优秀毕业生 、校优秀班干部 、校三等奖学金(2次)、国家励志奖学金、科技创新优秀个人奖(2次)。



# 💻 Full-Job Experience（全职工作经历）
- *2021.01 - 2021.07*, R & D Engineer,Responsible for visual inspection, including identification of aquatic fish, translucent dropper identification, and egg yolk quality identification.
                       研发工程师，负责视觉检测，包括涉及水鱼的识别、半透明滴管识别、蛋黄品质识别。
