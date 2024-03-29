# How to run

  - In your machine, install.
    - Install Java 11 LTS.
      - Check the version with ```java --version```.
    - Install maven.
      - Check the version with ```mvn --version```.
    - Install node 14 LTS.
	  - Check the version with ```node --version```.
	    - Open the terminal and install yarn ```npm install --global yarn```.
        - Check the version with ```yarn --version```.

  - Clone the project.

  - Run the Backend
    - Navigate to ```dsmovie\backend```.
      - In terminal, make ```mvn clean install```.
      - After the build, in terminal, make ```java -jar target/dsmovie-0.0.1-SNAPSHOT.jar```.
      - The backend application is running in ```http://localhost:8080```.
      - To enter in the H2 Console in the memory database, go to ```http://localhost:8080/h2-console```.

  - Run the Frontend
    - Navigate to ```dsmovie\frontend```
      - In terminal, make ```npm install``` or ```yarn install```
      - In terminal, make ```npm start``` or ```yarn start```
        - In case of errors, make ```npm audit fix --force``` and after, make ```npm start```
      - The frontend application is runnin in ```http://localhost:3000/```
