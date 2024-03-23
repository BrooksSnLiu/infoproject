Open the terminal into the folder you want the project in.
Type git clone https://github.com/NotAtomicBomb/Shoe-Sense and hit enter
Open the shoe_sense folder that is within Shoe-Sense in your ide
In the console/terminal type npm install
Open shoe_sense_api in terminal
Type python -m venv venv
After it is completed create a venv type .\venv\Scripts\activate
Then type pip install -r requirements.txt
After all that open xampp and start the mysql server and apache(You only need apache this first time to set up database)
Once both servers are up click on admin for the mysql server, make sure the port for mysql is 3306
Click on SQL tab and enter CREATE DATABASE shoe_sense CHARACTER SET utf8 (it is important that you spell shoe_sense right our django will not work.)
Now you should be able to run the servers
Apache license is used because it keeps me on guard and requires me to list the modifications. Just the action of that can help me with keeping track and engaging in my work. I've also just never used MIT before.
