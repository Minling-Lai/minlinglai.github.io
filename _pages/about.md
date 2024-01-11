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


My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2022.02*: &nbsp;🎉🎉  . 
- *2022.02*: &nbsp;🎉🎉. 

# 📝 Publications 


  
<img align="left" src='images/1-s2.jpg' width="260" />

[Spatial feature point measurement on large-curved surfaces: A portable mobile measurement method based on monocular multi-angle point](https://www.sciencedirect.com/science/article/pii/S1110016822005841)

**Minling Lai**, Huiling Tang, Qilin Bi,ZhenYu Tang

**Abstract:** This research introduces a precise and efficient detection method for feature-points distance measurement on the curved surface of large components based on tightly-coupled visual- Inertial measurement unit (referred to as IMU) such as forging, bridge, underwater pier, nuclear power and others manufacturing and quality monitoring sceneries. Basic algorithms and mathematical principles of the tightly-coupled monocular camera-IMU combined positioning module are utilized and real-time estimation model of the relative spatial attitude of the camera in the time domain is proposed. We study the calibration algorithm and mathematical principles of monocular camera external parameters during the measurement process and establish the estimation model of the relative spatial pose of the imaging surface and the object surface. The distance calculation model of the point to be measured on the space surface is established by fusing the camera's internal and external imaging parameters, imaging features and the theory of no distortion of the camera's optical axis. The distance measurement experiment device and the measurement system frame are constructed. The measurement results are validated by comparison against auxiliary target, image stitching and other measurement methods data. The target error within 20 m measured by the proposed method is controlled within 10 mm.

  
<img align="left" src='images/1-s3.jpg' width="270" />

[Method for detecting surface defects of underwater buildings: Binocular vision based on sinusoidal grating fringe assistance](https://www.sciencedirect.com/science/article/pii/S1110016823005938)

Qilin Bi; **Minling Lai**; Jindong Yu; Zhengyu Tang; Xianbin Teng; Youjie Lu; Jiashu Zou

**Abstract:** In underwater building-surface defect detection, high pressure, cold and other underwater factors will cause harm to frogmen, sonar and other detection techniques contain limited information and accuracy is difficult to meet the demand. In view of the above disadvantages, a sine stripe-assisted visual detection method of underwater building surface-defects is proposed. By generating a fixed sine stripe by program and projected it on the surface of the underwater building, and then control a binocular CCD to acquire six frames of sinusoidal stripes with different phases in one sampling period. Experiment results show that the error of our method does not exceed 0.5 mm and the reconstruction efficiency is not less than 5 m2/s in the 3D dimensional measurement of the defects on the surface of the submerged building body.

<img align="left" src='images/1-s4.jpg' width="270"/>

[Ship Collision Avoidance Navigation Signal Recognition via Vision Sensing and Machine Forecasting](https://ieeexplore.ieee.org/document/10164232)

 Qilin Bi; Miaohui Wang; Yijing Huang; **Minling Lai**; Zhijun Liu; Xiuying Bi

**Abstract:** Ship collision avoidance (SCA) is an important technique in the field of decision-making in marine navigation. Although some promising solutions have been developed recently, there is still the lack of low-cost and reliable sensing equipment. Inspired by the low-cost of camera sensors and the success of machine learning, this paper designs a vision-based method to recognize ships and their micro-features for SCA navigation planning. Firstly, we develop a vision-based bearing, distance and velocity model based on a wide-field optical imaging system. Secondly, optical information is used to construct the micro-characteristic imaging model of ship navigation signals. Thirdly, we have solved the problem between a large field-of-view (FOV) and high-resolution imaging in vision-based marine navigation. Finally, an improved Adaboost algorithm is designed for the intelligent recognition of an open-sea target (ship types and light patterns). The proposed method has been verified by extensive experiments in a practical environment, and the results show that it can effectively and efficiently identify the navigation signal of a target ship.

  
<img align="left" src='images/1-s8.jpg' width="250"/>

[Precise Inspection of Geometric Parameters for Polyvinyl Chloride Pipe Section Based on Computer Vision](https://iieta.org/journals/ts/paper/10.18280/ts.380608)

Qilin Bi; **Minling Lai**; Huiling Tang; Yanyao Guo; Jinyuan Li; Xinhong Zeng; Zhijun Liu

**Abstract:** The precise inspection of geometric parameters is crucial for quality control in the context of Industry 4.0. The current technique of precise inspection depends on the operation of professional personnel, and the measuring accuracy is restricted by the proficiency of operators. To solve the defects, this paper proposes a precise inspection framework for the geometric parameters of polyvinyl chloride (PVC) pipe section (G-PVC), using low-cost visual sensors and high-precision computer vision algorithms. Firstly, a robust imaging system was built to acquire images of a PVC pipe section under irregular illumination changes. Next, an engineering semantic model was established to calculate G-PVC like inner diameter, outer diameter, wall thickness, and roundness. After that, a region-of-interest (ROI) extraction algorithm was combined with an improved edge operator to obtain the coordinates of measured points on PVC end-face image in a stable and precise manner. Finally, our framework was proved highly precise and robust through experiments.


  
<img align="left" src='images/1-s6.jpg' width="220"/>

[Towards Automatic Surface Inspection for S-PVC Using a Composite Vision-based Method](https://opg.optica.org/ao/abstract.cfm?URI=ao-59-4-1008)

Qilin Bi; Miaohui Wang; **Minling Lai**; Jiaxin Lin; Jialin Zhang; Xiaoguang Liu


**Abstract:** Appearance defect inspection is crucial for quality control in the context of Industry 4.0. This research introduces a joint surface defect inspection and classification framework for polyvinyl chloride (PVC) pipe based on the low-cost visual sensors and high-efficiency computer vision algorithms. First, we build a robust imaging system to acquire the surface of PVC (S-PVC) by considering its characteristics and the illumination condition into the modeling process. Second, we adopt the region of interest method to eliminate the background interference captured in the S-PVC imaging and design an efficient S-PVC defect inspection and classification method. Third, we build an automatic machine prototype to evaluate the efficiency of the proposed method. Experimental results demonstrate that our framework has the advantages of low latency, high precision, and robustness.


  
<img align="left" src='images/1-s7.jpg' width="280"/>

[A Seamlessly Switch Method of Double Frequency Ship Electricity Grid from Shore Electricity Grid](https://www.semanticscholar.org/paper/A-Seamlessly-Switch-Method-of-Double-Frequency-Ship-Xiao-Lai/3d03cab764c94727e9f432ea1c697bc7da1c11c8?utm_source=direct_link)

Lemin Xiao; **Minling Lai**; Qilin Bi

**Abstract:** In this work, the seamlessly switch systems between shore electricity and ship electricity of dual frequency mode (50Hz-60Hz and 50Hz-50Hz) is proposed. It is mainly used in the power supply of ships (Abbreviated as SEG) which stay in the port, and the problem that the grid needs to be disconnected when the ship is provided with electricity from the shore electricity is resolved. Firstly, the phase locked loop (Abbreviated as PLL) control model is established in seamlessly switch systems between shore electricity and ship electricity of dual frequency mode. Secondly, the V/f control model of seamlessly switch systems is established, and the frequency (f) follow is implemented in seamlessly switch systems combined with the phase locked loop control model. At last, the P/Q control model of seamlessly switch systems is proposed. The load power is transferred from the ship's generator to the shore electricity grid combined with phase locked loop control model. The power supply between shore electricity which is 50Hz and ship electricity which is 50Hz or 60 Hz is achieved according to the grid technology research.
  
</div></div>


[**Project**] <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 


- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**



# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 



# 📖 Educations
- *2021.07 - 2023.12 (now)*, M.S.degree,Electronic Science and Technology,Guangdong University of Technology. 
- *2016.09 - 2020.06*, B.s.degree,Ship and Ocean Engineering Program,Guangzhou Maritime University. 



# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)


# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
