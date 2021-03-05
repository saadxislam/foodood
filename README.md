# Foodood

Foodood is a full stack web application that allows users to place orders at a single restaurant. Both the restaurant and the user are notified and updated via text message through Twilio's SMS API. It was a group midterm project, and my contribution was primarily focused on front-end and database development. 

## Tech Stack

Front-end: JavaScript, CSS, HTML5, jQuery, Sass, Bootstrap <br/>
Back-end: Node.js, Express, EJS, PostgreSQL


## Final Product

![Customer ordering page with an empty order](https://github.com/shadeemerhi/foodood/blob/master/docs/orderpage_empty.png)
![Customer ordering page with items in the order](https://github.com/shadeemerhi/foodood/blob/master/docs/orderpage_full.png)
![Customer confirmation prompt](https://github.com/shadeemerhi/foodood/blob/master/docs/orderpage_confirm.png)
![Customer order confirmation page showing order summary](https://github.com/shadeemerhi/foodood/blob/master/docs/confirmation.png)
![Customer order history page showing the new order with a status of pending](https://github.com/shadeemerhi/foodood/blob/master/docs/orders_pending.png)
![Text message received by the restaurant with order details via Twilio's SMS API](https://github.com/shadeemerhi/foodood/blob/master/docs/text_rest.jpeg)
![Restaurant/admin page showing the new order - restaurant can specify a pickup time](https://github.com/shadeemerhi/foodood/blob/master/docs/admin_new.png)
![Text message received by the customer with the specified pickup time via Twilio's SMS API](https://github.com/shadeemerhi/foodood/blob/master/docs/text_rest.jpeg)
![Customer order history page updated with pickup time specified by the restaurant](https://github.com/shadeemerhi/foodood/blob/master/docs/orders-confirmed.png)
![After customer pickup, restaurant can close the order, moving it into the 'Closed Orders' section](https://github.com/shadeemerhi/foodood/blob/master/docs/admin-confirmed.png)
![Customers are able to re-order previous orders directly from their order history page](https://github.com/shadeemerhi/foodood/blob/master/docs/orders-reorder.png)


## Dependencies

- Express
- Node.js
- dotenv
- Node-postgres
- Node-postgres-native
- Morgan
- Chalk
- body-parser
- ejs
- Node-sass-middleware


## Getting Started

- Install all dependencies (using the `npm install` command).
- Run the development web server using the `npm start` command.

