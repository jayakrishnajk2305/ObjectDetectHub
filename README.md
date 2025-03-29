### 🧠 Object Detection Using OpenCV, Detectron2 & YOLOv5

This mini-project demonstrates how to perform **object detection** using three powerful tools in computer vision: **OpenCV**, **Detectron2**, and **YOLOv5**. The project is implemented in a Jupyter Notebook using Python.

---

## 📂 Project Structure

```
📁 your-repo-name/
│
├── OPENCV.ipynb           # Main Jupyter notebook with object detection code
├── requirements.txt       # Python dependencies (optional)
└── README.md              # This file
```

---

## 🚀 Libraries Used

- **OpenCV** – For image/video manipulation and basic detection tasks.
- **Detectron2** – Facebook AI Research’s library for state-of-the-art object detection.
- **YOLOv5** – Ultralytics’ real-time object detection framework.
- **PyTorch** – Backend for Detectron2 and YOLOv5.

---

## 🔍 What This Project Does

1. **Image Input using OpenCV**
   - Loads an image using OpenCV.
   - Basic visualization using `cv2.imshow`.

2. **Object Detection using Detectron2**
   - Initializes a pre-trained Detectron2 model (e.g., Faster R-CNN or Mask R-CNN).
   - Performs inference on the input image.
   - Displays the predicted bounding boxes and classes.

3. **Object Detection using YOLOv5**
   - Uses a pre-trained YOLOv5 model.
   - Inference on the image.
   - Visualizes results with bounding boxes and confidence scores.

---

## 📸 Sample Output

> You can include screenshots here, like:
- Image before detection
- Image after Detectron2 detection
- Image after YOLOv5 detection

---

## 🛠️ How to Run

1. **Clone the repo**
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies**
   - Create a virtual environment (optional):
     ```bash
     python -m venv venv
     source venv/bin/activate  # or venv\Scripts\activate on Windows
     ```

   - Install required packages:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run the Notebook**
   - Open the Jupyter Notebook:
     ```bash
     jupyter notebook OPENCV.ipynb
     ```

---

## ✅ Results

- Detectron2 successfully detects multiple objects with high accuracy.
- YOLOv5 runs fast and shows competitive results.
- The notebook allows a side-by-side comparison of both models.

---

## 📚 Future Improvements

- Support for video streams and real-time webcam detection.
- Add more models (like YOLOv8 or SSD).
- Deployment as a web app using Streamlit or Flask.

---

## 🙋‍♂️ Author

**Jaya Krishna Sangoju**  
🔗 [LinkedIn](https://www.linkedin.com) | 📧 jaya23krishna2000@example.com

---

