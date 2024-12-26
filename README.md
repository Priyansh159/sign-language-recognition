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



