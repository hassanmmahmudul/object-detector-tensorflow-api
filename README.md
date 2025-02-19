# Object Detection Tensorflow API
# **Object Detection Using TensorFlow Object Detection API**

## **Project Overview**

This project aims to build an object detector from scratch using the **TensorFlow Object Detection API**. The goal is to train a **Faster R-CNN** model with a **ResNet101** backbone on the **satellite image dataset**. The project involves:

- **Data Collection: Satellite image dataset**
- **Annotation**
- **Model Training**
- **Evaluation**
- **Inference**

---

## **Dataset**


<details>
<summary>🌍 **Satellite Image Dataset**</summary>

- **Source**: [Kaggle Dataset](https://www.kaggle.com/ancaco12/aerial-satellite-images/metadata)
- **Image count**: 
  - **200 satellite images (640x640 resolution) for training**
  - **40 images for validation**
- **Three object detection classes**:
  - 🏊 `Piscina` (swimming pool)
  - 🔄 `Rotonda` (traffic circle/roundabout)
  - 🅿 `Parking`

</details>

---

## **🛠 Tools Used**
- **TensorFlow Object Detection API**
- **`labelImg`** for image annotation
- **Google Colab** for training
- **Faster R-CNN with ResNet101** as backbone

---

## **📂 Project Structure**
```plaintext
├── data/                # Dataset files (images and annotations)
├── models/              # TensorFlow model repository
├── training/            # Training checkpoints
├── output/              # Exported trained model
├── test/                # Test images for evaluation
├── label_map.pbtxt      # Label map file
├── pipeline.config      # Model configuration file
└── object-detection-tensorflow-api.ipynb  # Python Notebook
