Yoga AI: Real-Time Yoga Pose Correction

Yogi AI is a computer vision–powered application that provides **real-time feedback on yoga poses**. Using AI-based pose estimation, the app detects key body landmarks, analyzes angles, and evaluates posture correctness. Whether you're a beginner or an advanced yogi, Yogi AI helps you **improve your form, enhance performance, and reduce injury risks**.

---

Features

| Feature                  | Status |
| :----------------------- | :----- |
| Real-time Pose Detection | ✅      |
| Angle & Form Analysis    | ✅      |
| Visual Feedback          | ✅      |
| Pose Recognition         | ✅      |

* **Live Pose Tracking**: Uses your webcam to track body landmarks in real time.
* **Pose Recognition**: Detects and classifies multiple yoga poses with high accuracy.
* **Performance Analysis**: Computes joint angles (knee, elbow, hip, etc.) to assess correctness.
* **Visual & Textual Feedback**: Provides on-screen indicators and step-by-step corrections.

---

Installation

Make sure you have Python 3.7+ installed. Then, follow these steps:

Clone the repository

   ```bash
   git clone https://github.com/your-username/yogi-ai.git
   cd yogi-ai
   ```

   Create & activate a virtual environment

   ```bash
   python -m venv venv

   # On Windows:
   .\venv\Scripts\activate

   # On macOS/Linux:
   source venv/bin/activate
   ```

Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

---

Usage

Run the main script to start real-time yoga pose correction:

```bash
python main.py
```

Your webcam will open, and Yogi AI will begin **pose detection & analysis**.
Follow the on-screen instructions and practice different yoga poses!

---

Technologies Used

  Python → Core programming language
  OpenCV → Video stream processing & visualization
  MediaPipe → Real-time pose estimation (Google ML framework)
  NumPy→ Efficient numerical computations







