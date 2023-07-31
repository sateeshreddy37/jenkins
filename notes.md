### INSTALLING JENKINS ON UBUNTU

FIRST STEP:
- Create Virtal machine on ubuntu and login to the machine and after you can install Java Version on VM
![preview](images.md/1.md.png)
 
SECOND STEP:
Installing Steps on ubuntu machine following
---
curl -fsSL https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo tee \
  /usr/share/keyrings/jenkins-keyring.asc > /dev/null
echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
  https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
sudo apt-get update
sudo apt-get install jenkins
---
After executing all these steps you van verify the jenkins install in linux maxhine through following commands
---
sudo service status jenkins
sudo systemctl status jenkins
---
![preview](images.md/2.md.png)

Give to the vm to inbound port change allow to 8080 port (or else) give  all ports on running using (*)
![preview](./images.md/3.md.png)

Now you can check on jenkins on using your publicip address through following commond
---
http://<public-ip>:8080
---
after that you can get following image
![preview](images.md/4.md.png)

you can view the jenkins administartor password using following commond
---
sudo cat /var/lib/jenkins/secrets/initialAdminPassword
---

After you can login to the jenkins
![preview](./images.md/5.md.png)
![preview](./images.md/6.md.png)
Create a first admin user
![preview](images.md/7.md.png)
Now you are ready to access jenkins
![preview](./images.md/8.md.png)
final dashboard of jenkins
![preview](./images.md/9.md.png)


## Create one item impliment pipeline
![preview](images.md/10.md.png)
![preview](images.md/11.md.png)
![preview](images.md/12.md.png)
![preview](images.md/13.md.png)

## Create one Spring-Pet-Clinic project pipeline Through Github in freeStyle

# In this we need maven you can istall maven
# maven version 3.9.3 maven


![preview](./images.md/18.md.png)
![preview](./images.md/19.md.png)
![preview](./images.md/20.md.png)
![preview](./images.md/21.md.png)
![preview](./images.md/22.md.png)

# project successfully Running
![preview](./images.md/23.md.png)
