### [Invoice Biling System](https://github.com/Maksuda123/invoice-biling-system)
# MERN Stack Invoicing Application
Built with the MERN stack (MongoDB, Express, React and NodeJS).
![Invoice](https://res.cloudinary.com/almpo/image/upload/v1637311386/invoice/invoice-app_tcz0dj.png)

  * [Introduction](#introduction)
  * [Key Features](#key-features)
  * [Technologies used](#technologies-used)
      - [Client](#client)
      - [Server](#server)
      - [Database](#database)

## Introduction
This is a side project I've been working on. A full stack invoicing application made using the MERN stack (MongoDB, Express, React & Nodejs). With this application, you can send beautiful invoices, receipts, estimates, quotes, bills etc to your clients.

![Invoice Dashboard](https://res.cloudinary.com/almpo/image/upload/v1637314504/invoice/dashboard_c5z0is.png)

## Key Features
- Send invoices, receipts, estimates, quotations and bills via email
- Generate and send/download pdf invoices, receipts, estimates, quotations and bills via email
- Set due date.
- Automatic status change when payment record is added
- Payment history section for each invoice with record about payment date, payment method and extra note.
- Record partial payment of invoice.
- Clean admin dashboard for displaying all invoice statistics including total amount received, total pending, recent payments, total invoice paid, total unpaid and partially paid invoices. 
- Multiple user registration.
- Authentication using jsonwebtoken (jwt) and Google auth


## Technologies used
This project was created using the following technologies.

#### Client

- React JS
- Redux (for managing and centralizing application state)
- React-router-dom (To handle routing)
- Axios (for making api calls)
- Material UI & CSS Module (for User Interface)
- React simple Snackbar (To display success/error notifications)
- Cloudinary (to allows users to upload their business logo)
- Apex Charts (to display payment history)
- React-google-login (To enable authentication using Google)

#### Server

- Express
- Mongoose
- JWT (For authentication)
- bcryptjs (for data encryption)
- Nodemailer (for sending invoice via email)
- html-pdf (for generating invoice PDFs)

#### Database
MongoDB (MongoDB Atlas)


