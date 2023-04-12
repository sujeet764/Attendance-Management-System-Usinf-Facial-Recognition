# Attendance-Management-System-Using-Facial-Recognition
In whole model there are two main modules 1. Attendance 2. Login
![image](https://user-images.githubusercontent.com/60980975/231382434-ce04e6b0-8469-4194-a691-29ecc8718f49.png)

1.	Attendance
This module avails the feature to mark the attendance of the students just by providing unique student ID/Facial Recognition.
![image](https://user-images.githubusercontent.com/60980975/231382570-018d539b-4c93-417f-8af5-e86e74bd8695.png)
How it works ?
As we open the attendance we will get two options 1.Manual 2.Facial Recognition. In which if we will press the manual button provided interface will appear. 
![image](https://user-images.githubusercontent.com/60980975/231382615-79cd9a6b-3fc7-4a95-b0e2-b48afd11edc1.png)
Here you only need to provide the ID and press the submit button it will extract your name and class from the database if available else it will throw an error that record not found.
![image](https://user-images.githubusercontent.com/60980975/231382649-cf6879ca-8263-48ab-87b3-84b91e2b54f0.png)
if your details will find in the database it will extract details and display in the box along with the confirmation message, as you will press yes your attendance will be marked. And we can see the attendance in the database as a image below.
![image](https://user-images.githubusercontent.com/60980975/231382715-27ff73d5-8990-44b6-bd46-fa5f3dbcc0db.png)

Facial Recognition 
In the application you will also able to find the option of facial recognition where you can mark the attendance just by looking into the camera.
How it works?
When we press the button, it accesses the pc camera and you will only have to look for some couple of seconds and it will take your image and recognize it and it will return an ID and based on that ID we will extract the record from the main student database and it will get stored in the attendance database along with timestamp. If image will find it will return a notification that attendance marked else it will throw an error that record not found. 
![image](https://user-images.githubusercontent.com/60980975/231382802-7d82ef63-4f84-4d6c-9199-208ed64fbbf1.png)
Note :- for documentation purpose I re-trained the model without this person’s image .


LOGIN:
this module is for admin where admin have the rights to manipulate the database means, they can add, remove, update the records as per requirement.
![image](https://user-images.githubusercontent.com/60980975/231382897-c7888e92-d73f-4e1c-a683-13f2397ef11d.png)

Here admin will have to provide correct username and password to access the admin options. If login details will be right they will redirect to next page:

Here admin will have to provide correct username and password to access the admin options. If login details will be right they will redirect to next page:

Here admin will get three option:
1.	New :- here new records can be added to the database. They only have to provide the following details.
![image](https://user-images.githubusercontent.com/60980975/231383073-a7258e31-a4f5-48bf-b327-a209263bdd05.png)
Once the details are filled just press the submit button and record will be stored in the database.
2.	Show/update :- here admin can view the records as well update if necessary. They just have to pass the student ID to fetch the record. If record will be found, it will display and you can change the value and just press the update button it will be updated in database, if record not found it will throw an error.
![image](https://user-images.githubusercontent.com/60980975/231383130-21cf6aae-f535-4682-a1a3-445129f8b63a.png)

3.	Delete :- this option allows admin to delete any records from the database. They just have to provide the student ID and if record found it will ask for confirmation for delete. If not found it will produce an error.
![image](https://user-images.githubusercontent.com/60980975/231383186-924f16b7-a1f8-4172-8507-0eab63bd1728.png)









