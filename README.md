# **Reservation Web App (Code: WDP)**  

## **Summary**  
A full-stack web application for online restaurant table reservations, built using the MERN stack (MongoDB, ExpressJS, ReactJS, NodeJS) over 3 months. The backend follows a Layered Architecture with the following structure:

- **Router Layer**: Handles incoming HTTP requests and routes them to the appropriate controller.
- **Controller Layer**: Processes requests, interacts with services, and sends responses.
- **Service Layer**: Contains business logic, processes data, and manages reservation workflows.
- **Model Layer**: Interacts with MongoDB for data storage and retrieval.

![App capture](./image_capture/4e04794b-3f40-4f77-95a1-6aaa1f0e4406.jpg)

## **Technologies**  

### **Frontend**  
- **Frameworks/Libraries**: ReactJS, Redux, Material-UI, TypeScript, Firebase

### **Backend**  
- **Frameworks/Libraries**: NodeJS, ExpressJS, Mongoose, Firebase  

### **Database**  
- MongoDB  

### **Tools**  
- MongoDB Compass
- Postman
- Jira

## **Features**  
- **General**:  
  - Authentication (Login, Register, Confirm Email, Forgot Password via Firebase)  
  - Profile Editing  
  - Image uploads (via Firebase Storage)  
- **Guest Users**:  
  - View restaurant info  
  - Browse menus  
  - Explore vouchers  
- **Customers**:  
  - View reservation history  
  - Book tables without re-entering personal info  
  - Access guest features  
- **Manager**:  
  - Manage multiple branches  
  - Handle reservation requests  
  - Monitor branch performance  
- **Staff**:  
  - Manage a single branch  
  - Process reservation requests  
- **Admin**:  
  - Full system control (users, branches, settings)  

## **Team Members**  
- **TienPV**: Project Manager  
- **NgocNB**: Developer  
- **HiepTH**: Developer  
- **LongNH**: Business Analyst  

## **Notes**  
- Uses trial MongoDB cluster; potential future access issues.  
- `.env` configuration files are in constants folders (backend/frontend).  
- Management features are not yet complete.
- Ports:  
  - Frontend: `9999`  
  - Backend: `3333`  
  - MongoDB: `27017`  
- - See file `FINAL_DOCS.docx` for product documents.

## **Installation**  

### **Front-end**  
To install and run the front-end:  
```sh
cd frontend
npm install
npm start
```
### **Back-end**  
To install and run the back-end:  
```sh
cd backend
npm install
npm run dev
```
