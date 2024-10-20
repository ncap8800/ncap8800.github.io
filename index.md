# Nadezda Capkunovic

---

## Summary

Computer engineering student currently in the final year of studies. Experienced with multiple programming languages and frameworks, with a focus on software development and machine learning. Knowledgeable in Java, Python, and SQL, with hands-on experience in building scalable applications and working with big data technologies. Strong problem-solving abilities and a keen interest in developing efficient, high-performance solutions. Additional interests include brain-computer interfaces and digital signal processing. Always eager to learn and continually improve my skillset.


---

## Skills

- **Languages**: 
  - Familiar: C, C++, C#, R
  - Some experience: Python, GNU Octave, JavaScript
  - More experience: Java
- **Frameworks/Libraries**: 
  - Java: Spring Boot, Zuul API Gateway, Eureka, Kryonet, RMI, JDBC, JPA Hibernate, JRaft
  - Python: FastAPI, pandas, SQLAlchemy, numpy, matplotlib, pytorch, tensorflow, OpenCV, Tesseract OCR
  - JavaScript: React, Angular, Node.js, Vue.js
- **Databases**: MySQL, H2, SQLite
- **Tools**: 
  - Familiar: Docker, Hadoop
  - Some experience: Git, Kafka, Zookeeper, Spark, JWT, PsychoPy, OpenViBE, Databricks
  - More experience: Postman, Maven, Jupyter Notebooks
- **Other**: RESTful APIs, Microservices architecture, Distributed systems

---


## Education

**School of Computing**  
Computer Engineering<br>
*2019 - Present*

**Faculty of Organisational Sciences**  
Information Systems and Technologies<br>
*2017 - 2019*

**IX Belgrade Gymnasium Mihailo Petrović Alas**  
Socio-linguistic major<br>
*2013 - 2017*

---

<br><br>

## Relevant projects

### *Robot Vacuum Control System*
- Developed a web application simulating the management of robot vacuums, allowing users to add vacuums, control their states, and schedule operations. 
- Implemented user and vacuum management with permissions for actions such as start, stop, discharge, add, and remove. 
- Enabled scheduling of operations with error tracking for unsuccessful tasks. 
- Integrated a responsive frontend using Angular and a Spring-based backend with a relational database, ensuring robust task scheduling and real-time updates on vacuum statuses.
- Technologies used: Spring, Angular.
- 

### *Distributed Hotel Reservation and Payment System using Java*
- Developed a distributed system for hotel reservations and payments similar to Booking.com or AirBnB.
- Implemented hotel attributes: name, category, location, and distance from the city center.
- Enabled clients to query available hotels based on specified criteria.
- Provided real-time notifications for hotel availability and price changes via a scalable socket server.
- Facilitated hotel reservations using RPC calls using RMI with concurrent task handling.
- Integrated a payment system requiring clients to complete transactions within a defined period.
- Updated hotel records and handled financial transactions, including commission deductions.
- Displayed real-time hotel information and statistics to clients.
- Technologies used: RMI, Executor service, socket server.


### *System for managing class schedules using microservices with Spring Boot in Java*
- Designed and implemented a system for managing class schedules with User, Schedule, and Notification services.
- **User Service**
  - Provided secure access and authorization using JWT.
  - Supported user authentication, token generation, and role assignment.
  - Implemented REST API operations for user login and role management.
- **Schedule Service**
  - Managed schedule viewing and editing.
  - Supported operations for managing teachers, subjects, student groups, classrooms, and terms.
  - Implemented REST API operations for managing schedule-related entities.
- **Notification Service**
  - Sent email notifications for scheduled changes.
  - Implemented REST API operations for managing notifications.
- Integrated services using Netflix Zuul for API gateway and Eureka for service discovery.
- Ensured scalability and reliability through microservices architecture.
- Provided detailed logging and error handling for all services.
- Technologies used: Spring Boot, JWT, Netflix Zuul, Eureka.


### *User Management System using CRUD Operations and JWT Authentication*
- Developed a user management web application using Angular and Spring with MySQL.
- Implemented role-based access control for secure CRUD operations.
- Utilized JWT for user authentication and authorization, ensuring secure API requests.
- Created a user-friendly frontend with Angular, including login, user management, and role assignment features.
- Ensured data security with hashed passwords and unique email enforcement.
- Included real-time updates for user status and permissions.
- Integrated validation for user input to maintain data integrity.
- Provided detailed error handling and user feedback mechanisms.
- Technologies used: Angular, Spring, MySQL, JWT.


### *Online News Publishing and Management Platform*
- Developed an online platform for publishing and reading news using Angular, Spring, and MySQL.
- **Content Management System (CMS)**
  - Implemented JWT-based user authentication and role-based access control.
  - Supported roles: content creator (manage articles) and admin (manage users and articles).
  - Managed entities: User, Category, News Article, Tag, Comment.
- **Public News Reading Platform**
  - Displayed latest and most-read news articles.
  - Enabled browsing by category and searching for articles.
  - Provided full article views with author details, tags, and comments.
  - Allowed users to like/dislike articles and comments.
  - Showed related news based on tags and articles with most reactions.
