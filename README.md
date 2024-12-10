# Attendance-Management-System-using-Facial-Recognition.

**Project Description**

The **Attendance Management System** leverages facial recognition technology to automate attendance tracking, ensuring **accuracy, efficiency, and authenticity**. By replacing traditional manual attendance methods, this system minimizes errors, prevents proxy attendance, and streamlines the process for educational institutions and workplaces.

**Key Functionalities**

1. **Face Registration**: Register and capture students’ or employees’ images.
2. **Face Detection & Recognition**: Uses the **Viola-Jones algorithm** and **Local Binary Patterns** for accurate face detection and identification.
3. **Attendance Logging**: Automatically marks attendance and stores it in a database with timestamps.
4. **Report Generation**: Provides easy-to-access attendance reports.

Attendance Management System Using Face Recognition
Overview
This project provides an automated Attendance Management System using real-time facial recognition. By replacing traditional manual attendance methods with a tech-driven approach, this system ensures efficient, accurate, and authentic attendance tracking for educational institutions and workplaces.

Features
Facial Recognition: Automatically captures and verifies attendance via real-time face detection.
User-Friendly GUI: Built with Tkinter, making it easy to interact and operate.
Attendance Logs: Stores attendance data with timestamps for easy record-keeping.
Image Storage: Captures and saves images of registered faces for training purposes.
Real-Time Capture: Efficiently processes live video feed for face recognition.

Technologies Used
Python: Core programming language.
OpenCV: For face detection and recognition.
Tkinter: For building the graphical user interface.
Pandas: To manage and manipulate attendance data.

Installation & Setup

Clone the Repository:
git clone https://github.com/Pujitha-user/Attendance-Management-System.git


Install Dependencies:
pip install opencv-python-headless pandas tk


Run the Application:
python main_app.py

   

 **Technologies**

- **Python**
- **OpenCV** (for image processing)
- **Tkinter** (for GUI)
- **Pandas** (for data handling)
- **MySQL** (for database management)
  
- **File Structure**
                ├── main_app.py          # Main application file

                ├── train_model.py       # Script to train the face recognition model

                ├── Attendance/          # Stores attendance CSV files

                ├── TrainingImage/       # Stores captured images for training

                └── haarcascade_frontalface_default.xml  # Pre-trained Haar Cascade for face detection


**How It Works**

1. **Capture**: Real-time image capture using a webcam.
2. **Detect**: Identify faces using the **Viola-Jones algorithm**.
3. **Recognize**: Match the detected face with the stored database using **Local Binary Patterns**.
4. **Log**: Record attendance in the database with accurate timestamps.

 **Future Improvements**

- Integration of **deep learning models** for enhanced recognition accuracy.
- Development of a **mobile app version** for convenient usage.
- Implementing **cloud-based storage** for scalability and secure data management.

 **Why This Project Matters**

This system addresses the limitations of traditional attendance methods by ensuring:
- **Error Reduction**: Minimizes manual entry mistakes.
- **Proxy Prevention**: Reduces fraudulent attendance marking.
- **Efficiency**: Saves time and automates routine tasks.

For any questions or issues, feel free to contact pujitha.puja.reddy@gmail.com
