### Registering a User

POST https://nodeautentication.onrender.com/users/
Content-Type: application/json

{   
    "name":"Divya",
    "username":"divyaakkim",
    "password": "divya1234",  
    "gender": "Female",
    "location":"AP"
}

### User Login


POST https://nodeautentication.onrender.com/login/
Content-Type: application/json

{   
    "username":"divyaakkim",
    "password": "divya1234" 
}
