# Projects

#My First Project
#Medicure dbms

Co-authored-by: Darkpanther253 <karthik.rajeev253@gmail.com>

Medicure Database Management system
Through this project we intend to make storage of patient and doctor details easy and efficient—a cornerstone for the successful operation of any hospital.
The MDBM system comes with a plethora of features that takes care of the needs of both the patients and the hospital authorities.  It manages everyday processes that take place in a hospital by providing  simple presets that are easy to use thus reducing the work of healthcare professionals. This enables them to give their best in treating their patients. The patient’s relatives can easily view the details of the patient through the USER mode which is particularly helpful if the patients are senior citizens and relatives are out of town. The MYSQL Direct Feature allows the user to run commands that may not be included in the presets thus providing greater flexibility to the system .Data security is given high priority. Admin options are password protected and the patients/relatives of patient have limited access to data. The  Doctor table and patient table are linked by foreign key constraint thereby reducing data inconsistency .Each Doctor/patient is linked to their respective record via a unique id.
 
ADVANTAGES
• It is fast, efficient and reliable
• Avoids data redundancy and inconsistency
• Very user-friendly
• Easy accessibility of data
• Provides more security and integrity to data

Requirements

This project needs the following to run properly:

Software requirements

-Python 3 or above
-MySql
-MySql connectors

Additional Points

-replace the password field in the mysql.connector.connect line.

-Some of the code might have to be commented out 
eg: The drop database line must be commented out unless there is a need to reset the database
The create databases and create tables command must be commented out after set up

-The doctor table must be populated before you can work on the patient table. This is because of the foreign key constraint between the two tables.This has been done to ensure data integrity.

-The project would be of more value if the USER mode could be connected to the hospitals website for easy access.
