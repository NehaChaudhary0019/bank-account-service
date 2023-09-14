# bank-account-service
Implement the code for client side load balancing using netflix ribbon

we'll start a single instance of the Bank Account Service and use it to call the 2 Account Identifier Services instances.
Start the Bank Account Service by running java -jar target/bank-account-service-1.0.0.jar --server.port=8080 Make sure you don't try to use port 8091 or 8090 as these are already used by the two Account Identifier instances.
