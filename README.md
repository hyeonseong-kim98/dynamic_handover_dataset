# 🤝 Dynamic Handover Dataset

This repository provides the **Dynamic Robot-to-Human Handover Dataset**, collected for research in dynamic object handover between robots and humans. The dataset is introduced in the following paper:

📄 **[Learning-based Dynamic Robot-to-Human Handover (ArXiv 2024)](https://arxiv.org/abs/2502.12602)**

---

## 📦 Dataset Overview

- **Total Motions**: 1,000
  - **In-distribution**: 900 motions
  - **Out-of-distribution**: 100 motions
- **Capture Rate**: 30 Hz
- **Data Folder**: `data/whole_motions/`
- **Sensors Used**:
  - 🎥 **ZED2i Stereo Vision** with built-in body tracking
  - 🎯 **OptiTrack Motion Capture System** (for precise object pose tracking)

---

## 🎮 Visualization

We provide motion visualization using the **MuJoCo simulator**. You can find the demo and analysis code in the `notebook/` folder.

### ✅ Recommended Usage

We **strongly recommend** running the visualization demo to understand the data structure and motion patterns.




### Install Dependencies To Run Visualization Code
```bash
pip install -r requirements.txt
```

For questions or collaborations, please contact the authors listed in the [paper](https://arxiv.org/abs/2502.12602).