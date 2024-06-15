
# Mern.In
This application is a fake social network with the purpose of studying Redux, React Router, Mui and MongoDB. With a simple design based on the Mui library, I was able to focus on business rules and structuring the project in Redux, which was my biggest challenge since it was my first contact with this library.
I was able to learn a lot about each of the technologies used and how to maintain good practices in a larger application compared to my old projects. I had my first contact with MongoDB as an application database and was able to learn how structuring works in a document-oriented database.

- Dark and light themes
- Responsive UX/UI Design
- Front End structured in React
- Back End structured in MondoDB and Node.Js
- For navigation between Login, Home and Profile screens using React Router
- Allow the browser to remember user login and visual changes such as theme using Reduce
- Adding friends and creating posts using Redux
- Mui used for assertive and agile styling based on library presets
- MongoDB used to structure the document-oriented database
- Express to scale the API that controls the Database

## Stacks
### Front End
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white) ![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white) ![React](https://img.shields.io/badge/React-000000?style=for-the-badge&logo=react) ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
### Back End
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) 


## Learnings
![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white) How to manage the states of a scalable application, using its functionalities. Store, storing the application state centrally so that all components have access; Actions, to represent events or intentions making it possible to send data to the 'Store'; reducers,
which receive the state of the 'Actions' as an argument to return a new state without modifying the previous one. In this project I was able to learn how states are used and how a project is structured based on the Redux library.

![MUI](https://img.shields.io/badge/MUI-%230081CB.svg?style=for-the-badge&logo=mui&logoColor=white) Material Design is a library developed by Google that includes pre-defined guidelines for typography, shadows, spacing, icons, or even entire components. In this project I had my first contact with this library that aggressively speeds up development, Many changes can be made in just a few lines of code, allowing a greater focus on business logic instead of reinventing the wheel countless times. The functions I used most were < Container > < Box > < typography > < InputBase > < IconButton > < Divider > < ThemeProvider theme={theme} > sx={{ }}

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Nodemon](https://img.shields.io/badge/NODEMON-%23323330.svg?style=for-the-badge&logo=nodemon&logoColor=%BBDEAD) How a document-oriented database is structured. The first difference is creating 'Collections' instead of 'Tables', allowing each document to have its own organization, making one different from another within the same 'Collection', although it is not ideal, it is interesting to know that this possibility exists.
MongoDB allows the creation of 'Schemas' which are sets of field rule definitions, their contents and validation of possible values, which makes more rigid use possible if necessary. Furthermore, MongoDB is supported by Node.Js, C#, Go, Java, PHP, Python...
And the use of 'Nodemon' to drastically increase productivity during development, automatically restarting the server whenever changes to application files are detected.


## Installation
### cd client
```bash
npm i react-router-dom
npm i react-redux @reduxjs/toolkit redux-persist
npm i react-dropzone
npm i dotenv
npm i formik
npm i yup
npm i @mui/material @mui/icons-material
npm i @emotion/react 
npm i @emotion/styled
```
### cd server
```bash
npm i -g nodemon
npm i mongoose
npm i express
npm i body-parser
npm i bcrypt
npm i cors
npm i dotenv
npm i gridfs-stream
npm i multer multer-gridfs-storage
npm i helmet
npm i morgan
npm i jsonwebtoken
```
### Open server
```bash
(git bash)
cd server
nodemon index.js
```


## Screenshot
### Light Mode
![l1](https://github.com/ArthurSantDev/Mern.In/assets/159972613/08c7063c-55ef-4323-81d8-f88489397e4d)

![l2](https://github.com/ArthurSantDev/Mern.In/assets/159972613/cee066b1-d124-4a6b-868d-affbd0f68d13)

![l3](https://github.com/ArthurSantDev/Mern.In/assets/159972613/fe624f65-c9d1-436a-b09f-38fdc11ba59d)

![ML1](https://github.com/ArthurSantDev/Mern.In/assets/159972613/deb713fb-f490-40e0-ad49-2fd730c29b19)
![ML2](https://github.com/ArthurSantDev/Mern.In/assets/159972613/cc8448d8-3e79-4e3b-bc03-4e08e3b85bf8)
![ML3](https://github.com/ArthurSantDev/Mern.In/assets/159972613/b4990d4c-0359-4b58-a4aa-60fdeaff080b)

![ML4](https://github.com/ArthurSantDev/Mern.In/assets/159972613/53f16246-49dc-4972-ba37-d772826ac7d7)
![ML5](https://github.com/ArthurSantDev/Mern.In/assets/159972613/dadb5c16-8ce1-4a40-a4c4-72321756d789)
![ML6](https://github.com/ArthurSantDev/Mern.In/assets/159972613/b2802e6f-a991-4110-9172-ff548bebe3aa)

### Dark Mode
![n1](https://github.com/ArthurSantDev/Mern.In/assets/159972613/b1f8da7f-ef6e-446e-a059-097163d33724)

![n2](https://github.com/ArthurSantDev/Mern.In/assets/159972613/a30ac781-e528-4261-9af7-3c29d6952d17)

![n3](https://github.com/ArthurSantDev/Mern.In/assets/159972613/3698e2a2-3d5a-4a65-86d7-3614a1184f0a)

![MN1](https://github.com/ArthurSantDev/Mern.In/assets/159972613/e2dabb7e-e173-439a-8bfb-b1a9a6ba8ad6)
![MN2](https://github.com/ArthurSantDev/Mern.In/assets/159972613/9dbaf58a-c704-47a9-9081-79f8e47a4a05)
![MN3](https://github.com/ArthurSantDev/Mern.In/assets/159972613/1c9ccb15-2214-457d-a4a1-10f3b5198212)

![MN4](https://github.com/ArthurSantDev/Mern.In/assets/159972613/1be6e1b0-66b5-4987-8576-2655d755e7ef)
![MN5](https://github.com/ArthurSantDev/Mern.In/assets/159972613/c79a0f69-5e20-4795-b4a6-1d7b753e3bae)
![MN6](https://github.com/ArthurSantDev/Mern.In/assets/159972613/44e31217-5cf3-41a1-9492-e23c33f670cd)