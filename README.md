# Sign Language Recognition 🎯

A real-time sign language recognition system that uses deep learning and computer vision to interpret hand gestures into meaningful actions. This project is our final-year capstone, showcasing advanced gesture recognition techniques.

---

## Features 🌟

- **Real-time Gesture Recognition**: Recognizes gestures like `hello`, `thanks`, and `love you` using a webcam feed.
- **Custom Model Training**: Implements an LSTM-based neural network for accurate predictions.
- **MediaPipe Integration**: Utilizes MediaPipe for real-time keypoint detection.
- **Jupyter Notebook Workflow**: A modular and interactive implementation using Python notebooks.
- **Data Visualization**: Visualizes recognition results dynamically in the video feed.

---

## Technology Stack 🛠️

- **Languages**: Python
- **Libraries**:
  - TensorFlow & Keras (Deep Learning)
  - MediaPipe (Keypoint Detection)
  - OpenCV (Image Processing)
  - NumPy (Data Manipulation)
  - Matplotlib (Result Visualization)
  - Scikit-learn (Data Splitting)

---

## Workflow 🚀

### 1. **Data Collection**:
   - MediaPipe is used to detect keypoints.
   - Data is saved as `.npy` files for gestures (`hello`, `thanks`, `love you`).

### 2. **Model Training**:
   - Sequential LSTM-based model processes keypoint sequences.
   - Model is trained on gesture data for 700 epochs.
   - Best weights are saved using `ModelCheckpoint`.

### 3. **Real-time Recognition**:
   - Keypoints are extracted from live webcam feed.
   - The trained model predicts gestures based on input frames.
   - Results are displayed in real-time.

---

## Usage 🖥️

### Prerequisites:
1. Install the required Python libraries:
   ```bash
   pip install tensorflow opencv-python mediapipe numpy matplotlib scikit-learn

## Run the Project:
    git clone <repository-link>
    cd signlanguage-recognition

## Screenshots
<img width="716" alt="Screenshot 2024-12-01 at 8 14 38 PM" src="https://github.com/user-attachments/assets/f594a82e-bcd0-40bf-aa86-4de15bced1af" />
<img width="1392" alt="Screenshot 2024-12-01 at 8 01 03 PM" src="https://github.com/user-attachments/assets/54136eea-8195-4904-ad9b-d8a3e3ed1deb" />
<img width="1392" alt="Screenshot 2024-12-01 at 8 01 26 PM" src="https://github.com/user-attachments/assets/9947b8b4-eb97-4cd1-83d5-b78de9b028cb" />

## Challenges Faced 🧗‍♂️
	•	Managing sequential data for model training.
	•	Ensuring the model performs in real-time with webcam input.
	•	Debugging MediaPipe integration with TensorFlow.

## Contributors ✨
	•	Priyansh Rana
	•	Geetansh Anand
	•	Deepanshu Kumar Mani

## Acknowledgments 🙏
	•	Thanks to MediaPipe for their efficient pose detection.
	•	Guided by Mr. Puneet Mittal Sir.



