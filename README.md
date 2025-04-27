# 🌊 Underwater Plastic Pollution Detection using YOLOv11

This project fine-tunes a YOLOv11-Nano model to detect plastic waste in underwater environments, helping promote cleaner oceans and marine conservation.

## 📚 Dataset

- **Underwater Plastic Pollution Detection**  
  Kaggle Link: [https://www.kaggle.com/datasets/arnavs19/underwater-plastic-pollution-detection](https://www.kaggle.com/datasets/arnavs19/underwater-plastic-pollution-detection)

## 🧠 Model

- **YOLOv11-N** pre-trained weights
- Fine-tuned on underwater plastic dataset
- Ultralytics YOLO interface used for training and inference

## 🚀 Workflow

1. Install dependencies
2. Load YOLOv11 pre-trained model
3. Perform object detection on sample images
4. Fine-tune model using underwater dataset
5. Save and evaluate the final model

## 🧰 Dependencies

- `ultralytics`
- `opencv-python`
- `pandas`
- `Pillow`
- `numpy`
- `matplotlib`

## 🔧 How to Run

```bash
pip install -r requirements.txt
# Then run the notebook:
snail-cv.ipynb
