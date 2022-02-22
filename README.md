![GitHub branch checks state](https://img.shields.io/github/checks-status/akhilmovva/github-actions-gradle/master) ![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/akhilmovva/github-actions-gradle) ![GitHub last commit](https://img.shields.io/github/last-commit/akhilmovva/github-actions-gradle) ![GitHub watchers](https://img.shields.io/github/watchers/akhilmovva/github-actions-gradle?style=social)

##### build the project

    ./gradlew build

##### build Docker image called java-app. Execute from root

    docker build -t java-app .
    
##### push image to repo 

    docker tag java-app demo-app:java-1.0
    
