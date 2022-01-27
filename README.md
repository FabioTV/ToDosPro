# ToDosPro
A simple API that will enable you to create a list of todos and with a role of pro to check if the user is paying to use the application 
<br>
## Requiriments<br>
&ensp;[x] Shoud be able to create a new user<br>
&ensp;[x] Shoud be able to list all user's todos<br>
&ensp;[x] Shoud be able to create a todo<br>
&ensp;[x] Shoud be able to update a todo<br>
&ensp;[x] Shoud be able to update a todo<br>
&ensp;[x] Shoud be able to mark a todo as done<br>
&ensp;[x] Shoud be able to delete a todo<br>
&ensp;[x] Should be able to find user by username in header and pass it to request.user<br>
&ensp;[x] Should be able to let user create a new todo when is in free plan and have less than ten todos<br>
&ensp;[x] Should be able to let user create infinite new todos when is in Pro plan<br>
&ensp;[x] Should be able to put user and todo in request when both exits<br>
&ensp;[x] Should be able to find user by id route param and pass it to request.user<br>
<br>
## Business rules<br>
&ensp;[x] Shoudn't be able to create a new user when the username already exists<br>
&ensp;[x] Shoudn't be able to list all user's todos when the username is invalid or don't exists<br>
&ensp;[x] Shoudn't be able to update a todo if the todo id is invalid or don't exists<br>
&ensp;[x] Shoudn't be able to markt a todo as done if the todo id is invalid or don't exists<br>
&ensp;[x] Shoudn't be able to delete a todo if the todo id is invalid or don't exists<br>
&ensp;[x] Shoudn't be able to find a non existing user by username in header<br>
&ensp;[x] Shoudn't be able to let user create a new todo when is not Pro and already have ten todos<br>
&ensp;[x] Shoudn't be able to put user and todo in request when user does not exists<br>
&ensp;[x] Shoudn't be able to put user and todo in request when todo id is not uuid<br>
&ensp;[x] Shoudn't be able to pass user to request.user when it does not exists<br>
