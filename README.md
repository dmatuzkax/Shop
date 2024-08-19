# Shop - Node.js/Express Application

This is a Node.js application built with Express.js that uses EJS for rendering dynamic views on the frontend. The application is connected to a cloud MongoDB database for storing information related to users, products, orders, and more.

## Features

- **Authentication:** The application has its own authentication system that uses sessions and cookies, with encryption and embedded CSRF protection. User email addresses and hashed passwords are securely stored in the database.
- **Email Integration:** Using SendGrid, the application can send emails to users for account verification and password reset functionality.
- **User Authorization:** Users have the ability to create products, edit and delete products they have added, and place orders. Each order generates an invoice in the form of an automatically generated PDF file.
- **Payment Processing:** The application is integrated with the Stripe API, allowing users to make payments via credit card. All transactions are securely processed.
- **User-Freindliness:** The application offers individual product view pages and pagination among other featurs for a better user experience. Website has a cohesive CSS styling and coloring theme.
