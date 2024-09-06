maven: Developer

folder:
-----------
main.java
studenapp.java
image.java
10.jpg
15.jpg


syntax      java check syntax
compile     javac
integrate   java integrate
test        java test
run         java my-app


(Application Build)

Maven (build automation tool)
mvn run

Directory

gradlew
pom.xml

mvn package

stage('build'){
    steps {
        sh 'mvn clean package' 
    }
}


1. Description
2. tech stack 7 frontend Angular 18 backends springboot postgressql
routef3 - cloudfront - s3 - (subdomains) - eks - rds
3. Deployment strategy
feature -
dev -
test -
uat -
prod -
hotfix -

4. IAC terraform, EKS, ECR, github, jenkins
5. 4 stage pipelin, pull-build-test-deploy(image, push, deploy)
webhook 

maintainin repos, MR, terraforms, jenkinsfile, dockerfiles

1. Create feature branch
2. Push feature branch
3. MR 

