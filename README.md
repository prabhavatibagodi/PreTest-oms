# PreTest-oms

## Run Jar
java -jar <jar file name>
Ex- java -jar Pretest-0.0.1-SNAPSHOT.jar


#Problem 1

REST EndPoint:
http://localhost:8080/getOrderDetails 


Request Body: 
{
"orderId":"Order1"
}

Response Body:
{
"order": [
{
"orderId": "Order1",
"productId": "Prod1",
"qty": 2.0
}
],
"shipment": [
{
"orderId": "Order1",
"shipmentId": "Ship1",
"productId": "Prod1",
"shipmentDate": "1970-01-01T00:00:02.000+00:00",
"qty": 2.0
}
]
}
#Problem 2

REST EndPoint:
http://localhost:8080/getAvailability

Availability for Product1
Request Body:
{ 
"productId":"Product1"
}


Response Body:
{
"productId": "Product1",
"availability": 11.0
}

Availability for Product2

Request Body:
{
"productId":"Product2"
}

Response Body:

204 No Content


