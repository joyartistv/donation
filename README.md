     Discontinued ⚒️
# Project Red Stream
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=RESPONSIVE+WEBSITE+TEMPLATE;)](https://git.io/typing-svg)

[<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />](https://www.instagram.com/whxitte)

Red Stream is a full stack website project based on online blood donation. This  is a responsive and userfriendly website for making the process of blood donation easy.

including publishing, marketing, or using it in a commercial project, is not permitted without explicit permission.


# How you run this full website on your local computer ?

You can download and use xampp or WampServer to run a web server on your PC. After that start Apache and Mysql services and now you successfully made your PC into a server.<br>
You need to download and extract this project into xampp>htdocs folder.<br>
Now type localhost in your browser and enter and go to phpMyAdmin section. There you need to add a new database named 'redstream_db'. Inside that create 2 tables named 'registered_users' and 'response_back'.<br>
Inside registered_users table create the following columns:-  name, email, phone, password, bloodgroup, gender, birthdate, weight(kg), state, zipcode, district, area, landmark, donations, and received. All of them needs to be VARCHAR datatype except weight(kg) and zipcode is int datatype and birthdate is date datatype.<br>
In response_back table create only one column named email.<br>
And now  you are good to go. If you sucsessfully extracted the project file into htdocs folder of xampp, you can just run localhost/YourFolderName in your browser and you can see the and experience the  project live.<br>
I created the php scripts according to the database, tables and column names i mentioned. If you dont want to use that you can create your own database and columns and you need to change that in the php scripts also.




  ©Sethu

