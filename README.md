
# Computer Vision & Perception Engineering Portfolio

**Oluoma Phylis Oji** | Computer Vision Engineer  
📧 oluomaoji@gmail.com | 💼 [LinkedIn](https://www.linkedin.com/in/oluomaoji/) | 🔗 [Full CV](link-to-your-cv) | youtube_link

---

## About Me

I'm a Computer Vision Engineer with 5+ years of experience building **production-grade perception systems** that bridge the gap between pixels and intelligent action. My work spans the full spectrum: from classical computer vision techniques to modern deep learning architectures, and from standalone vision systems to integrated robotics perception pipelines.

**What drives me:** I don't just train models—I build complete systems that work reliably in the real world. Whether it's detecting crop diseases in variable lighting, enabling robots to grasp objects with precision, or designing perception stacks for autonomous navigation, I focus on **end-to-end solutions that solve real problems**.

### My Technical Philosophy

- **Pragmatic Problem Solving:** I choose the right tool for the job—classical CV when appropriate, deep learning when it adds value, and hybrid approaches when they deliver the best results
- **Production-First Mindset:** Models are only valuable when they're deployed, maintained, and delivering impact
- **Robotics Integration:** Unique ability to connect vision systems with motion planning, navigation, and manipulation in ROS2 ecosystems

---

## Core Capabilities

**Computer Vision**  
Object Detection • Image Classification • Semantic & Instance Segmentation • Feature Extraction • Image Processing • Camera Calibration

**Deep Learning & Frameworks**  
PyTorch • TensorFlow • OpenCV • CNNs • Transfer Learning • Model Optimization

**Robotics & Perception**  
ROS2 • Nav2 • MoveIt2 • Visual SLAM • TF Transforms • Vision-Guided Manipulation • Sensor Fusion

**MLOps & Deployment**  
MLflow • Docker • Model Serving • Edge Deployment • CI/CD for ML

---

## Featured Projects

### 🌱 [End-to-End Crop Disease Detection System](./potato-disease-detection/)
**Production-Ready Vision Pipeline | PyTorch • OpenCV • Deep Learning**

Built a complete computer vision system for agricultural disease detection achieving **>90% classification accuracy** on real-world potato leaf images.

**Key Achievements:**
- Designed full ML lifecycle: data ingestion → preprocessing & augmentation → CNN training → evaluation → production inference
- Solved severe class imbalance through intelligent augmentation strategies, improving minority-class recall by 35%
- Delivered deployment-ready pipeline optimized for variable field conditions (lighting, angles, occlusion)
- Implemented comprehensive evaluation framework with precision-recall analysis and confusion matrices

**Why This Matters:** Demonstrates ability to build complete, production-grade pipelines that handle real-world data challenges—not just Kaggle-perfect datasets.

[→ View Technical Details](./potato-disease-detection/)

---

### 🤖 [Vision-Guided Pick & Place System](./ros2-pick-and-place-vision/)
**Robotic Manipulation | ROS2 • MoveIt2 • OpenCV • Gazebo**

Developed end-to-end perception and manipulation system enabling Franka Emika Panda robot to autonomously detect, grasp, and sort objects.

**Key Achievements:**
- Implemented robust classical CV pipeline (color segmentation, contour detection) for object localization
- Engineered coordinate transformation system using TF frames to convert 2D detections → accurate 3D grasp poses
- Integrated perception with MoveIt2 collision-aware motion planning, achieving 95%+ pick success rate
- Built complete perception-to-action loop with sub-200ms total latency

**Why This Matters:** Shows ability to bridge vision and robotics—taking detections from images all the way to physical robot actions.

[→ View Technical Details](./ros2-pick-and-place-vision/)

---

### 📦 [Autonomous Warehouse Robot](./autonomous-warehouse-robot/) *(In Progress)*
**Mobile Manipulation | ROS2 • Nav2 • SLAM • MoveIt2 • Computer Vision**

Building autonomous mobile manipulator capable of warehouse navigation and shelf-based pick-and-place operations—a complete robotics perception challenge.

**Technical Scope:**
- Designing multi-modal perception pipeline: object detection + 6-DOF pose estimation for manipulation
- Integrating Nav2 autonomous navigation with SLAM-based localization in dynamic environments
- Architecting complete perception-to-action workflow: vision → localization → path planning → manipulation → control
- Building modular system with clean separation of concerns for testing and deployment

**Why This Matters:** Demonstrates system-level thinking and ability to architect complex perception systems that integrate multiple robotics subsystems.

[→ View Technical Details](./autonomous-warehouse-robot/)

---

### 🚗 [Autonomous Vehicle Perception Stack](./autonomous-vehicle-perception/) *(System Design)*
**Multi-Task Perception | Computer Vision • Deep Learning • Architecture**

Designed modular perception architecture for autonomous driving scenarios with emphasis on robustness and real-world reliability.

**Design Highlights:**
- Multi-task perception: object detection, lane detection, semantic segmentation, multi-object tracking
- Robustness considerations: lighting variations, scale changes, occlusion handling, edge case management
- Efficient sensor fusion strategy and real-time processing constraints
- Scalable architecture suitable for deployment on autonomous vehicle compute platforms

**Why This Matters:** Shows ability to think at the systems level—designing architectures that balance performance, robustness, and computational constraints.

[→ View Design Details](./autonomous-vehicle-perception/)

---

## What Sets My Work Apart

✅ **End-to-End Ownership:** I don't just fine-tune models—I build complete systems from data collection through deployment  
✅ **Production Experience:** 5+ years shipping CV systems that operate reliably in real-world conditions  
✅ **Hybrid Approaches:** Pragmatic blending of classical CV and deep learning for optimal results  
✅ **Robotics Integration:** Unique ability to connect vision with motion planning, navigation, and manipulation  
✅ **Problem-Solver First:** Focus on delivering working solutions, not just impressive benchmarks

---

## Technical Stack

**Languages:** Python (Expert) • C++ (Intermediate)  
**CV & Deep Learning:** OpenCV • PyTorch • TensorFlow • scikit-learn  
**Robotics:** ROS2 • Nav2 • MoveIt2 • Gazebo  
**MLOps:** MLflow • DVC • Docker • Git/GitHub  
**Deployment:** Model Optimization • Edge Deployment • Real-Time Systems

---

## Professional Background

**Computer Vision Engineer** | Byteworks Technology (2019–2024)  
Built and deployed production computer vision systems spanning object detection, classification, and image processing applications.

**Machine Learning Engineer** | Vibra Technology (2024–Present)  
Developing and deploying ML models with emphasis on computer vision applications and production pipelines.

**Robotics Perception Training** | The Construct (2025)  
Intensive hands-on training in robotics perception, autonomous navigation, and vision-guided manipulation.

[→ View Full CV](link-to-your-cv)

---

## Current Focus

I'm actively seeking opportunities in **Computer Vision Engineering** and **Perception Engineering** roles where I can:
- Design and deploy production-grade vision systems
- Bridge computer vision with robotics and autonomous systems
- Build perception pipelines that enable intelligent action
- Work on challenging real-world problems with measurable impact

**Interested in working together?** Let's connect:  
📧 oluomaoji@gmail.com | 💼 [LinkedIn](https://www.linkedin.com/in/oluomaoji/)

---

## Repository Structure

```
computer-vision-perception-portfolio/
│
├── README.md                           ← You are here
│
├── potato-disease-detection/           ← End-to-end ML pipeline
│   ├── README.md
│   ├── src/
│   ├── notebooks/
│   └── results/
│
├── ros2-pick-and-place-vision/         ← Vision-guided manipulation
│   ├── README.md
│   ├── src/
│   ├── launch/
│   └── demo/
│
├── autonomous-warehouse-robot/         ← Mobile manipulation system
│   ├── README.md
│   ├── src/
│   ├── config/
│   └── architecture/
│
└── autonomous-vehicle-perception/      ← AV perception design
    ├── README.md
    ├── design-docs/
    └── architecture/
```

---

*This portfolio showcases production-oriented computer vision and perception engineering work. Each project demonstrates end-to-end thinking, technical depth, and real-world problem-solving capabilities.*
