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
s3 - eks - rds

