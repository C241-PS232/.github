
# FruitLens

## Team Information
- **Team ID:** C241-PS232
- **Team Members:**
  - **ML**: Indira Elza Yunita (M006D4KX2190), Universitas Brawijaya - [Active]
  - **ML**: Jauza Zahraza (M006D4KX2438), Universitas Brawijaya - [Active]
  - **ML**: Irnada Al Anati (M006D4KX2180), Universitas Brawijaya - [Active]
  - **CC**: Abiyyu Dhiyaul Haq (C194D4KY0748), Universitas Budi Luhur - [Active]
  - **CC**: Kelvin Pahotton Simamora (C194D4KY0685), Universitas Budi Luhur - [Active]
  - **MD**: Muhammad Arafie Setiawan (A194D4KY3960), Universitas Budi Luhur - [Active]
  - **MD**: Dimas Nyondro Radityo (A009D4KY3494), Universitas Gunadarma - [Active]

## Project Information
- **Title:** FruitLens
- **Theme:** Empowering Minds: A holistic approach to education and personal development

## Executive Summary
“FruitLens” is an innovative mobile application designed to enhance the educational experience by providing users with a comprehensive platform for identifying and learning about fruits. Users can take pictures of fruits, and the system uses advanced image recognition technology to identify them. This application also provides detailed information about each fruit, thereby increasing users' understanding of fruits more deeply. By combining education and technology, this application makes it easier to recognize fruits and fosters curiosity and knowledge in users of all ages.

## Project Genesis
The idea for FruitLens arose from recognizing a gap in how individuals, especially students, interact and learn about nature. Our team aimed to create an app that makes learning about fruits interesting and informative by leveraging image recognition to identify fruits and provide information. This aligns with the current trend of using AI and machine learning to enhance educational tools.

## Project Scope & Deliverables

### Scope

- **Machine Learning Team:**
  - Develop a machine learning model to identify fruits from images using a pre-trained convolutional neural network (CNN) with transfer learning.

- **Cloud Computing Team:**
  - Design and implement the cloud infrastructure using Google Cloud Platform (GCP).
  - Set up the backend framework using Node.js and Express to handle API requests.
  - Utilize Firestore for storing prediction results and historical data.
  - Configure API Gateway to manage and secure API endpoints.
  - Develop backend services to process image uploads, interact with the ML model, and return predictions.

- **Mobile Development Team:**
  - Implement features to allow users to upload images of fruits for identification.
  - Develop a quiz game feature to test users' knowledge of fruits and their benefits.
  - Create a feature to keep a history of fruit recognition results.

### Deliverables

- **Machine Learning:**
  - A machine learning model trained to recognize a wide variety of fruits.
  
- **Cloud Computing:**
  - Detailed documentation of the cloud infrastructure, including architecture diagrams and configuration settings.
  - A fully operational backend framework.
  - A comprehensive database containing detailed information about various fruits.
  - Configured API Gateway for secure and efficient routing of API requests.

- **Mobile Development:**
  - An Android application capable of identifying fruit objects using AI technology.
  - A history feature for the results of fruit object recognition.
  - A quiz game feature to test users' knowledge of fruits and their benefits.

## Project Schedule

### General
- **Progress Report:** May 14 - May 31
- **Final Preparation and Coordination:** June 1 - June 20

### Machine Learning
- **Collecting Data:** May 14 - May 17
- **Data Pre-Processing:** May 18 - May 20
- **Create Data Model:** May 21 - May 23
- **Testing Data Model:** May 24 - May 26
- **Data Model Adjustment to Platform:** May 27 - May 30

### Cloud Computing
- **Cloud Environment and Backend Framework Setup:** May 14 - May 17
- **Database Setup and API Gateway Configuration:** May 18 - May 20
- **Backend Development:** May 21 - May 23
- **Performance Monitoring, Testing, and Optimization:** May 24 - May 26

### Mobile Development
- **Development of User Interface (UI) and Basic Functionality:** May 14 - May 17
- **Development of Connection to ML Server:** May 18 - May 20
- **Testing, Optimization, and Refinement of UI/UX:** May 21 - May 23

## Task Assignment

### Machine Learning
- **Create Data Model:** Indira Elza Yunita
- **Testing Data Model:** Irnada Al Anati
- **Data Model Adjustment to Platform:** Jauza Zahraza

### Cloud Computing
- **Cloud Environment and Backend Framework Setup:** Abiyyu Dhiyaul Haq
- **Database Setup and API Gateway Configuration:** Kelvin Pahotton Simamora
- **Backend Development:** Abiyyu Dhiyaul Haq
- **Performance Monitoring, Testing, and Optimization:** Kelvin Pahotton Simamora

### Mobile Development
- **Development of Connection to ML Server and UI/Basic Functionality:** Muhammad Arafie Setiawan
- **Testing, Optimization, and Refinement of UI/UX:** Dimas Nyondro Radityo

## Tools, IDE, Library, and Resources

### Tools
- **Git:** Distributed version control system.
- **Postman:** Tool for testing and interacting with APIs.

### IDE
- **Visual Studio Code:** Source code editor supporting JavaScript and Python.
- **Android Studio:** Official IDE for Android application development.

### Library
- **TensorFlow:** Library for numerical computation and machine learning.
- **Matplotlib:** Library for creating visualizations in Python.
- **Scikit-Learn:** Machine learning library for Python.
- **Node.js:** Back-end JavaScript runtime environment.
- **Express:** Web application framework for Node.js.
- **JWT & OAuth:** Technologies for securing communications.
- **CameraX:** Library for easing camera app development.
- **DataStore:** Data storage solution.
- **Room:** Persistence library for SQLite.
- **SQLite:** Relational database management system.
- **Retrofit:** Type-safe REST client for Android and Java.

### Resources
- **Google Cloud Platform:** Suite of cloud computing services.

## Machine Learning Part
Our app leverages machine learning for fruit recognition. Fruits are classified using the phone's camera or uploaded from the gallery. We use a pre-trained CNN model built with transfer learning. Another feature is a quiz about fruit, classified using a supervised learning model with user questionnaire responses as input.

## Mobile Development Part
We will create an Android application using Android Studio and Kotlin. The app will enable users, especially children, to scan fruits as educational material, providing information and benefits of the fruits. It also includes a quiz feature to test users' knowledge.

## Cloud/Web/Frontend/Backend Part
Google Cloud will host the backend, ensuring scalability. Our backend, developed in JavaScript using Expressjs, will manage a secure, authenticated API, thoroughly documented, and backed up against third-party API instability.

## Potential Risks
## Remarks
This project aims to increase children's knowledge about fruits and their benefits using AI technology, fostering early education and awareness. The quiz feature makes learning fun and engaging, contributing to health improvement and educational initiatives.

