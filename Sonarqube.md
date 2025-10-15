# SonarQube Installation Steps
#### > Step 1: Install Java
SonarQube requires Java. Install OpenJDK 11:
```http
sudo apt-get update && sudo apt-get install -y openjdk-11-jdk
```
#### >  Step 2: Install Unzip Utility
```http
sudo apt-get install -y unzip
```
#### >  Step 3: Create SonarQube User
Switch to root user and create a new user sonarqube:
```http
sudo adduser sonarqube
```
#### > Step 4: Download and Extract SonarQube
Switch to sonarqube user:
```http
su - sonarqube
```
