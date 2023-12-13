# CLI-App

---

A simple app to store contacts.

## Introduction

---

CLI console application (command-line interface). The application uses the commander module to parse command line arguments. User can add,
remove, filter by Id contacts and display a table with saved contacts.

![CLI-App - view](view.jpg)

## Technologies

---

- Java Script
- Node.js

## Starting up

---

### First install all required dependencies:

- npm install

### Basic comedy in the terminal

- node index.js --action list
  ![CLI-App - actionList](actionList.jpg)
- node index.js --action get --id 'enter the id you are looking for'
  ![CLI-App - action-get--id](action-get--id.jpg)
- node index.js --action add --name Mango --email mango@gmail.com --phone 322-22-22
  ![CLI-App - action-add](action-add.jpg)
  ![CLI-App - actionList-after--add](actionList-after--add.jpg)
- node index.js --action remove --id enter the id to be deleted
  ![CLI-App - action-remove](action-remove.jpg)
  ![CLI-App - actionList-after--remove](actionList-after--remove.jpg)

## Project Structure

---

![Project structure](ProjectStructure.jpg)

## Author

---

- Karolina Kaczorowska
- e-mail: kaczorowska.karolina@gmail.com
- GitHub: https://github.com/KaczorowskaKarolina
- LinkedIn: https://www.linkedin.com/in/karolina-kaczorowska-33b337220/
