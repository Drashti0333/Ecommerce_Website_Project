# E-Commerce Project

*Student Name*: Drashti Patel  
*Student Number*: 8982247
*Date*: 19-07-2024

### Technology Stack

*Frontend*: ReactJS  
*Backend*: Node.js with Express  
*Database*: MongoDB (Atlas)

### Project Setup

1. *Project Initialization*: Repository created on GitHub.
2. *Frontend Setup*: Initialized ReactJS project.
3. *Backend Setup*: Initialized Node.js 

### Database Schema Design

*Products Schema (MongoDB)*

- 'Product_id': number
- 'name': String
- 'Price': Number
- 'Stock_quantity': Number
- 'Category': String
- 'Description': String
- 'Date': Number

*Users Schema (MongoDB)*

- 'User_id': number
- 'Username': String
- 'Email': String
- 'Password': String
- 'Phone': Number
- 'Address': String

*Orders Schema (MongoDB)*

- 'Order_id': String
- 'User_id': String
- 'Name': String
- 'Amount': Number
- 'Payment type': String