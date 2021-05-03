#Login

This service is responsible for the login in the portal.

This code is written in Go language , Hence need to install 'go' in the system.

# apt update
# wget -c https://dl.google.com/go/go1.14.2.linux-amd64.tar.gz -O - | sudo tar -xz -C /usr/local
Adjusting the Path Variable

 # export PATH=$PATH:/usr/local/go/bin
 # source ~/.profile
 # go version
Getting Started with Go

 # mkdir /go
 # cd /go 
 # git clone https://github.com/zelar-soft-todoapp/login.git
 # cd  login
 # export GOPATH=/go
 # go get
 # go build
 # ./login
Now, lets set up the service with systemctl.

 # vim /etc/systemd/system/login.service
 # systemctl daemon-reload
 # systemctl start login.service
 # systemctl enable login.service
