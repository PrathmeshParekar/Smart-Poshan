# Smart-Poshan

SmartPoshan is an advanced web application designed to revolutionize nutritional monitoring and attendance tracking within educational institutions. Leveraging state-of-the-art technologies, the system integrates sophisticated image processing techniques and user-centric interfaces to streamline administrative processes and enhance student welfare.

## Features

- **Comprehensive Data Management:** Efficiently track student attendance, manage meal records, and store detailed nutritional information.
- **Intuitive User Interface:** Developed with Flask, the UI offers a seamless and responsive experience for both School Users and Admins.
- **Deep Learning Integration:** Utilizes Convolutional Neural Networks (CNN) for precise image processing and nutritional analysis of meal images.
- **Secure Authentication:** Incorporates SHA-256 key encryption to ensure data security and integrity.
- **Dynamic Report Generation:** Generate detailed, interactive reports on student attendance, meal nutrition, and overall system performance.

## Scope

- **Educational Institutions:** Tailored for schools and educational facilities to optimize administrative management.
- **Cross-Platform Accessibility:** Accessible from various devices including desktops, facilitating on-the-go usage.
- **Scalable Architecture:** Designed to handle extensive data volumes and accommodate future expansions or enhancements.
- **Seamless Integration:** Potential for integration with existing school management systems or databases to ensure cohesive operations.

## Motivation

- **Enhanced Operational Efficiency:** Streamline administrative processes to save time and resources for educational institutions.
- **Improved Student Welfare:** Monitor student attendance and nutritional intake more effectively to ensure their overall well-being.
- **Advanced Technology Utilization:** Leverage cutting-edge technology like deep learning and secure data encryption to enhance system capabilities and performance.
- **Responsive to User Needs:** Address the evolving needs of educators and administrators for a modern, user-centric school management solution.



## How to Run the Project

### Prerequisites

Before you begin, ensure you have the following installed:

- Python 3.10
- pip (Python package installer)
- MongoDB Compass
- Flask
- vcredist_X64
- Any additional dependencies listed in the `requirements.txt` file

### Installation

1. **Clone the Repository:**
- git clone https://github.com/PrathmeshParekar/Smart-Poshan.git
- cd your-repository-name
2. **Create a Virtual Environment:**
- python -m venv venv
4. **Activate the Virtual Environment:**
- **On Windows**
- .\venv\Scripts\activate
- **On macOS/Linux**
- source venv/bin/activate
5. **Install Dependencies:**
- pip install -r requirements.txt

   
### Database Setup
**Start MongoDB Compass:**

-Ensure MongoDB Compass is running on your system. If MongoDB Compass is not installed, refer to the official MongoDB Compass installation guide.

**Create Necessary Collections:**

Use MongoDB tools or a client like MongoDB Compass to create the necessary collections for storing student records, meal images, and other relevant data.

### Running the Application
**Set Environment Variables:**

Set up any necessary environment variables, such as database connection strings or configuration settings.

**Start the Flask Application:**
  flask run


## Dataset

The performance analysis dataset comprises 900 images, with 80% used for training and 20% for validation. It includes three classes: chana bhaji, lapsi, and khichidi.

## Implementation

The system is implemented as a web application with the following capabilities:

- **Student Records Management:** Add, update, and view student details.
- **Meal Image Upload:** Upload meal images and analyze nutritional content.
- **Attendance Tracking:** Use QR codes and photographic evidence to track student attendance.
- **Admin Dashboard:** Manage user accounts, generate reports, and oversee system operations.

## Usage

1. **Login:**
   - Schools and admins can log in to access different features.
2. **Manage Student Records:**
   - Add or update student information.
3. **Upload Meal Images:**
   - Upload images to analyze nutritional content.
4. **Track Attendance:**
   - Use QR codes and photos to record attendance.
5. **Generate Reports:**
   - Download detailed reports on attendance and nutrition.

## Screenshots





 

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## Contact

For more information, please contact Prathamesh Parekar at parekarprathamesh06@gmail.com .
