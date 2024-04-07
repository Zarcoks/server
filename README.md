You need first to install docker with command:
- sudo snap install docker

Then, position terminal on ~/, and run the following commands:
- cd server
- mkdir mysqldata
- sudo docker compose up -d

So you can access to MySQL on localhost:6033 and PhpMyAdmin on localhost:8081.

You have also a database created (name: "test"), with username = "Username" and password = "Password". 
Root password is: 0000.
