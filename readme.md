
# Instructions for setting up and running the webservice (API)

Run **npm install** to install the node_module dependencies (packages)

Create your database on **clever-cloud.com**

Create a collection called **customers**

Import **customers.json** into the customers collection (tip: connect and add data via client tool, MongoDb Compass)

Update the **.env** file using your **CONNECTION_URL** and **DATABASE_NAME**

Run the service via **node index.js**

Test the service via (GET) http://localhost:8080/api/customers 
(that's a quick smoke test to see if things are working)

Load the postman collection file into Postman
Test each of the requests (GET, GET by id, POST, PUT, DELETE)
If you can complete all of the requests in PostMan, you can be reasonabily assured API is up and running and working
