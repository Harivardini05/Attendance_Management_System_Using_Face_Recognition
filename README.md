---

# **Attendance Management System Using Face Recognition**

## **Table of Contents**
1. [Introduction](#introduction)  
2. [Features](#features)  
3. [Technologies Used](#technologies-used)  
4. [Installation](#installation)  
5. [Usage](#usage)  
6. [Screenshots/Demo](#screenshots-demo)  
7. [License](#license)  
8. [Acknowledgments](#acknowledgments)
9. [Modifications](#modifications)
10. [Contribution](#contribution)

---

## **Introduction**

> This project is an advanced **Attendance Management System** that utilizes face recognition technology to automate and streamline the process of tracking attendance. By integrating machine learning techniques for facial detection and recognition, it eliminates the need for traditional manual or biometric systems.  
> The project is designed for schools, colleges, and organizations to ensure accurate, fast, and secure attendance management.

---

## **Features**
Key features of the project include:  
- **Face Detection and Recognition**: Uses facial recognition to mark attendance.  
- **Real-Time Attendance Tracking**: Detect faces via a live webcam feed.  
- **Secure and Reliable**: Prevents unauthorized access.  
- **Attendance Report Generation**: Generates attendance reports in a tabular format.  
- **Scalability**: Can handle multiple users and faces.  
- **Customizable User Database**: Allows adding/removing users.

---

## **Technologies Used**
This project was built using the following technologies:  

- **Programming Language**: Python  
- **Libraries and Frameworks**:  
  - OpenCV (for face detection)  
  - NumPy  
  - Pandas (for report generation)  
  - Tkinter (for GUI)  
  - Face Recognition (dlib-based library)  
- **Database**: CSV file-based storage for attendance records.  
- **Other Tools**: Webcam for live face detection.

---

## **Installation**

Follow these steps to set up the project on your local machine:  

### Prerequisites:
1. Install Python (version >= 3.7).  
2. Ensure your system has a working webcam.  
3. Install the required libraries using `pip`.  

### Steps:
1. Clone the repository:  
   ```bash
   git clonehttps://github.com/Harivardini05/Attendance_Management_System_Using_Face_Recognition.git
   cd Attendance_Management_System_Using_Face_Recognition
   ```

2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:  
   ```bash
   python main.py
   ```

4. To add new users to the system:  
   - Add images of new users in the `dataset` folder.  
   - Run the encoding script:  
     ```bash
     python encode_faces.py
     ```

---

## **Usage**

### Steps to Use:
1. Start the application by running `main.py`.  
2. The system will open the webcam and start detecting faces.  
3. If a recognized face is detected, the attendance will be marked automatically.  
4. Access attendance reports in the `attendance` folder.  

### File Structure:
- `dataset`: Stores images of registered users.  
- `attendance`: Contains generated attendance reports.  
- `encode_faces.py`: Encodes images into face recognition data.  

---
# Screenshots/Demo
Screenshot 1: Report interface

![1](https://github.com/user-attachments/assets/946f787c-3564-426c-9560-8b2afaf12b3e)


Screenshot 2: Face Detection in Action

![2](https://github.com/user-attachments/assets/ffbecc44-326d-40a7-b6e6-518f3fb24bb0)




## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## **Acknowledgments**

Special thanks to:  
- The developers of the [Face Recognition library](https://github.com/ageitgey/face_recognition).  
- OpenCV contributors for their open-source computer vision tools.  




## **Modifications**

Suggested improvements for the project:  
1. **Database Integration**: Replace the CSV system with MySQL or MongoDB for scalability.  
2. **Email Notifications**: Send attendance status updates to users via email.  
3. **Data Visualization**: Add graphs to visualize attendance trends.  
4. **Improved GUI**: Use a modern interface like PyQt or a web-based frontend.  
5. **Role-Based Access**: Implement admin and user roles for better access control.  

---

## **Contributing**

We welcome contributions!  

### Steps to Contribute:
1. Fork the repository and clone it to your system:  
   ```bash
   git clone https://github.com/your-username/Attendance_Management_System_Using_Face_Recognition.git
   ```  
2. Create a new branch:  
   ```bash
   git checkout -b feature-name
   ```  
3. Make changes and test them thoroughly.  
4. Commit your changes:  
   ```bash
   git commit -m "Add: Description of your feature"
   ```  
5. Push your changes and open a pull request.  

---
# Grateful for Your Support!

I extend my heartfelt gratitude to my mentor, Aditya Ardak, for his invaluable guidance and encouragement throughout the course of this project. His sessions were insightful and greatly enhanced my understanding, making this journey an enriching experience.

I am also deeply thankful to the team for providing me with the opportunity to work on this project. It has been an incredible learning experience, and I have gained a wealth of knowledge and skills along the way.



