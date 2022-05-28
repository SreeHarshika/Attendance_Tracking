# Attendance_Tracking
A python GUI integrated attendance system using face recognition to take attendance.

In this python project, I have made an attendance system which takes attendance by using face recognition technique. I have also intergrated it with GUI (Graphical user interface) so it can be easy to use by anyone. GUI for this project is also made on python using tkinter.
//REQUIREMENTS USED:
pip install tk-tools
pip install opencv-contrib-python
pip install datetime
pip install pytest-shutil
pip install python-csv
pip install numpy
pip install pillow 
pip install pandas
pip install times
//PASSWORD USED:
456 (can be modified) for new registrations
//TECHNOLOGY USED:
1) tkinter for whole GUI
2) OpenCV for taking images and face recognition (cv2.face.LBPHFaceRecognizer_create())
3) CSV, Numpy, Pandas, datetime etc. for other purposes.

//FEATURES:
1) Easy to use with interactive GUI support.
2) Password protection for new person registration.
3) Creates/Updates CSV file for deatils of students on registration.
4) Creates a new CSV file everyday for attendance and marks attendance with proper date and time.
5) Displays live attendance updates for the day on the main screen in tabular format with Id, name, date and time.
6) It can also identify faces with masks.
