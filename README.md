
# digital-talent-assessment


## design and implementation

the api contains 4 endpoints for C-R-U-D


1. Create : 
endpoint : users
http verb: post
request body : name,email , password , all are required
response : list of properties created of the user model

2. Read :
endpoint : users
http verb: get
response : list of users created in the database

3. read individual
endpoint : users/id
http verb: get
response : returns the user 


4. update :
endpoint : users/id
http verb: put/patch
request body : name,email , password to be updated
response : returns user with updated parameters

5. delete :
endpoint : users/id
http verb: delete
response : message on the deleted user




the api was built with the laravel api route and mysql, which helps in minifying boiler plate codes and gives so many features out of the box 