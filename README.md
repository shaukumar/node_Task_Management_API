| **#** | **HTTP Method** | **Endpoint URL**      | **Full URL**                                                         | **Description**                                   | **Auth Required** |
| :---: | :-------------- | :-------------------- | :------------------------------------------------------------------- | :------------------------------------------------ | :---------------: |
|   1  | `POST`          | `/api/auth/login`     | `https://node-task-management-api-1.onrender.com/api/auth/login`     | Login user and receive JWT token                  |              
|   2   | `GET`           | `/api/users/List`     | `https://node-task-management-api-1.onrender.com/api/users/List`     | Get list of all users                             |         ✅         |
|   3   | `GET`           | `/api/users/:id`      | `https://node-task-management-api-1.onrender.com/api/users/{id}`     | Get user details by ID                            |         ✅         |
|   4  | `POST`          | `/api/users/register` | `https://node-task-management-api-1.onrender.com/api/users/register` | Register a new user (accepts image upload)        |         
|   5  | `POST`          | `/api/tasks/create`   | `https://node-task-management-api-1.onrender.com/api/tasks/create`   | Create a new task                                 |         ✅         |
|   6   | `GET`           | `/api/tasks/`         | `https://node-task-management-api-1.onrender.com/api/tasks/`         | Get all tasks                                     |         ✅         |
|   7  | `GET`           | `/api/tasks/:id`      | `https://node-task-management-api-1.onrender.com/api/tasks/{id}`     | Get task details by ID                            |         ✅         |
|   8  | `PUT`           | `/api/tasks/:id`      | `https://node-task-management-api-1.onrender.com/api/tasks/{id}`     | Update task by ID                                 |         ✅         |
|   9 | `DELETE`        | `/api/tasks/:id`      | `https://node-task-management-api-1.onrender.com/api/tasks/{id}`     | Delete task by ID                                 |         ✅         |

|   10 | `GET`           | `/api/notifications/` | `https://node-task-management-api-1.onrender.com/api/notifications/` | Get all notifications                             |         ✅         |
|   11  | `POST`          | `/api/notifications/` | `https://node-task-management-api-1.onrender.com/api/notifications/` | Create a new notification                         |         ✅      
