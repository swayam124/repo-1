sudo su -
hostnamectl set-hostname jenkins-server.ex.com
bash

yum update -y
yum install wget -y
from Jenkins on aws documentation
////wget -o
////rpm --import  
yum upgrade
yum install java-21-amazon-corretto -y
yum install Jenkins -y

systemctl enable Jenkins
systemctl start Jenkins

//allow 8080 custom tcp in sec group
//copy pub ip :8080
cat /paste

inside settings of Jenkins, add maven integration and GitHub integration

sudo mount -o remount,size=2G /tmp
df -h
vim /etc/fstab
tmpfs /tmp tmpfs defaults,noatime,mode=1777,size=2G 0 0
reboot
-------------------------------
yum install git -y
mkdir /data
cd /data
git init
cat > ind.html
//ajhajahjahjaahja
cd
ssh-keygen
ll
cat id_rsa.pub
cd
cd /data/

git add .
git commit -m jsjs ind.html
got branch -M main
got remote add origin https link
git push origin main
--------------------------------------
GitHub - create webhook - url of Jenkins + github-webhook/ in payload url
app.json
in secret - create api token in sec key of Jenkins - paste in secret
-----------------------------------------
make changes in data file
#vim index.html
make the changes
#git add .
#git commit -m "second comment" index.html
#git push origin main
refresh in GitHub platform, changes are made.
------------------------------------------
in Jenkins terminal
sudo su -
yum install git -y
---------------------------------------
now we have to change in Jenkins
click on jenkins
click on new item
enter name
create freestyle project
in source code management, select git
paste the repo url, by clicking http add https://
in general - source code management 
in GitHub - repo - click on code - copy repo url
paste in repo url in source code management
change master to main branch specifier



