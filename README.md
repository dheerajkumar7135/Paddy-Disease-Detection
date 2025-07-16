# 🌾 Paddy Crop Disease Detection using VGG16

This repository contains an implementation of **VGG16** for classifying various paddy crop diseases. The model helps farmers and agronomists detect leaf diseases early through image-based analysis.

## 📌 Model Architecture: VGG16

- Used **VGG16** by constructing it from scratch.
- Appended custom dense layers for disease classification.
- Employed image augmentation and preprocessing techniques to enhance model robustness.
- Fine-tuned Hyper parameters according to the dataset.

## 📊 Dataset

- Contains labeled thermal images of paddy leaves.
- Includes diseases such as bacterial blight, brown spot, leaf smut, etc.
- Performed data augmentation: rotation, flipping, zooming, and cropping.

## ⚙️ Features

- Accurate classification of paddy leaf diseases from images.
- Early detection capability for better yield management.
- Supports transfer learning and fine-tuning.

## 🛠️ Technologies Used

- Python, TensorFlow, Keras
- OpenCV for image processing
- Google Colab for training and experimentation

---


## 🙏 Acknowledgements

- Thanks to **Kaggle** and open-source contributors for providing image datasets.
- Special mention to the academic community and Google Colab for resources.

---

## 📄 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.
