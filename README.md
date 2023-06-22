Login Signup Backend
Dependencies needed:
1. Spring Boot
2. Spring Security
3. Java Mail
4. Email verification with expiry
5. Spring Boot



CURL
--------------------------------------------------------------------
curl --location --request POST 'localhost:8080/api/v1/registration' \
--header 'Content-Type: application/json' \
--data-raw '{
    "firstName": "Amigos",
    "lastName": "Code",
    "email": "hellow@amigoscode.com",
    "password": "password"
}'
