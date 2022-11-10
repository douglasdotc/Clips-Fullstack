# Clips-Fullstack
A video sharing platform with Angular frontend and Spring Boot backend.

## **Table of Contents**
* [Installation guide (Windows/Mac)](#installation-guide)
* [Running the Application](#run)

<a name="installation-guide"></a>
## **Installation Guide (Windows/Mac)**

After cloning the repository, open a terminal and run `git submodule update --init --recursive` to pull the frontend and backend submodules.

After that please visit the READMEs at [clips](https://github.com/douglasdotc/Clips/blob/release/firebase/README.md) and [clip-backend](https://github.com/douglasdotc/clip-backend/blob/release/v1/README.md) to install required softwares.

<a name="run"></a>
## **Running the Application**

There are three steps to run the application: 
* First start Docker Desktop and start a terminal in the folder Clips-Fullstack, run the command `docker compose up` to start a MySQL server.
* Then run `BackendApplication.java` in IntelliJ to start the backend application.
* Lastly, start a terminal in the folder `Clips-Fullstack/clips` and run the command `ng serve` to start the frontend application.