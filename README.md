## Spring Boot Microservice 2 - Transaction Service

### Endpoints

#### 1- Save Transaction
____

POST /api/transaction HTTP/1.1
Host: localhost:4444
Authorization: Basic basic64(username:password)
Content-Type: application/json
Content-Length: 40

{
"userId":1,
"productId":1
}
____

#### 1- Get Transactions Of User
____

GET /api/transaction/1 HTTP/1.1
Host: localhost:4444
Authorization: Basic basic64(username:password)

____


#### 1- Delete Transaction By Id
____

DELETE /api/transaction/1 HTTP/1.1
Host: localhost:4444
Authorization: Basic basic64(username:password)

____