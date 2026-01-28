# AI-Based Traffic Congestion Management 🚦

This project implements an **AI-based traffic congestion management system** that dynamically adjusts traffic signal timing using **machine learning for vehicle detection** and **intelligent decision-making logic**.

The system processes traffic lane images or video input to detect vehicles and assign adaptive green signal time instead of using fixed mathematical formulas.

---

## 📂 Project Structure

```
AI PROJECT/
├── Lane1.jpg
├── Lane2.jpg
├── Lane3.jpg
├── Lane4.jpg
├── model.ipynb
├── yolov8n.pt
├── output.jpg
├── sample.mp4
├── traffic.png
└── .ipynb_checkpoints/
```

---

## ⚙️ How the System Works

1. Input traffic images or video frames from multiple lanes  
2. Detect and count vehicles using YOLOv8  
3. Apply AI-based decision logic to compute green signal timing  
4. Display results and save detection output  

---

## 🛠️ Requirements

- Python 3.8+
- Jupyter Notebook
- OpenCV
- Ultralytics (YOLOv8)
- NumPy

---

## 🚀 How to Run the Project

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/traffic-congestion-management.git
cd traffic-congestion-management
```

### Step 2: Install Dependencies
```bash
pip install opencv-python ultralytics numpy
```

### Step 3: Open the Notebook
```bash
jupyter notebook model.ipynb
```

### Step 4: Run the Notebook
- Execute all cells in order
- Vehicle counts and green signal time will be displayed
- Output image will be saved as `output.jpg`

---

## 🧠 Why This Is AI (Not Just ML)

- ML handles vehicle detection
- AI logic handles decision-making
- Signal timing adapts to traffic conditions

---

## 📌 Use Cases

- Smart traffic signal control
- Traffic congestion analysis
- Academic AI projects
- Internship portfolio projects

---

## 📜 License

For academic and educational use only.
