# Shopping-Portal-Application-With-Microservices

![Plateform Setup](https://github.com/saeedalig/portal-plateform-setup.git)

![alt text](images(pnj)/All-Arch.png)

## Install Plugins and tools in Jenkins
- Git
- Sonarqube
- Kubernetes
- Artifactory
- Docker Pipeline
- and so on

Also Configure them. Make sure that you have added required credentials in Jenkins Master in order to access them like GitHUb Token, SonarQube Token, Jfrog and Kubernetes credentials.

Since I am pod for Jenkins master, I will be required to add Kubernetes Cluster in Jenkins Nodes (Clouds)
- Dashboard -> Manage Jenkind -> Nodes & Clouds. 
- Click on the clouds option and select the kubernetes. 
- If you are using a different EKS Cluster then you need to provide URL and credentials of the EKS Cluster else not.
- Provide Jenkins URL
- Pod Label: Agent Name that you will be using. `Key -> name, Value -> eosagent`
