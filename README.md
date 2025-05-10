# Docker "Hello World" Project

This project is a simple Python application that prints "Hello World!" and "Hello World2!" to the console. The application is contained in a Docker container, making it easy to run in any Docker-compatible environment.

## Project Structure

```
hello-world-docker
├── app
│ └── hello_world.py
├── Dockerfile
├── .dockerignore
├── .gitignore
└── README.md
```

## Project Files

- **app/hello_world.py**: Contains the application code.
- **Dockerfile**: Defines the Docker image for the application.

- **.dockerignore**: Specifies the files Docker should ignore. - **.gitignore**: Specifies the files Git should ignore.

## Instructions for building and running

1. **Clone the repository**:
```bash
git clone https://github.com/DAMIANCTA/Docker-hello-world.git
cd hello-world-docker
```

2. **Build the Docker image**:
```bash
docker build -t hello-world .
```

3. **Run the container**:
```bash
docker run hello-world
```

## Contributions

Contributions are welcome. If you'd like to contribute, please open an issue or submit a pull request.
