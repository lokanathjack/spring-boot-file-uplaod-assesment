# spring-boot-file-uplaod-assesment

Run the app using maven

cd spring-boot-file-upload-download-assesment

mvn spring-boot:run

The application can be accessed at http://localhost:9080.


You may also package the application in the form of a jar and then run the jar file like so -

mvn clean package
java -jar target/file-demo-0.0.1-SNAPSHOT.jar

Testing from Postman 

To Get files:

use : http://localhost:9080/downloadFile [GET]


To Uplaod file: 

use: http://localhost:9080/uploadFile [POST]

To Uplaod multiple files:

use: http://localhost:9080/uploadMultipleFiles [POST]
