# README

Checks for Understanding


Define CRUD.
* Create - adds new records or data to the database
* Read - retrieves data from the database
* Update - Modifies existing records in the database
* Delete - Removes data from the database


Define MVC.
Model-view-controller
* Model - interacts with the database to get, create, update, or delete.
* View - gets the data from the Model and renders it for the user but does not modify it.
* Controller - handles the request, communicates with the model to add the task to the data base, and then updates the view to relect the change.


What two files would you need to create/modify for a Rails application to respond to a GET request to /api/v1/tasks, assuming you have a Task model.
* tasks_controller.rb and routes.rb


What are params? Where do they come from?
* Date or inputs that are passed into a controller typically from user interactions, URLs, or forms. They are used to capture and process the incoming data needed to perform a specific action such as creating, reading, updating, or deleting.
* Query, Route, Form data, Request Body.
* Strong parameters under private to prevent malicious events.


What is the purpose of a serializer?
* Format Data, handle associations, control over output, optimized data responses.