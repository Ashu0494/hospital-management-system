# Hospital Management System
This is an Hospital Management System Project in java made by our group "GUVI GEEKS" in the 2nd semester of our Btech journey.
This system has a home or login page from where the administrator can login. On logging in the user can add details of patients and doctors.
This Hospital Management System is a comprehensive desktop application developed in Java using Swing for the graphical user interface, and JDBC (Java Database Connectivity) for interaction with a MySQL database. It is designed to serve as a full-fledged hospital management solution, integrating essential features required to manage patients, doctors, appointments, billing, and other administrative tasks efficiently.

The application is modular, easy to scale, and follows standard coding practices to maintain readability and functionality. It is built to demonstrate an end-to-end software development cycle including GUI design, backend logic, and database connectivity.

🚀 Features
👩‍⚕️ Patient Management (Add, Update, View, Delete patient records)

🧑‍⚕️ Doctor Management (Specialization, Schedule, Contact Info)

📅 Appointment Scheduling (Assign patients to doctors with date/time)

💊 Medicine & Prescription Tracking

🧾 Billing System (Generate and print invoices)

🔒 Login Authentication (Admin/User roles)

📂 Data Storage using MySQL Database

📈 Real-Time Data Updates with JDBC

🖥️ User-Friendly GUI using Java Swing

⚙️ Technologies Used:-
Tech Stack	Purpose,
Java (JDK 8+)	Core programming language,
Swing (javax.swing)	GUI Framework for desktop UI,
JDBC	Database connectivity layer,
MySQL	Backend RDBMS for data storage,
XAMPP / WAMP (optional)	Local server setup for MySQL,
Eclipse / IntelliJ IDEA	Recommended IDE for development.




## Screenshot
###### Login Screen
![alt Login Screen](https://github.com/vivekcsiam/Hospital-Management-System/raw/master/Images/screenshots/Login.png "Login Screen")
>>>> It is an interface which helps us in logging in...
###### Patient Screen
![alt Patient Screen](https://github.com/vivekcsiam/Hospital-Management-System/raw/master/Images/screenshots/Patient.png "Patient Screen")
>>>> It helps in filling the patient details...
###### BedRoom Availability
![BedRoom Availabilty](https://github.com/user-attachments/assets/ec742076-10ab-46e1-889e-744ef2919d85)
>>>> This interface shows the availabilty of the rooms in hospital for patient...
###### Department Info
![Department Info](https://github.com/user-attachments/assets/7fedbc4f-4aa8-4c5e-98bd-e3ff21c55ce8)
>>>> It is giving the info about all the departments of hospital... 
###### CheckOut Screen
![CheckOut Screen](https://github.com/user-attachments/assets/ef17a696-cdba-4181-a363-56e66fe4f344)
>>>> It is an Screen which helps in saving the checking out details from hospital...
###### Update Patient Info
![Update Pateint Info](https://github.com/user-attachments/assets/7e7c53bb-cd88-473e-bb73-c9eb1c1562a8)
>>>> This interface helps in updating the patient info...




## Installation
1. Clone or download zip from github repository
2. Install [MySQL Connector/J](https://dev.mysql.com/downloads/connector/j/3.1.html), on Ubuntu/linux MySQL connector can be installed by `apt-get install libmysql-java` and then add the path of `.jar` file to `CLASSPATH`. On Ubuntu/linux the location of `.jar` file can be added to `CLASSPATH` by adding the following line `export CLASSPATH=".:/usr/share/java/mysql.jar"` to `~/.bashrc` file followed by `source ~/.bashrc`
3. Create database named `hms` and table `users` with columns `username`, `password`, table `doctors` with columns `DocName`, `Specialisation`, `Address`, `Pnumber`, table `Patients` with columns `Pname`, `Address`, `Pnumber`, `Age`, `Sex`, `Illness` and table `contactus` with columns `email`, `comments`
4. Navigate to the project folder and run `javac HomePage.java` to compile and `java HomePage` to run the program

## License
This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

###### P.S This project is simply a proof of concept done while i was still in school/college. This project is not to be taken seriously and is not production ready.
