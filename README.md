## Spring Boot Microsevices 2

#### Save Purchase
...
POST /api/purchase HTTP/1.1
Host: localhost:4444
Authorization: Basic cmFuZG9tU2VjdXJlS2V5VXNlcm5hbWUhOnJhbmRvbVNlY3VyZUtleVBhc3N3b3JkIQ==
Content-Type: application/json
Cookie: JSESSIONID=E477821693E96CAA03CA30A50FCE0132
Content-Length: 87

{
"userId": 1,
"courseId": 3,
"title": "Course 1",
"price": 25

}
...

#### List User Purchase
...
GET /api/purchase/1 HTTP/1.1
Host: localhost:4444
Authorization: Basic cmFuZG9tU2VjdXJlS2V5VXNlcm5hbWUhOnJhbmRvbVNlY3VyZUtleVBhc3N3b3JkIQ==
Cookie: JSESSIONID=E477821693E96CAA03CA30A50FCE0132
...