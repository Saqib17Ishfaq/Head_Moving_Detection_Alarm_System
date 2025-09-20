Head Moving Detection Alarm System

This project uses OpenCV, Mediapipe, and winsound to monitor head movement and eye closure in real time using a webcam.
If the user turns their head left/right or keeps their eyes closed for more than 3 seconds, an alarm sound is triggered.
It also records the webcam feed into an output.mp4 file.

🚀 Features

✅ Detects head movement (left/right).
✅ Detects eye closure (for drowsiness detection).
✅ Plays an alarm beep if the user’s head is turned or eyes are closed for more than 3 seconds.
✅ Records video output as output.mp4.
✅ Press Q to exit gracefully.

🛠️ Technologies Used

Python 3
OpenCV
 – Computer vision library
Mediapipe
 – Face landmark detection
Winsound
 – Sound for alarm (Windows only)

 🎯 Usage

Run the script → Webcam will start.
Move your head left/right → Alarm triggers after 3 seconds.
Close your eyes → Alarm triggers after 3 seconds.
Press Q to stop and close the camera.

📹 Demo Output
A video recording will be saved as output.mp4 in the project folder.

🔮 Future Improvements

Cross-platform alarm support (Linux/Mac).
Add yawning detection for better drowsiness monitoring.
GUI for easier user interaction.
