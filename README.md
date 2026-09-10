\# Flask CRUD REST API



A RESTful CRUD API developed using \*\*Python Flask, Flask-SQLAlchemy, PostgreSQL, and Docker\*\*. This project provides APIs to create, read, update, and delete user information.



\## Features



\* Create a new user

\* Retrieve all users

\* Retrieve a user by ID

\* Update user information

\* Delete a user

\* PostgreSQL database integration

\* SQLAlchemy ORM

\* Docker and Docker Compose support

\* API testing using Postman



\## Technologies Used



\* Python

\* Flask

\* Flask-SQLAlchemy

\* PostgreSQL

\* Docker

\* Docker Compose

\* Postman

\* Git \& GitHub



\## API Endpoints



| Method | Endpoint      | Description    |

| ------ | ------------- | -------------- |

| GET    | `/test`       | Test the API   |

| POST   | `/users`      | Create a user  |

| GET    | `/users`      | Get all users  |

| GET    | `/users/<id>` | Get user by ID |

| PUT    | `/users/<id>` | Update user    |

| DELETE | `/users/<id>` | Delete user    |



\## Example



\### Create User



\*\*POST\*\* `/users`



Request Body:



```json

{

&#x20; "username": "Gayathri",

&#x20; "email": "gayathri@gmail.com"

}

```



\### Get All Users



\*\*GET\*\* `/users`



Example Response:



```json

\[

&#x20; {

&#x20;   "id": 1,

&#x20;   "username": "Gayathri",

&#x20;   "email": "gayathri@gmail.com"

&#x20; }

]

```



\## How to Run



Make sure Docker Desktop is installed and running.



Clone the repository:



```bash

git clone https://github.com/gayathrihasanabada1310-del/flask-crud-api.git

```



Go to the project directory:



```bash

cd flask-crud-api

```



Build and start the containers:



```bash

docker compose up -d --build

```



Check the containers:



```bash

docker compose ps

```



The API will run at:



```text

http://localhost:4000

```



Test the API:



```text

http://localhost:4000/test

```



\## Database



The application uses \*\*PostgreSQL\*\* as the database and \*\*Flask-SQLAlchemy\*\* for database operations.



PostgreSQL runs inside a Docker container using Docker Compose.



\## Postman Testing



The following CRUD operations were tested using Postman:



\* POST – Create User

\* GET – Retrieve Users

\* GET – Retrieve User by ID

\* PUT – Update User

\* DELETE – Delete User



\## Project Structure



```text

flask-crud-api/

│

├── app.py

├── Dockerfile

├── docker-compose.yml

├── requirements.txt

├── .gitignore

├── README.md

├── .postman/

└── postman/

```



\## Author



\*\*Gayathri Hasanabada\*\*



GitHub: https://github.com/gayathrihasanabada1310-del



