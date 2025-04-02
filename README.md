DynamicHumanAuth
DynamicHumanAuth is a real-time facial recognition system designed to enhance organizational security by preventing unauthorized access. Leveraging the Local Binary Patterns Histogram (LBPH) algorithm, this project offers an efficient and accurate method for identifying individuals attempting to enter secure areas.

Table of Contents
Overview

Features

Technologies Used

Installation

Usage

Contributing

License

Overview
In today's security landscape, controlling access to sensitive areas is paramount. DynamicHumanAuth addresses this need by implementing a dynamic human authentication system that utilizes real-time face recognition. Authorized personnel images are stored in a database, and the system continuously monitors entry points using IP cameras. When an unrecognized individual attempts to gain access, the system promptly alerts security personnel, thereby mitigating potential security breaches.

Features
Real-Time Face Recognition: Utilizes the LBPH algorithm for swift and accurate facial recognition.

Unauthorized Access Alerts: Immediately notifies security personnel when an unrecognized face is detected.

Database Management: Efficient storage and retrieval of authorized personnel images.

IP Camera Integration: Seamless integration with IP cameras for live monitoring.

User-Friendly Interface: Intuitive interface for registering and managing authorized users.

Technologies Used
Python: Core programming language for the system.

OpenCV: Library used for computer vision tasks, including face detection and recognition.

LBPH Algorithm: Employed for its effectiveness in facial recognition tasks.

IP Cameras: Hardware component for capturing real-time video feeds.

Installation
Clone the Repository:

bash
Copy
Edit
git clone https://github.com/Rishikiran98/DynamicHumanAuth.git
Navigate to the Project Directory:

bash
Copy
Edit
cd DynamicHumanAuth
Install Required Dependencies:

Ensure you have Python installed. Then, install the necessary packages:

bash
Copy
Edit
pip install -r requirements.txt
Usage
Register Authorized Personnel:

Run the Register.py script to capture and store images of authorized individuals.

Configure Camera Settings:

Use the Camera_select.py script to set up and test IP camera configurations.

Start the Home Page Interface:

Launch the Home_page.py script to access the main interface.

Monitor and Authenticate:

The system will continuously monitor the video feed. When an unrecognized face is detected, an alert will be triggered to notify security personnel.

Contributing
We welcome contributions to enhance DynamicHumanAuth. To contribute:

Fork the repository.

Create a new branch (git checkout -b feature/YourFeature).

Commit your changes (git commit -m 'Add some feature').

Push to the branch (git push origin feature/YourFeature).

Open a pull request detailing your changes.

License
This project is licensed under the MIT License. See the LICENSE file for more details.
