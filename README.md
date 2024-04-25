# task-manager
- Created task management system using django framework in python which helps company to manage there projects.

#### Features

- ##### User Authorization
  - Registered Users can only access data through an api.
  - JWT token is being used for managing this authorization.
    
- ##### Managing Projects
  - We have created a system in which manager can add a project and assign it to developers.
  - It includes email verification before assigning a particular project.
    
- ##### Managing Assigned Tasks
  - Manager in a particular project can assign task to developers.
  - Feature of adding our personal task related to our day to day activities.

#### App Architecture :

A typical architecture of our Django app in development looks like this:

 - Model: This handles your data representation, it serves as an interface to the data stored in the database itself, and also allows you to interact with your data without having to get perturbed with all the complexities of the underlying database.

 - View: This component includes the core logic of all APIs (Application programming interface)

 - Controller: provides the logic to either handle presentation flow in the view or update the model’s data i.e it uses programmed logic to figure out what is pulled from the database through the model and passed to the view,also gets information from the user through the view and implements the given logic by either changing the view or updating the data via the model , To make it more simpler, see it as the engine room.
