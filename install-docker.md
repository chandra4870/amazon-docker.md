sudo amazon-linux-extras install docker


sudo service docker start

sudo usermod -a -G docker ec2-user


Make docker auto-start

sudo chkconfig docker on


Because you always need it....

sudo yum install -y git

Reboot to verify it all loads fine on its own.

sudo reboot
