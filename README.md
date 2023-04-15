This repository it to store the jenkins pipelines for our CI-CD

sudo dnf install java-11-amazon-corretto -y
https://www.jenkins.io/doc/pipeline/steps/sonar/

SonarQube Scanner for Jenkins

Jenkins – an open source automation server which enables developers around the world to reliably build, test, and deploy their software
## Commands to install tols  
  5  ls
    6  sudo yum update -y
    7  sudo wget -O /etc/yum.repos.d/jenkins.repo \ https://pkg.jenkins.io/redhat-stable/jenkins.repo
    8  sudo dnf install java-11-amazon-corretto -y
    9  sudo wget -O /etc/yum.repos.d/jenkins.repo \ https://pkg.jenkins.io/redhat-stable/jenkins.repo
   10  sudo yum install wget -y
   11  sudo yum update -y
   12  sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo 
   13  sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key 
   14  yum install jenkins -y
   15  sudo wget -O /etc/yum.repos.d/jenkins.repo \ https://pkg.jenkins.io/redhat-stable/jenkins.repo
   16  sudo wget -O /etc/yum.repos.d/jenkins.repo     https://pkg.jenkins.io/redhat-stable/jenkins.repo
   17  sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
   18  sudo yum upgrade
   19  sudo yum install jenkins -y
   20  sudo systemctl enable jenkins
   21  sudo systemctl start jenkins
   22  cd /var/lib/jenkins/secrets/initialAdminPassword
   23  cat /var/lib/jenkins/secrets/initialAdminPassword
   24  history
   25  wget http://downloads.sourceforge.net/project/sonar-pkg/rpm/sonar.repo
   26  sudo mv sonar.repo /etc/yum.repos.d/sonar.repo
   27  sudo yum install sonar
   28  sudo service sonar start
   29  yum install git -y


## Author
Arjun Rayewar