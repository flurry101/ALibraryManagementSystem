<!DOCTYPE html>
# LDBMS
A Mini-School Group Project

# **Project on Library Management System**
A library management system using Python-SQL connectivity.

<i> Funnily enough, we didn't realize that this was a small implementation of CRUD operations!</i>

# **INTRODUCTION**
	
A library management system is software that is designed to manage all the functions of a library. It helps maintain the details of all books, employees, members and the books borrowed by the members.  
A well-developed database management system makes things very informative and simple for both the readers and the librarians.
A database which gives an in-depth information books borrowed by each of the readers , and helps to learn their interests. This will also enable the librarians to track the books efficiently, and prevent any loss or damage of books. 

### **SOFTWARE REQUIREMENTS:**

•	Windows OS/Mac OS <br>
•	Python 3.4 or higher <br>
•	MySQL 8.0 or higher <br>

### Default credentials:
Username: `root` <br>
Password: `pswd@123` (for `mysql`)


### **Modules Used:**

`Tkinter Module`: Tkinter is a Python binding to the Tk GUI toolkit. It is the standard Python interface to the Tk GUI toolkit, and is Python's de facto standard GUI. Tkinter is included with standard Linux, Microsoft Windows and Mac OS X installs of Python. The name Tkinter comes from Tk interface.
<br>
`Date Time Module`:  In python, date and time are not a data type of their own, but a module named `datetime` can be imported to work with date and time. This module supplies classes to work with date and time, these classes provide a number of functions to deal with dates, times and time intervals. 
<br>
`MySQL Connector Module`:  It would be best to remember to: `pip install mysql-connector` before running the program. MySQL Connector enables Python programs to access MySQL databases, using an API that is compliant with the Python Database API Specification v2.0 (PEP 249). It is written in pure Python and does not have any dependencies except for Python Standard Library.
<br>
Here, the MySQL Connector module has been used to allow users to interact with the LDMS database which is present in MySQL through the python front-end. 

# **An Overview of the Project**

![Image](https://github.com/flurry101/A_Library_Management_System/blob/main/images/358847851-b65db1cd-35d5-4a1c-8963-1058a3030095.png)

# Some screenshots...


![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture2.png)
![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture3.png)
![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture4.png)
![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture5.png)
![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture6.png)
![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture8.png)
![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture9.png)
![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture10.png)
![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture11.png)
![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture12.png)
![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture13.png)
![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture14.png)
![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture15.png)
![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture16.png)
![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture17.png)
![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture18.png)
![Image](https://github.com/flurry101/Library-DBMS/blob/main/images/Picture19.png)


# ABOUT THE PROJECT

### **OBJECTIVES OF THE PROJECT**

The objective of this project is to let students apply their programming knowledge into a real - world situation/problem and expose the students how programming skills help in developing a good software.<br>
•	Write programs utilizing modern software tools. <br>
•	Apply object-oriented programming principles effectively when developing small to medium sized projects. <br>
•	Write effective procedural code to solve small to medium sized problems. <br>

### **PROJECT DESCRIPTION:**

The simplicity of creation of a database depends on the type of information stored in it. A library management database is a software system where the management of the entire library is computerized. the application stores reader record and borrowing activities performed in the library such as reader details, books borrowed, issued date, return date, penalty, etc. all are computerized and the management is done without any difficulty with the use of Python modules and directories. <br>

The system maintains the different location that is available and registered to a central database which leads easy accessibility and consistency.
Each accommodation available units and all the unit facilities are available at the click of a mouse
The registration for a user is done online making it more efficient and convenient for the registration process.
The readers are provided with accurate details regarding their borrowing history.
This application allows the library management the ability to operate the entire system from a single online interface, giving them more power and flexibility.
Maintain a steady influx of visitors and guests throughout the year, as well as top promote the library’s extensive rang e of services.
Better safety and security in maintaining data and personal information using automation

### **SCOPE OF THE PROJECT**

As the technology and the passion of being well read is increasing day by day, the need for a well-organized, computer-based library management system has become the need of the society. This system helps the admin and the librarian to maintain large data about the users and their daily activity in the library. It should be suitable for maintaining records about the books **borrowed, issued and returned.** 

### **Conventional system**

In the library management system, if we take the conventional system and compare it with the proposed system, it is far behind. Every work in a conventional system is manual and done on paper and the computer systems do not function efficiently, leading to the need of tedious manual work. 
Some major drawbacks of the existing conventional system are as follows:
•	Requires a lot of paperwork and the process takes time. <br>
•	Everything is done on paper, which is highly prone to damage and requires a good amount of security and space to store. <br>
•	Requires buying of goods more frequently as compared to the online system. <br>
•	Likely to have an error. <br>
•	Lack of storage space for handwritten documents. <br>
•	Requires more physical work and manpower. <br>
•	Information is not available globally to both clients and employees hence location restriction. <br>

### **Proposed system**

The system that we shall be proposing in this project not only corrects the drawbacks of the existing system, but it also provides a whole slew of new facilitates and opportunities to take advantage of. Data will be fed to the database from input devices. This will be processed (if needed) and stored in a centralized memory and will be accessible to the library staff. Output will be given by the database itself on demand. The software that will be used for managing the database will be MySQL, and the front end will be designed using Python. 

### **Possible Future Ideas for Upgrades **
• The system would also collect user credentials (username, role (employee / member / non-member) and password) and use them to login into the LDBMS system, which allows them to customize the interface according to their role in the LDBMS, and prevent access of others' data ensuring data privacy at the least. <br>
• The system would introduce a drop-down menu, for genres, book titles, and authors, to make the system more seamless. <br>
• For members and non-members, there would be an interest-based recommendation system, based on the data collected of their book borrowals. For example, if a user#3 has borrowed more books in the genre of "mystery", than in any other system, then, the recommendation system would generate 6-10 books in the same genre.


# *Disclaimer:
**In no manner**, I claim "complete" ownership of this project. 

### *Acknowledgments:*
Apart from the efforts by me and my two other teammates (say, S and H), the success of any project depends largely on the encouragement and guidelines of many others. 
Hence, I take this opportunity to express my gratitude to the people (parents & teachers) who have been instrumental and contributed in bringing this project up to this level, as well as in assisting with the successful completion of this project.


# Lastly...
Thanks for checking out this. 
