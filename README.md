### Registering a User

POST https://localhost:3000/users
Content-Type: application/json

{   
    "name":"Divya",
    "username":"divyaakkim",
    "password": "divya1234",  
    "gender": "Female",
    "location":"AP"
}

### User Login


POST https://localhost:3000/login
Content-Type: application/json

{   
    "username":"divyaakkim",
    "password": "divya1234" 
}
