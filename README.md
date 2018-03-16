# Automatic Attendance System
### Dependencies-

    Python 2.7 or 3+
    OS: linux, windows
    Python libraries - OpenCV and dlib All the dependencies should be met before installing face_recognition module
    
### Installation:
    pip install pandas
    pip install numpy
    pip install face_recognition

## attendanceSystem folder contains two python codes-

    attendanceSystem.py - gui + face recognizer(open this to run software)
    face_re.py - face identifier and recognizer

    It also contains 'Images' folder in which we keep the set of images of faces which we want to recognize. **Kindly change the path of your Images folder in the code of attendanceSystem.py
    

Note: GPU acceleration (via nVidia’s CUDA library) is required for good performance with this model. You’ll also need to enable CUDA support when compliling dlib.

## Project Title – Automated Attendence System

This system automatically marks the attendence of students that are coming inside a room by recognizing their faces using camera and then storing the name of the person in the attendance list (if the person is already stored in the database, if not, it gives the output as unknown) 

## Applications:

The software can be used to mark the attendance of the participants in any event. The concerned software is developed mainly for schools, colleges, etc. It is a viable option to the biometric system, currently in usage in most of the institutions. The system just requires the images of the concerned people. The software recognises the person(if the image matches with one of those stored in the database) and even records the time of entry. This data is stored in a file in .csv format, which can be accesed by the professor. Thus, transparency is ensured regarding the time of entry of the students. It can also be used in seminars or meetings, which involve top level authorities where security is one of the primary concerns. In the above mentioned case, the images of the attendees can be feeded into the system. As a result, an unknown person cannot enter and the chances of security breach are almost nil.

## Benefits:

1.**Time Saving:** Generally taking the attendance of students is a time consuming process in the case of class involving a large number of students. This time can be reduced and more time can be devoted to teaching, if this system is used.

2.**Accountability:** Since the problem we are dealing is of less attendence in government schools. The reason behind this is very less interest of teachers in teaching. With this system we can even monitor the teachers as well. So our system will automatically capture the time and name of person and strict action can be taken if someone is not coming on time on school.

3.**Transparency:** Since it automatically marks attendence based upon the video feed, there is full transparency in terms of who is present or who is absent. Nobody can alter this result based upon their wish. There can be no adulteration with attendence of students and teachers and exact attendence will be recorded. This will lead to punctuality on the parts of teachers and students as they now know that their attendence is being taken by software.

## Demo:
![Alt text](Attendance_sample.png?raw=true "Attendance")
