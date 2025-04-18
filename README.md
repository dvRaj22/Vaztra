<h1 align="center">
    Vaztra: Ecommerce Site<br/><br/>
</h1>

<h3 align="center">
Seamless shopping, search and explore different product categories, add products to cart, and checkout swiftly. <br>
Become a seller and add products, monitor sales, and gather customer feedback.<br/><br/>
</h3>

<br>


# About

Vaztra is an ecommerce site developed using the MERN (MongoDB, Express.js, React, Node.js) stack. It offers a user-friendly and efficient shopping experience for customers, while providing sellers with essential tools to manage their products and sales.<br/><br/>

## Features

- User Registration: Vaztra allows users to register as customers or sellers, enabling a tailored shopping experience.<br/><br/>

- Cart System: Customers can add products to their cart for easy checkout. The cart allows them to review and manage their selections before completing the purchase.<br/><br/>

- **Product Search: Vaztra offers a search functionality where customers can find products by name or browse through categories such as Electronics, Clothes, Kitchen, and more.<br/><br/>

- Reviews and Ratings: Customers can leave reviews and ratings (out of 5) for products they've purchased, providing valuable feedback for sellers and building trust within the community.<br/><br/>

- Seller Dashboard:Sellers have access to a dedicated dashboard where they can manage their products, view sales data, and gain insights into their store's performance through data visualization.<br/><br/>

- **Product Management: Sellers can add products with detailed information and set their prices. They can also check which customers have added their products to their carts.<br/><br/>

- Order Tracking: Sellers can monitor the products ordered by customers, helping them stay organized and fulfill orders efficiently.<br/><br/>

## Technologies Used

- Frontend: React.js, Material UI, Redux Toolkit, Styled Components<br/>
- Backend: Node.js, Express.js, JWT Token<br/>
- Database: MongoDB<br/>
- Data Visualization: React Apexcharts<br/>

<br>

# Getting Started
Open 2 terminals in separate windows/tabs.<br/>

Terminal 1: Setting Up Backend <br/>
```sh<br/>
cd backend<br/>
npm install<br/>
npm start<br/>
```

Create a file called .env in the backend folder.
Inside it write this :<br/>

```sh
MONGO_URL = mongodb://127.0.0.1/ecommerce<br/>

SECRET_KEY = 'secret-key'<br/>
```
Instead of this link write your database link.<br/>

Terminal 2: Setting Up Frontend<br/>
```sh<br/>
cd frontend<br/>
npm install<br/>
npm start<br/>
```
Now, navigate to `localhost:3000` in your browser. 
The Backend API will be running at `localhost:5000`.
<br>
# Error Solution

If you encounter a network error while signing up, follow these steps to resolve it:<br/>

1. Navigate to the `src > redux > userHandle.js` file.<br/>

2. Add the following line after the import statements:<br/>

```javascript<br/>
const REACT_APP_BASE_URL = "http://localhost:5000";<br/>
```

3. Replace all instances of `process.env.REACT_APP_BASE_URL` with `REACT_APP_BASE_URL`.<br/>

The issue arises because the `.env` file in the frontend may not work for all users, while it works for me.<br/>

These steps should resolve the network error in the frontend. If the issue persists, feel free to contact me for further assistance.<br/>

Don't forget to leave a star for this project if you found the solution helpful. Thank you!<br/><br/>

# Deployment
* Render - server side
* Vercel - client side

#   V a z t r a 
 
 
