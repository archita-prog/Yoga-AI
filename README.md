Yogi AI: Real-Time Yoga Pose Correction

Yogi AI is an innovative computer vision project that provides real-time feedback on yoga poses. Using AI-powered pose estimation, the application detects key body landmarks and analyzes them to determine the correctness of a user's pose. Whether you're a beginner or an experienced yogi, this tool helps improve your form and prevent injuries.

| Feature | Status |
| :--- | :--- |
| Real-time Pose Detection| ✅ |
| Angle & Form Analysis | ✅ |


Features
Live Pose Tracking: Utilizes a webcam feed to identify and track a user's body landmarks in real time.
Pose Recognition: Accurately recognizes various yoga poses.
Performance Analysis: Calculates angles between key joints (e.g., knee, elbow, hip) to evaluate pose correctness.
Visual Feedback:Provides on-screen indicators and instructions to guide the user toward the correct form.

-----

Installation

To get started with Yogi AI, you'll need Python 3.7 or higher. Follow these steps to set up your environment:

1.  Clone the repository:

    ```
    git clone https://github.com/your-username/yogi-ai.git
    cd yogi-ai
    ```

2.  Create and activate a virtual environment (recommended):

    ```
    python -m venv venv
    # On Windows:
    .\venv\Scripts\activate
    # On macOS/Linux:
    source venv/bin/activate
    ```


 Usage

To run the application, ensure your virtual environment is active and execute the main Python script:

```
python main.py
```

The application will launch your webcam and begin real-time pose detection. Follow the on-screen prompts and try out different yoga poses\!

-----
Technologies Used

Python: The core programming language for the project.
OpenCV: An open-source computer vision library used for processing the video stream and drawing visualizations.
MediaPipe:A machine learning framework by Google for real-time human pose estimation.
NumPy:A library for numerical operations and efficient array manipulation.

-----
Contributing

Contributions are welcome\! If you'd like to improve the project, feel free to fork the repository and submit a pull request with your changes. 

-----

