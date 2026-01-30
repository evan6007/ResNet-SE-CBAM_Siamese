# ResNet-SE-CBAM Siamese + KNN Classifier

A Siamese network combining ResNet, SE (Squeeze-and-Excitation), and CBAM (Convolutional Block Attention Module), followed by a KNN classifier for defect detection.

---

## 🔥 Colab Demo

Click the link below to try it directly on Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1kLoaVsBMfykAern0G3JncQDnrsTc3D6I?usp=sharing)


---

## 🖼️ Example Results

🔴 **Red circle:** Correctly predicted **pass**  
❎ **Green cross:** Correctly predicted **ng**  

<div align="center">
  <img src="https://github.com/evan6007/ResNet-SE-CBAM_Siamese/blob/main/Resnet_se_cbam_knn_demo_image.jpg" width="600">
</div>



---

## 🚀 How to Run

1. Download the pretrained model and test images:

```bash
wget https://huggingface.co/evan6007/ResNet_SE_CBAM_KNN/resolve/main/R_image.zip -O R_image.zip
wget https://huggingface.co/evan6007/ResNet_SE_CBAM_KNN/resolve/main/resnet_se_cbam_40_20.pth -O resnet_se_cbam_40_20.pth
unzip R_image.zip
```

---
## 📖 Reference
[https://www.mdpi.com/1424-8220/25/13/4233](https://www.mdpi.com/1424-8220/25/13/4233)<br>
ResNet-SE-CBAM Siamese Networks for Few-Shot and Imbalanced PCB Defect Classification<br>
Chao-Hsiang Hsiao, Huan-Che Su, Yin-Tien Wang, Min-Jie Hsu, and Chih-Chiang Hsu > Sensors 2025, 25(13), 4233; DOI: 10.3390/s25134233

<details>
<summary><b>📋citation (BibTeX) </b></summary>

```bibtex
@Article{sensors25134233,
AUTHOR = {Hsiao, Chao-Hsiang and Su, Huan-Che and Wang, Yin-Tien and Hsu, Min-Jie and Hsu, Chih-Chiang},
TITLE = {ResNet-SE-CBAM Siamese Networks for Few-Shot and Imbalanced PCB Defect Classification},
JOURNAL = {Sensors},
VOLUME = {25},
YEAR = {2025},
NUMBER = {13},
ARTICLE-NUMBER = {4233},
URL = {[https://www.mdpi.com/1424-8220/25/13/4233](https://www.mdpi.com/1424-8220/25/13/4233)},
DOI = {10.3390/s25134233}
}
