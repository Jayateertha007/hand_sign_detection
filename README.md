
🤟 Sign Language Detection using OpenCV & Streamlit
This project is a real-time Sign Language Detection system built with OpenCV, Streamlit, and a custom Hand Tracking Module. It uses webcam input to detect hand gestures and classify common signs like Hello, Yes, Please, Like, Dislike, and Thank You.

🎯 Features
🖐️ Real-time Hand Tracking: Uses OpenCV and a custom HandTrackingModule to detect hands and finger landmarks.

🤖 Gesture Recognition: Recognizes signs based on finger positions and 3D normal vectors.

💬 Predefined Sign Detection: Supports detection for:

Hello

Yes

Please

Nice

Like

Dislike

Thank You

🎛️ Streamlit Interface: Start/Stop webcam via UI buttons and view detection results live in the browser.

🧱 Tech Stack
Frontend: Streamlit (for interactive UI)

Computer Vision: OpenCV

Hand Tracking: Custom module (HandTrackingModule.py) using MediaPipe or cv2-based logic

Language: Python

🗂️ Project Structure
bash
Copy
Edit
├── app.py                        # Main Streamlit app
├── HandTrackingModule.py        # Custom hand detection module
├── requirements.txt             # Dependencies list
⚙️ How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/sign-language-detection.git
cd sign-language-detection
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Run the app:

bash
Copy
Edit
streamlit run app.py
Allow access to the webcam when prompted.

🚨 Notes
You must have a webcam for real-time detection.

The hand tracking is done in a lightweight and interactive way via the browser.

More gestures can be added by extending the conditionals in the detection logic.

