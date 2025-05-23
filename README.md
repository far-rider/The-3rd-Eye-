# The-3rd-Eye-
Behavior Analysis Through Cctv Feed To Prevent Potential Threats .Involves Ai- Driven System Which Detects And Alert Real Time Security Threats Reduce Rely On Manual Monitoring
Here’s a professional `README.md` for your GitHub project based on the contents of your script, titled **THE THIRD EYE PROJECT**:

---

```markdown
# 🧠 THE THIRD EYE PROJECT 🔍🎥

An AI-powered real-time surveillance system that combines object detection, human pose estimation, and sequence prediction to identify potentially suspicious or dangerous behavior in a monitored area.

## 🚀 Features

- ✅ **YOLOv8** for real-time weapon detection
- ✅ **MediaPipe** for human pose estimation
- ✅ **ResNet50** for feature extraction
- ✅ **LSTM** network for behavioral pattern recognition
- ✅ Real-time alert system on detecting suspicious activity
- ✅ Works with live webcam or video files

---

## 🧰 Tech Stack

- `Python`
- `TensorFlow` / `Keras`
- `OpenCV`
- `MediaPipe`
- `YOLOv8` via `ultralytics`
- `NumPy`, `scikit-learn`

---

## 📁 Dataset Structure

You need a dataset organized like this:

```

weapon-detection.v1i.createml/
├── train/
│   ├── img1.jpg
│   └── ...
├── valid/
│   ├── imgA.jpg
│   └── ...

````

- Images in `train/` are labeled **positive (1)** — e.g., suspicious.
- Images in `valid/` are labeled **negative (0)** — e.g., normal activity.

---

## 🧪 How It Works

1. 🔍 **YOLOv8** detects weapons like knives or guns in frames.
2. 🏃 **MediaPipe** tracks human pose.
3. 🧠 A **ResNet50** model extracts spatial features from video frames.
4. 🧮 A **stacked LSTM** analyzes feature sequences over time to classify behavior.
5. 🚨 If LSTM predicts suspicious behavior, an **alert** is displayed on screen.

---

## 🖥️ Running the Project

### 🛠️ Requirements

Install dependencies:

```bash
pip install opencv-python mediapipe tensorflow ultralytics numpy scikit-learn
````

### ▶️ Start Live Surveillance

Edit the dataset path in `main`:

```python
DATASET_PATH = r"your_dataset_path_here"
```

Then run:

```bash
python THE\ THIRD\ EYE\ PROJECT.py
```

* Press `q` to exit the live feed.

---

## 🎯 Applications

* Public safety in transportation hubs, malls, schools, and airports
* Behavior monitoring in high-risk zones
* Intelligent alert systems for security teams

---

## 🧠 Model Training

The project automatically:

* Extracts image features using ResNet50
* Prepares time-series data
* Trains LSTM on suspicious vs. normal behavior
* Starts real-time prediction

---

## 📸 Example

![demo](https://via.placeholder.com/600x300?text=Live+Detection+Demo)

---



## 📜 License

This project is licensed under the MIT License.

---

> ⚠️ This system is a prototype and should be validated before real-world use.

`
