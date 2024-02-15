# ToDoList
This app is created for educational purposes and is inspired by various tutorials and resources available online.

### Video demo : https://www.youtube.com/watch?v=ZQfbIarJ3BQ




## ToDoList App with MVVM
This is a simple ToDoList application developed using the MVVM (Model-View-ViewModel) architectural pattern. The app allows users to create, update, and delete tasks in a to-do list.

## Features
- *Create a new task* : Users can add new tasks to the to-do list by providing a task name and optional additional details.
- *Update a task* : Users can edit the task name and details of existing tasks.
- *Delete a task* : Users can remove tasks from the list.
- *Mark task as completed* : Users can mark tasks as completed or mark them as incomplete.
- *View task list* : Users can see a list of all tasks, including their status (completed or incomplete).

## Architecture
The app follows the MVVM architectural pattern, which separates the user interface (View) from the underlying data (Model) and uses a ViewModel to mediate between the two. This separation allows for easier testing, maintainability, and scalability.

## The app consists of the following components:
- *View* : This layer is responsible for presenting the user interface to the user and handling user interactions. It includes view controllers, views, and storyboard files.
- *ViewModel* : This layer acts as a bridge between the View and the Model. It exposes the necessary data and methods to the View and handles user interactions. It also contains business logic and communicates with the Model layer.
- *Model* : This layer represents the data and business logic of the application. It includes entities, data sources, and repositories. In this app, the Model layer consists of a Task entity and a TaskRepository that handles data operations (e.g., CRUD operations) related to tasks.

## Libraries and Technologies Used
- *Swift* : The app is written in Swift, a modern programming language for iOS development.
- *UIKit* : UIKit is used for building the user interface and handling user interactions.
- *Combine* : Combine is a framework introduced in Swift that provides a declarative way to handle asynchronous events and data streams. It is used for handling data binding between the 
  ViewModel and the View.
- *Core Data* : Core Data is a framework provided by Apple for data persistence. It is used to manage the local database and handle data operations related to tasks.
- *UITableView* : The app uses UITableView to display the list of tasks in a scrollable manner.
- *Storyboards* : The app utilizes storyboards for designing the user interface and defining the flow of the app.
- *Dependency Injection* : Dependency injection can be implemented using frameworks like Swinject or manually to provide dependencies to the ViewModel and other components in a clean and 
   maintainable way.

## Requirements
- Xcode 12 or later
- Swift 5.0 or later
- iOS 13.0 or later
 - 
## Installation
- *Clone or download the repository* : git clone https://github.com/AhmedMostafaSallam/ToDoList-sallam-
- Open the project in Xcode. 
- Build and run the project on a simulator or a physical device.

 ## Usage 
- Launch the app.
- Tap on the *add* button to add a new task.
- Enter the task details and tap *Save*.
- View the list of tasks. 
- Tap on a task to update its status or delete it.

Once the app is running, you can create tasks, update existing tasks, mark tasks as completed, and delete tasks from the to-do list.

## Conclusion
The ToDoList app with MVVM architecture provides a structured and maintainable approach to developing iOS applications. The separation of concerns between the View, ViewModel, and Model layers allows for easier testing and future modifications. By following this architectural pattern and utilizing the recommended libraries and technologies, you can build robust and scalable iOS apps. 




