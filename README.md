# 🚗 Vehicle Number Plate Detection

This project is a simple computer vision-based application that detects and extracts vehicle number plates from images using OCR.

It was developed as an experimental mini project during my 3rd year of college to explore image processing and text recognition.

---

## 📌 Overview

The goal of this project is to:

* Detect vehicle number plates from an input image
* Extract the text from the number plate
* Display the detected number directly on the image

This project focuses on combining basic image processing techniques with OCR to solve a real-world problem.

---

## ⚙️ Tech Stack

* Python
* OpenCV
* EasyOCR
* NumPy

---

## 🚀 How It Works

1. Upload or provide a vehicle image
2. The image is processed using OpenCV
3. Regions likely to contain number plates are identified
4. EasyOCR is used to extract text from those regions
5. The detected number plate is displayed on the image

---

## 📂 Project Structure

```
├── images/              # Sample input images
├── output/              # Processed output images
├── main.py              # Main script
├── requirements.txt     # Dependencies
└── README.md
```

---

## 🛠️ Installation

Clone the repository:

```bash
git clone https://github.com/taibaakhtar/Vehicle-Number-Plate-Detection.git
cd Vehicle-Number-Plate-Detection
```

Install dependencies:

```bash
pip install easyocr
pip install imutils
```

---

## 📸 Sample Output

* Input: Vehicle image
* Output: Image with detected number plate and extracted text

---

## ⚠️ Limitations

* Works best with clear and well-lit images
* Performance may drop for:

  * Blurry images
  * Low or high resolution inputs
  * Obstructed number plates
* Not optimized for real-time detection

---

## 💡 Future Improvements

* Improve accuracy using deep learning-based detection models (e.g., YOLO)
* Add real-time detection using live stream/video
* Deploy as a web application
* Enhance preprocessing for better OCR performance

---

## 🎯 Learning Outcome

This project helped in understanding:

* Basics of computer vision
* Image preprocessing techniques
* OCR integration
* Working with real-world unstructured data

---

## 🤝 Contributing

Feel free to fork this repo and improve the project!

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 🙌 Acknowledgment

* EasyOCR for text recognition
* OpenCV for image processing

---
