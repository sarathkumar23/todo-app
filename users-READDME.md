#users

Todo-Users

Users service is responsible for finding the users by username and password

       # apt update
       # apt-get install openjdk-8-jdk
       # java -version
Now go and fetch git code

      # git clone https://github.com/zelar-soft-todoapp/users.git
      # cd users
      # mvn clean package
      # cd target
      # mv users-api-0.0.1.jar users,jar
      # mv users,jar users.jar
      # java -jar target/users.jar
Start service now

     # vim /etc/systemd/system/users.service
     # systemctl daemon-reload
     # systemctl start users.service
     # systemctl enable users.service
