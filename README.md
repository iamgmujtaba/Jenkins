Integrate Machine Learning Models using Jenkins and Docker

# Jenkins Installation on Ubuntu

```shell
$ wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -
$ sudo sh -c 'echo deb https://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'
$ sudo apt-get install jenkins
$ sudo systemctl daemon-reload
$ sudo systemctl start jenkins
$ sudo systemctl status jenkins
$ sudo ufw allow 8080
$ sudo ufw status
```