- Ensured data security with hashed passwords and unique email enforcement.
- Technologies used: Angular, Spring, MySQL, JWT.


### *Theatre Ticket Purchase Application*
- Developed a web application for purchasing theatre tickets using Vue.js for the frontend and Node.js with Express for the backend.
- **User Types**:
  - Guest: Can read publicly available content without logging in.
  - Registered User: Can add and edit their content.
- **Frontend**:
  - Built using Vue.js.
  - Utilized Vue Router for navigation and Vuex for state management.
  - Implemented authentication and routes for login and registration.
  - Used Bootstrap Vue for styling and WebSockets for real-time updates.
- **Backend**:
  - Implemented using Node.js with Express.
  - Provided REST API for CRUD operations on all entities.
  - Validated user inputs and used JWT for authentication.
  - Entities: User, Ticket, Show, Seat, and more.
  - Enabled user roles: Admin (full access) and Moderator (limited access).
  - Used MySQL with Sequelize ORM.
- **Features**:
  - Users can browse shows, select seats, and purchase tickets.
  - Admins can manage users, shows, and tickets.
  - Real-time updates for ticket availability.

## Notable projects using ML technologies

### *Using reinforcement learning for model training within an endless runner video game in Python*
- Developed a basic endless runner video game in Pygame where the controllable character avoided obstacles.
- Utilized reinforcement learning to train the agent using the DQN (Deep Q-Network) algorithm.
- Created the training environment with the Stable Baselines3 framework.
- Sent game commands programmatically using the Pydirectinput library.
- Captured game frames with MSS and processed them using OpenCV.
- Used Tesseract OCR to recognise the "Game Over" screen, which reset the reward total.
- Monitored and logged model training with TensorBoard.

### *Brain MRI Classification using CNNs in Python*
- Implemented binary classification of brain MRIs to determine abnormal or normal status.
- Utilised TensorFlow, NumPy, Matplotlib, and OpenCV (cv2) libraries for image visualisation and data processing.
- Automated dataset creation and preprocessing with tf.keras.utils.image_dataset_from_directory().
- Developed the model with Keras Sequential API, incorporating Conv2D, MaxPooling2D, Flatten, and Dense layers with 'adam' optimizer and binary cross-entropy loss.
- Trained the model, used callbacks for periodic saving, and evaluated performance using accuracy, recall, and precision metrics.
- Tested the model on external data and classified images.
- Saved and loaded the trained model using Keras methods for future use.

### *Stock price prediction using TDNN in Python*
- Implemented a solution for predicting stock prices using artificial neural networks.
- Developed and tested three different TDNN (Time-Delay Neural Network) topologies.
- Employed a multi-layer perceptron (MLP) architecture with logistic sigmoid activation functions.
- Used momentum propagation algorithm for training. 
- Validated each network using test data, calculating mean relative error, and variance.
- Plotted mean square error versus epochs for the best training process of each topology.
- Compared desired and estimated values for specific time domain for the best training process of each topology.
- Analyzed results to determine the most suitable network topology and training configuration for future predictions.

### *Finding correlation between different types of imperfections in the production of tires in Python*
- Developed a Kohonen Self-Organizing Map (SOM) to classify automotive tire samples based on measured properties.
- Designed the network to detect similarities and correlations between variables.
- Trained the SOM and visualized the spatial structure and neuron neighborhoods.
- Classified samples into three distinct classes based on training results.
- Implemented the SOM to identify neuron groups corresponding to each class.
- Determined the class for each sample in the test dataset.

### *Creating systems for processing (near) real-time data using Apache Kafka, Apache Spark, and the Databricks platform*
- Used Apache Kafka in Java to produce and consume data from APIs made using FastAPI in Python.
- Stored the consumed data in a CSV file which was then loaded into a dataframe with specified schema using PySpark.
- Made and displayed correlation matrices for dataframes.
  1. Diabetes analysis
      - Analysed and visualised the data in order to find out the positive diagnosis percentage ratio between two age groups.
      - Analysed and visualised the data in order to determine the percentage in which a person's BMI affects a positive diagnosis.
  2. Rover telemetry analysis
      - Analysed and visualised the columns from correlation matrix in order to determine the source of recorded motion.
      - Used logical regression to determine if it was possible to predict whether there is light based on other factors of the dataset.
  3. EEG data structured streaming
      - Used structured streaming to simulate a real-time stream of EEG data and periodically visualised the data. 


---

## Certifications
- **Python Data Structures & Algorithms** 2024.
- **Passed test in BCI & Neurotechnology SpringSchool** - g.tec, 2023.
- **Certificate of participation for BCI & Neurotechnology SpringSchool** - g.tec, 2023., 2024.

---

## Activities
- Member of club for scientific research
- Member of Game Development club
- Participated in OpenIT18 conference, Data Science track, 2024.
- Participated in BCI & Neurotechnology SpringSchool, 2023. and 2024.
- Participated in OpenIT17 conference, Data Science track, 2023.
- Faculty of Organisational Sciences delegate at GamesCon 2017.

---

<br>

## Interests
- Brain-computer interface
- Automation and robotics
- Sociology/Psychology
- Game design
- Video/Board games
- Signal processing
- Crochet
- Puzzles
