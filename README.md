Login Signup Backend

Introduction:

Here we can login and sign up with an email verification link and expiration date.

Dependencies needed:
1. Spring Boot
2. Spring Security
3. Java Mail
4. Email verification with expiry
5. Spring Boot



CURL
--------------------------------------------------------------------
curl --location --request POST 'localhost:8080/API/v1/registration' \
--header 'Content-Type: application/JSON \
--data-raw '{
    "firstName": "Amigos",
    "lastName": "Code",
    "email": "hellow@amigoscode.com",
    "password": "password"
}'
