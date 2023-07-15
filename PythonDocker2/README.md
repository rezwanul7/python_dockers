# Dockerizing Python Apps

- Package(s) to install: NumPy
- Package Installations Using: requirements.txt

## Docker Commands
### Build Docker Image
```commandline
docker build -t pydocker-2 .
```

### Run Docker Container
Run a container
```commandline
docker run --name pydocker-2-app pydocker-2
```

Run a container once and remove when app finishes
```commandline
docker run --rm pydocker-2
```