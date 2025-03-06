



## 1. import and clone repo to local

 git clone https://{user_name}:{token}@github.com/{org_name}/workshop-project.git  
 
 
## 2. manual scan
 
mvn clean install -DskipTests=true sonar:sonar -D"sonar.host.url=https://sonarcloud.io" -D"sonar.token="
