![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) ![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white) ![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Scipy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=for-the-badge&logo=scipy&logoColor=%white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![mlflow](https://img.shields.io/badge/mlflow-%23d9ead3.svg?style=for-the-badge&logo=numpy&logoColor=blue) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![GitLab](https://img.shields.io/badge/gitlab-%23181717.svg?style=for-the-badge&logo=gitlab&logoColor=white)

## Welcome to My World 🌌

Hi, I’m **Fatma Elik**, a multidisciplinary professional passionate about leveraging cutting-edge technologies and philosophical insights to solve real-world problems. This is my space where engineering, artificial intelligence, geophysics, disaster management, and philosophy converge to create impactful projects.

---

 ## 💫 About Me:

- **Current Role**: Working at Istanbul Metropolitan Municipality’s Earthquake Ground Investigation Directorate.
- **Education**:
  - MSc in Satellite Imagery and Remote Sensing, Istanbul Technical University.
  - BSc in Geophysical Engineering (ABET-accredited), Istanbul Technical University, Turkey.
- **Languages**: English (Fluent), Turkish (Native), German (B1).

---

## 🔬 **Expertise Areas**

### **Artificial Intelligence**

- Vision-based Navigation
- 2D Semantic Segmentation & Object Detection
- Depth Estimation & SLAM
- Computer Vision in Natural Disasters
- Transfer Learning with Pretrained Models (EfficientNet, RandLANet, etc.)
- 3D Point Cloud Semantic Segmentation
- 3D Object Detection
- Point Cloud Change Detection
- Machine Learning Algorithms
- Deep Learning

### **Geo AI & Remote Sensing**

- Disaster Risk Management using Satellite Imagery
- Change Detection for Earthquake Damage Assessment
- Bathymetry, LIDAR, Satellite Data, and UAV (Drone) Data Analysis
- Earth Observation

### **Disaster Management**

- Microzonation Studies
- Earthquake Early Warning & Response Systems
- Tsunami Action Planning
- Capacity Building for Civil Defense Teams

### **Philosophy & Ethics**

- Modern Philosophy and AI Ethics
- Philosophy of Mind and Technology
- Decision-making Frameworks Inspired by Nietzsche, Descartes, and Hegel

---
# 📊 Deep Learning Outputs

---

## 1. Post-Earthquake Damage Detection
- **Models Used**: U-Net (ResNet34, ResNet50, ResNet101 encoders), DeepLabV3, PSPNet.
- **Task**: Semantic segmentation for post-earthquake damage detection.
- **Dataset**: Satellite imagery from Maxar, focused on the Kahramanmaraş earthquake region.
- **Result**: Successfully segmented damaged buildings and roads from satellite images.

![Damage Segmentation Output](https://github.com/user-attachments/assets/616827d2-dc10-4d22-ba1b-4faa547ff051)

---

## 2. Machine Learning-Based Disaster Detection Platform
- **Models Used**: EfficientNetB2, Vision Transformer (ViT).
- **Task**: Detect and visualize disaster-prone areas using geospatial data.
- **Components**:
  - **Leafmap**: Used for dynamic visualization of affected areas on an interactive map.
  - **Gradio Interface**: Allows users to upload geospatial data and analyze it with machine learning models.
- **Workflow**:
  1. Users upload satellite or drone imagery to the platform.
  2. Machine learning models process the data to identify disaster areas.
  3. Results are displayed interactively on a map for better disaster response and planning.
- **Result**: An interactive platform for disaster detection and rapid intervention planning.

![resim2](https://github.com/user-attachments/assets/f2cb7b19-735d-4e91-bd0a-5449a70764bc)


---

## 3. Natural Disaster Classification
- **Models Used**: U-Net, EfficientNetB0, EfficientNetB4, MobileNet V2, ResNet50, DenseNet121, Xception.
- **Task**: Classify natural disasters into six categories: earthquake, fire, flood, hurricane, tsunami, and volcano.
- **Dataset**: Customized xBD dataset focusing on post-disaster satellite imagery.
- **Approach**:
  - Pretrained models with transfer learning were fine-tuned for disaster classification.
  - Images were preprocessed and resized to suit each model's requirements.
- **Result**: Achieved effective classification of disasters, highlighting the advantages and limitations of transfer learning methods.

![Disaster Classification Output](https://github.com/user-attachments/assets/487a47ff-7616-4fe9-a95c-050e2b6a1b4f)

## 4. Toronto-3D: A Large-Scale Mobile LiDAR Dataset

## **Dataset**
- **Name**: Toronto-3D
- **Purpose**: Semantic segmentation of urban roadways using 3D LiDAR data.
- **Key Features**:
  - **Scale**: Over 78 million points with high spatial resolution (~1,600 points/m²).
  - **Annotations**: 8 semantic classes:
    - Ground
    - Road
    - Road Markings
    - Natural (trees, grass)
    - Building
    - Utility Line
    - Vehicles
    - Others
  - **Data Source**: Captured via a **Velodyne HDL-32E** LiDAR sensor in downtown Toronto.

## **Task**
Semantic segmentation of urban LiDAR point clouds into predefined categories, enabling better understanding of urban environments.

## **Approach**
1. **Deep Learning Models Tested**:
   - **RandLA-Net**:
     - A lightweight neural network designed for efficient large-scale point cloud segmentation.
     - Uses local feature aggregation and attentive pooling mechanisms for accurate results.
   - **KPConv**:
     - A kernel-based convolutional network designed to process unordered 3D point clouds.
     - Adapts convolutions to the irregular structure of LiDAR data.
2. **Data Processing**:
   - The LiDAR data was preprocessed to include XYZ coordinates, intensity, and semantic labels.
   - Segment-wise accuracy was compared across urban elements like roads, buildings, and vegetation.
3. **Training Setup**:
   - Models were trained with **cross-entropy loss** for multi-class segmentation.
   - **Data augmentation** techniques, such as rotation, scaling, and flipping, were applied to improve generalization.

## **Results**
- **Performance**: Models achieved high accuracy across semantic classes, with notable success in identifying roadways and buildings.
- **Contribution**:
  - Advanced the field of LiDAR-based semantic segmentation.
  - Improved the understanding of urban environments for applications like smart city planning, autonomous driving, and infrastructure management.

## **Conclusion**
Toronto-3D, combined with state-of-the-art deep learning models like RandLA-Net and KPConv, has demonstrated the potential of LiDAR data in accurately segmenting complex urban landscapes. This dataset and approach contribute significantly to both research and practical applications in urban development and autonomous navigation.


![Toronto-3D Output](link_to_your_image_or_gif)
---


## Awards and Recognition
- **Tubitak-2210/D - Graduate Scholarship Program For Domestic Industry**

I am conducting my thesis research on the Detection of Earthquake Damages Using Satellite Images and Deep Learning Approaches in collaboration with
ESRI Turkey.

- **2nd Place - IEEE GRSS Earth at Risk Map Contest:**

Achieved global recognition as the 2nd place winner for the comprehensive earthquake activity map in Kahramanmaraş, Turkey.

https://pollunit.com/lightboxes/grssearthatrisk?embed=1&option_id=3715076

- **2nd Place - BAU HUB DEPREM & AFET YÖNETİMİ TEKNOLOJİ GİRİŞİMLERİ DESTEK PROGRAMI (BAU HUB -DAYT/DP)**

Recognized as the 2nd place winner in the BAU HUB Earthquake and Disaster Management Technology Ventures Support Program.

 https://bau-hub.com/bau-hub-deprem-afet-yonetimi-teknoloji-girisimleri-destek-programi-bau-hub-dayt-dp/#pll_switcher

## Projects
- **Earthquake Parameter Prediction With Linear Regression**
  
 https://medium.com/analytics-vidhya/earthquake-parameter-prediction-withlinear-regression-c86e5abff79f

- **Making Dynamic Corona Virus Case Map with Python**

 https://medium.com/bilişim-hareketi/python-ile-dinamik-corona-virüs-vaka-haritası-yapımı-48598485cd42?sk=e5c802c56c1b554d299c13e938b29868

- **Afetbot Hackathon Idea - A Disaster Management Chatbot Designed To Be Integrated With Istanbul Metropolitan Municipality's Mobile Application**

https://cbsakademi.ibb.istanbul/gis-hackathon/

![](https://cbsakademi.ibb.istanbul/wp-content/uploads/2023/12/WhatsApp-Image-2023-12-18-at-12.04.01.jpeg)

## 🚀 **Current Projects**

1. **Istanbul Earthquake Risk Mitigation**

   - Utilizing UAVs and satellite imagery for urban resilience.
   - Collaboration with Istanbul Metropolitan Municipality’s disaster response teams.

2. **Vision-Based AI Portfolio**

   - Creating SLAM, visual odometry, and 3D reconstruction projects on GitHub.

3. **Upwork Ventures**

   - Data annotation and computer vision services.

4. **Philosophical Writings**

   - Exploring AI’s societal impacts through philosophical frameworks.

---
## 🎨 **Creative Projects**

- **3D Building Reconstructions**: Designing 3D terrain or building meshes with Blender.
- **10-Day Philosophy-AI Challenge**: Explored intersections of philosophy and technology.

---

## 🌐 **Let’s Connect**

- **Email**: [fatma.elik@ibb.gov.tr](mailto:fatma.elik@ibb.gov.tr)
- **Medium**: [Medium](https://medium.com/@fatmaelikf/)
- **Linkedin**: [LinkedIn](https://www.linkedin.com/in/fatma-elik-399141b3/)



# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=FatmaElik&theme=dark&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=FatmaElik&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=FatmaElik&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=FatmaElik&theme=radical&no-frame=false&no-bg=true&margin-w=4)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

---
[![](https://visitcount.itsvg.in/api?id=FatmaElik&icon=7&color=0)](https://visitcount.itsvg.in)


