# Hospital Management System



## Description-
   In this Project we aim to solve the traditional issues of hospital management. The existing system provided paper based solution for keeping OPD records of patients and hospital staff, but it gives overload to Doctor, Receptionist and Administrator.  The main issues were inappropriate data keeping, time wastage in storage, retrieval also patients were unable to understand the prescription etc. These issues are solved by providing a separate user account for doctors and other staff. Keeping each patient’s data separate and track previous visits in a single click. 
   
   This project uses MYSQL as backend and is developed in Java so it provides features such as platform independence, high performance and security. It is a web application which mainly uses SpringMVC and Hibernate frameworks. 
   
   It provides some enhanced features such as: an easy interface to add, remove employees as well as it provides PDF of prescription. Thus, reducing need to manually write  and  sign  by doctor.  <br>


## Technologies Used-

![techStack](https://github.com/rid17pawar/HospitalManagement/assets/47048717/0b9e95e2-b3f0-41bb-b76f-75c275273389)

### 1. Front end Technologies:
  - HTML
  - CSS
  - Bootstrap
  - JavaScript
  
### 2. Back end Technologies:
  - SpringMVC 
  - Hibernate
  
### 3. Database:
  - MySQL
  
### 4. Project management tool:
  - Maven
  
### 5. Webserver:
  - Apache Tomcat



## Features-
  1. Doctor module:
      - Seperate accounts for doctors
      - Each patients previous visits history is easily to access.
      - Doctor can generate prescription and it will be automatically sent to receptionist.
      - Doctor can remove patient from OPD queue.
      
  2. Receptionist module:
      - Register/add new patient's info.
      - Modify patients personal details
      - Search existing patient by name/ mobile no./ PID/ aadhar no.
      - Remove patient from OPD queue.
      - Take print of prescriptions.
      
  3. Administrator module:
      - Add new employee for following roles,
                      i) Doctor
                     ii) Receptionist
                    iii) Admin (another one)
      - Remove/edit existing employee. 
      - Displays currently active employees in system.
      
  4. Password Encryption:
      - *_Bcrypt Encoding_* is used for password encryption. Bcrypt is a password hashing function designed by Niels Provos and David Mazières. It is based on the Blowfish cipher. Bcrypt uses adaptive hash algorithm to store password. BCrypt internally generates a random salt while encoding passwords and hence it is obvious to get different encoded results for the same string. But one common thing is that everytime it generates a String of length 60.


## Snapshots-

1. Homepage

![homepg](https://github.com/rid17pawar/HospitalManagement/assets/47048717/ed1a7bcd-a327-4703-8954-f647d405272a)

2. Login page

![loginpg](https://github.com/rid17pawar/HospitalManagement/assets/47048717/87120956-e508-4d5b-b48f-c823f5e29851)

3. Administrator Dashboard

![adminDashboard](https://github.com/rid17pawar/HospitalManagement/assets/47048717/5223bfda-cd29-40f8-aa5b-988972d529fe)

![adminAll](https://github.com/rid17pawar/HospitalManagement/assets/47048717/88587d2b-515a-4912-8b76-469b68cb167f)

4. Doctor Dashboard

![doctorObservation](https://github.com/rid17pawar/HospitalManagement/assets/47048717/00dfe2c3-8802-48e9-8de7-daa71a1a89b4)

![doctorPrescription](https://github.com/rid17pawar/HospitalManagement/assets/47048717/1ff1d095-3ed9-434d-8ed5-5d9228d489d9)

5. Receptionist Dashboard

![receptionistSearch](https://github.com/rid17pawar/HospitalManagement/assets/47048717/dcbce603-9d5a-47b7-9138-1221458f323e)

![receptionistAdd](https://github.com/rid17pawar/HospitalManagement/assets/47048717/5f987507-0510-4edc-adc2-545f69123291)


### Thank You !
