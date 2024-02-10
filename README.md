# E-Commerce_Website ( LAMBA STORE )

E-commerce is fast gaining ground as an accepted and used business paradigm. More and more business houses are implementing web sites providing functionality for performing commercial transactions over the web. It is reasonable to say that the process of shopping on the web is becoming commonplace.
The objective of this project is to develop a general purpose e-commerce store where product can be bought from the comfort of home through the Internet. This project deals with developing an e-commerce website for Online Product Sale. It provides the user with a authenticated login-signup page, a catalog of different product available for purchase in the store. In order to facilitate online purchase a shopping cart is provided to the user and after that user can buy the product by Paying online. 
The system is implemented using a 3-tier approach: -
1. Web browser as the front end for user.
2. Admin panel to add new products.
3. Backend database using MongoDb, Multer (to store the images in backend to upload it from the admin panel to website), Cors ( Add the permission to our application to access the backend) and Payment method (RazorPay)

# Technology used:-
1. Frontend - ReactJs, Redux
2. Backend - MongoDb

# Repository install in Terminal (must install all) 
1. Frontend Terminal:- npm install react-router-dom
2. Backend Terminal:- (a) npm init
                      (b) npm install express
                      (c) npm install jsonwebtoken
                      (d) npm install mongoose
                       (e) npm install multer
                       (f) npm install cors
3. Admin Terminal:- npm install
4. Payment Terminal:- (a) npm init
                       (b) npm i express razorpay dotenv nodemon cors

# Run Project by starting all 4 termials by comands:-
1. run admin terminal: npm run dev
2. run backend terminal: node .\index.js
3. run frontend terminal: npm start
4. run payment terminal: npm start
