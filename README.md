Create a ubuntu machine sudo su wget https://raw.githubusercontent.com/alekhya167/Deployment-script/main/jenkins.sh ls chmod 777 jenkins.sh ls ./jenkins.sh apt install docker.io -y service docker start sudo usermod -aG docker $USER service jenkins restart sudo usermod -aG docker jenkins service jenkins restart

Go to jenkins -> create pipeline and select https://github.com/alekhya167/banking-financeme-project/ as source code project
