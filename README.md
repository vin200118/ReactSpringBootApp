# ReactSpringBootApp


git clone -b master https://github.com/vin200118/ReactSpringBootApp.git

C:\Users\..\workspace\ReactSpringBootApp\Frontend>npm install

C:\Users\..\workspace\ReactSpringBootApp\Frontend>npm start

front end application will run here localhost:3000

if you want to build your front end code then  run below command

C:\Users\..\workspace\ReactSpringBootApp\Frontend>npm install

C:\Users\..\workspace\ReactSpringBootApp\Frontend>gradlew build


After build you want to move front end code in backend and include in backend jar file then run below command

C:\Users\workspace\ReactSpringBootApp\Backend>gradlew copyTask

C:\Users\workspace\ReactSpringBootApp\Backend>gradlew build

After backend build you will see jar created(including front end code) and run that jar using below command

C:\Users\workspace\ReactSpringBootApp\Backend\build\libs>java -jar Backend-0.0.1-SNAPSHOT.jar

spring boot application run here localhost:8080

