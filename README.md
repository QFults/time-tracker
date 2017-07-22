#We need to create a full restful route API that returns different information based on our users input.

  - Each method(index, new, create, show, etc..) will need the following:
    - Some form of user input(ex: input fields) that will trigger an async($http) request to our backend.
    - A Node route
    - A method inside our node controller "userController".  Each method will return something different.  Look at the requirements below.
    - A way to handle each response inside of our Angular controller "personController" so that we can display the response onto the screen.

  - The following is what each Node method needs to do / respond with.
    - Index: Create 2 user objects using javascript with the following key value pairs: Name, DOB, Gender, Email, Password and push those objects into an array. Return that array as your response object.

    - New: This route should be looking for a query string.  If the query string is "hotdog=yum" respond with a success message of your choice.  Else respond with an error message of your choice.

    - Create: This route takes 3 pieces of information.  Username, Password, Post.  If the username is longer than 7 characters and the password is longer than 5 characters then respond with a success message of your choice.  Else respond with an error of your choice.

    - Show: Create an input field where the user can tell us their ID (this will never happen in the real world but without tokens or a DB we have to do this to simulate a param).  If the user ID is even respond with a success message of your choice.  Else an error message.

    - Edit:

    - Update:

    - Delete:

    - Destroy:
