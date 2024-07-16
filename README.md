# Movement_Control_Panel
A website interface has been created to control the robot's movement in four directions (forward, backward, right, left) and stop, and link it to a database for storing these commands.
![image](https://github.com/user-attachments/assets/86d4da67-c6d3-4cdc-9426-3d6ab99717ab)

## Tools Used:

## Task execution steps
1. I downloaded XAMPP from the following link: [Download XAMPP](https://www.apachefriends.org/download.html).

2. I started the XAMPP server by clicking "Start".
![image](https://github.com/user-attachments/assets/ce236b79-ea60-49c0-afa7-86669b9e71bc)

3. I opened localhost/phpadmin and created a database"robot" with a table"robotmovement" inside, as shown in the following figure.
![image](https://github.com/user-attachments/assets/4e5de6f4-f0d2-4c9f-9642-214e6e04f4de)

4. I added two columns (id, direction) in the table to store direction values.
![image](https://github.com/user-attachments/assets/041a58f5-7726-44ac-9657-ff87e0d2a1b3)

5. I created a folder "robot" to connect to the database, as illustrated in the figure.
![image](https://github.com/user-attachments/assets/718b3d76-2bd4-445c-8bb8-02a3e28b55d4)

6. I inserted the files "robot.html", "index.php", and "styControl.css" into the "robot" folder.
- index.php
![image](https://github.com/user-attachments/assets/94f1ff28-f866-4390-946b-3994da62bb66)
- robot.html
![image](https://github.com/user-attachments/assets/070f67df-d724-4af0-9ceb-96889011daaa)
- styControl.css 
![image](https://github.com/user-attachments/assets/ebe1e16b-410c-455b-b0fe-f3dcbe47bb2b)

Thus, I successfully created the web page and connected it to the database.✨

After that, I opened the robot.html file, as depicted in the figure.
After clicking the "stop" , the press was successfully stored in the database.

![image](https://github.com/user-attachments/assets/92dcf8e2-39e4-4868-a6e4-5f6c9ae8d894)
![image](https://github.com/user-attachments/assets/638112fc-8773-45a2-ada1-5c86d20a1ffe)

------------------------------------------------------------------------
**Test for all directions:**
![image](https://github.com/user-attachments/assets/9c619198-6643-4903-a01b-ab7c861cf198)
![image](https://github.com/user-attachments/assets/7a301628-3d62-4c1d-a16c-d8245dc4f092)
