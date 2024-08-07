# Movement_Control_Panel
A website interface has been created to control the robot's movement in four directions (Forward, Backward, Right, Left) and Stop, and link it to a database for storing these commands.
![image](https://github.com/user-attachments/assets/86d4da67-c6d3-4cdc-9426-3d6ab99717ab)

## Tools Used:
<img src="https://www.svgrepo.com/show/354575/xampp.svg" alt="Xampp" width="100" height="100" style="max-width: 100%;" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/php/php-original.svg" alt="php" width="100" height="100" style="max-width: 100%;" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original-wordmark.svg" alt="mySQL" width="100" height="100" style="max-width: 100%;" /><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" alt="HTML" width="100" height="100" style="max-width: 100%;" /><img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" alt="CSS" width="100" height="100" style="max-width: 100%;" />

## Task execution steps
1. I downloaded XAMPP from the following link: [Download XAMPP](https://www.apachefriends.org/download.html).

2. I started the XAMPP server by click "Start".
![image](https://github.com/user-attachments/assets/ce236b79-ea60-49c0-afa7-86669b9e71bc)

3. I opened [localhost/phpadmin](http://localhost/phpmyadmin/) and created a database"robot" with a table"robotmovement" inside, as shown in the following image.
![image](https://github.com/user-attachments/assets/4e5de6f4-f0d2-4c9f-9642-214e6e04f4de)

4. I added two columns (id, direction) in the table to store direction values.
![image](https://github.com/user-attachments/assets/041a58f5-7726-44ac-9657-ff87e0d2a1b3)

5. I created a folder "robot" to connect to the database, as illustrated in the image.
![image](https://github.com/user-attachments/assets/718b3d76-2bd4-445c-8bb8-02a3e28b55d4)

6. I inserted the files "robot.html", "index.php", and "styControl.css" into the "robot" folder.
- index.php
![image](https://github.com/user-attachments/assets/94f1ff28-f866-4390-946b-3994da62bb66)
- robot.html
![image](https://github.com/user-attachments/assets/070f67df-d724-4af0-9ceb-96889011daaa)
- styControl.css 
![image](https://github.com/user-attachments/assets/ebe1e16b-410c-455b-b0fe-f3dcbe47bb2b)

Thus, I successfully created the webpage and connected it to the database. ✨

After that, I opened the robot.html file and clicked on "stop". The press was successfully stored in the database, as depicted in the image.

![image](https://github.com/user-attachments/assets/92dcf8e2-39e4-4868-a6e4-5f6c9ae8d894)
![image](https://github.com/user-attachments/assets/638112fc-8773-45a2-ada1-5c86d20a1ffe)

------------------------------------------------------------------------
### Test for all directions
![image](https://github.com/user-attachments/assets/9c619198-6643-4903-a01b-ab7c861cf198)
![image](https://github.com/user-attachments/assets/b2e7aa5e-53ed-4d46-811d-1765435e9118)
