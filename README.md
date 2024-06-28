# HNG-task1
This is the beginning of HNG Internship tasks.
This first task is to write a simple website in html, incorporating css and js. Then deploy the webpage on an Nginx web server and host it on AWS EC2 instance. 
The steps I used to achieve the tasks are as follows - 
 - Prepared my index.html, index.css & index.js files. they are available in this git repository
 - Spin up an AWS EC2 server. I used Ubuntu 22.04, t2-micro (free tier config). Under the security group settings, ensure to allow HTTP port 80 in addition to the ssh port 22 allowed by default.
 - set up nginx web server on the Ubuntu machine by running the following commands
   ```bash
   $ sudo apt update
   $sudo apt install nginx -y
   
  - Verify the nginx is properly set up by viewing the default page on the browser using the public ip address of my EC2 instance
  - I Cloned the git repository containing my website files onto the server
  - I copied the files to the /var/www/html directory
  - Voila! My simple website is available and displayed in my browser! 
