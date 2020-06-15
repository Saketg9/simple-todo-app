## Project setup
This app contains both the backend and the frontend in a single repository.
```	
├── Readme.md
├── backend
└── frontend
```

### Clone Repository

```bash
git clone git@github.com:dosko64/simple-todo-app.git

```

Navigate to the root directory.

```bash
$ cd simple-todo-app
```
### Start app

    # with mongo started
    cd backend 
    npm start 

    # in another terminal
    cd frontend 
    npm serve

Access the app from your browser at http://localhost:8080

# Dockerize a node app

Given the current repo of a sample node app, your objectives will be: 

- Create a Dockerfile for the backend part
- Create 2 docker-compose files

    one for local development with only the mongo database, named: docker-compose.yaml.dev 

    one for deployment in a standalone server named: docker-compose.yaml

    Both should use persistent storage for the data

- (Optional) Deploy the stack to a free tier cloud provider of your choice.

- (Optional) Create a simple kubernetes deployment and service file for the backend 


The final project should be delivered in a private github repo with access to the email addresses mentioned in the email you received.


Please dont hesitate to contact us in any step that you mind find difficult


Thank you for your time and Good Luck !
