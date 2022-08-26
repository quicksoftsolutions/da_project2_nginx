INTRODUCTION 

This Project is to establish the installation of the LEMP STACK IMPLEMENTATION

1. This first action is setting UP an EC2 instant on AWS 
![image](https://user-images.githubusercontent.com/41007763/186931584-0c900303-772c-4dae-83a8-2564c477207f.png)


1. I also was able to setup the NGINX Server using the **sudo apt install nginx** command and using **sudo systemctl status nginx** to check status and using to start it whenenver am starting the machine again **sudo systemctl start nginx**
 ![image](https://user-images.githubusercontent.com/41007763/186931980-10cda298-88b3-4ae2-a604-31d60430be9d.png)
 ![image](https://user-images.githubusercontent.com/41007763/186937855-54e52186-6c39-44f2-8915-f4152ab3f6ad.png)


1. Ii install the mysql Database with the command **sudo apt install mysql-server** 
  ![image](https://user-images.githubusercontent.com/41007763/186932895-1b91004a-8539-407d-8f0e-acc02a5f5efd.png)


1. I install PHP  **sudo apt install php-fpm php-mysql** I assign ownership of the directory with the $USER environment variable. 
![image](https://user-images.githubusercontent.com/41007763/186933525-1165537d-0463-4e34-87f0-efdc46ff6f64.png)

1. using **sudo ln -s /etc/nginx/sites-available/projectLEMP /etc/nginx/sites-enabled** I was able to link the Nginx to the PHP and displayed the message below
![image](https://user-images.githubusercontent.com/41007763/186934936-e44e3dc5-cbac-45fe-a91f-fd29734de08e.png)

1. I tested PHP is working with the NGINX by loading **http://3.8.207.194/info.php** then I replace the page info.php file with a customised htnl website and css file 
![image](https://user-images.githubusercontent.com/41007763/186939463-ca7af910-5b13-45ec-94c4-e19e6d4bdf29.png)

1.Using sudo mysql I was able to navigate in the Database display database with **mysql> SHOW DATABASES** I selected the Database to Use Using **USE DATABASENAME** 

I did not take much screenshort here as it my convenient domain, I was able to insert data in the TAble Authors, in the Database **example_database** and display them as shown below
![image](https://user-images.githubusercontent.com/41007763/186940575-ae06dd85-c0d9-42c8-8ab6-41ea718aa5a2.png)



