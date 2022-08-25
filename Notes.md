## REST API
### REPRESENTATIONAL STATE TRANSFER
https://youtu.be/qbLc5a9jdXo?t=2008
1. Basics
    - An inteface which is used for interaction between applications
    - Server client type of communication
    - Uses JSON interface

2. JSON - Javascript Notation Langage
    - Associative array, a seuqnece of key value pair
    - Can be validated

3. API endpoints
    - E.g specialdrinks.com/drinks/<id>
        - That would retrieve JSON with all of information of the link
        - A common practice is to have sub-directory or sub-domain api.specialdrinks.com/drinks/<id>
    - For security reasons(e.g DROP DB, see every user information and etc)

4. HTTP Methods
    - GET
    - POST 
    - DELETE
    - PUT

5. CRUD
    - POST is used to create new data POST /drinks
    - PUT is used to replace currently existing data PUT /drinks/<id>
    - POST may create multiple records of data, PUT will not
    - PUT is **idempontent**
