Face Recognition Attendance System 🎯

A real-time face recognition system that automatically marks attendance and stores records in a CSV file.

Built using Python and OpenCV, this project detects faces from a live webcam feed, matches them against stored images, and logs verified identities with timestamps — fully automated and contactless.

🚀 Project Overview

This system:

Captures live video using webcam 📷

Detects and encodes facial features 🧠

Compares faces with stored dataset

Identifies matched individuals

Logs name and time into Attendance.csv 📄

Prevents duplicate entries automatically

The dataset currently includes sample identities such as:

Kendall Jenner

Kylie Jenner

Hailey Bieber

Elon Musk

🛠 Tech Stack

Python 🐍

OpenCV 👁️

face_recognition

NumPy

CSV file handling 📊

📂 Project Structure
FACE_RECOGNITION/
│
├── .venv/
├── ImagesAttendance/        # Stored face images
│   ├── Kendall.jpg
│   ├── Kylie.jpg
│   ├── Hailey.jpg
│   └── Elon.jpg
│
├── AttendanceProject.py     # Main face recognition script
├── Basics.py                # Supporting script
├── Attendance.csv           # Attendance records
├── requirements.txt
└── README.md
⚙️ How It Works

Load images from ImagesAttendance/

Generate face encodings

Start webcam feed 📷

Detect faces in each frame

Compare with known encodings

If matched → log name and current time into Attendance.csv ⏱️

Efficient. Accurate. Real-time.

📑 Sample Attendance Format
Name, Time
KENDALL, 09:15:23
KYLIE, 09:17:02
HAILEY, 09:20:11
💻 Installation

Clone the repository:

git clone https://github.com/your-username/Face_Recognition.git
cd Face_Recognition

Install dependencies:

pip install -r requirements.txt

Run the project:

python AttendanceProject.py
🌟 Future Improvements

Excel (.xlsx) integration

Web-based dashboard 🌐

Database storage

Admin authentication 🔐

Attendance analytics and reports 📈

👩‍💻 Author

Aasrita Sangani
B.Tech CSE (AIML)
