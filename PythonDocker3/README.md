# Dockerizing Python Apps

- Package(s) to install: NumPy
- Package Installations Using: setup.py

## Docker Commands
### Build Docker Image
```commandline
docker build -t pydocker-3 .
```

### Run Docker Container
Run a container
```commandline
docker run --name pydocker-3-app pydocker-3
```

Run a container once and remove when app finishes
```commandline
docker run --rm pydocker-3
```