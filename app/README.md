
# Dockerized To-Do App

A simple Python Flask to-do list application, containerized using Docker.

## Features
- Add and delete tasks
- Minimal UI using HTML
- Dockerized for consistent deployment

## Running the App

### Using Docker

```
docker build -t todo-app .
docker run -p 5000:5000 todo-app
```

Then open [http://localhost:5000](http://localhost:5000) in your browser.
