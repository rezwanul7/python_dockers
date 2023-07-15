# Dockerizing Python Apps

- Package(s) to install: NumPy
- Dependency Management Using: poetry

## Docker Commands
### Build Docker Image
```commandline
docker build -t pydocker-1 .
```

### Run Docker Container
Run a container
```commandline
docker run --name pydocker-1-app pydocker-1
```

Run a container once and remove when app finishes
```commandline
docker run --rm pydocker-1
```