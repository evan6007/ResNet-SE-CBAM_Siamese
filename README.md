# ResNet-SE-CBAM Siamese + KNN Classifier

A Siamese network combining ResNet, SE (Squeeze-and-Excitation), and CBAM (Convolutional Block Attention Module), followed by a KNN classifier for defect detection.

---

## 🔥 Colab Demo

Click the link below to try it directly on Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://colab.research.google.com/github/evan6007/ResNet_SE_CBAM_KNN/blob/main/ResNet_SE_CBAM_KNN_demo.ipynb](https://colab.research.google.com/drive/1kLoaVsBMfykAern0G3JncQDnrsTc3D6I?usp=sharing))

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
