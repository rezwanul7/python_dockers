# Dockerizing Python Apps

- Package(s) to install: NumPy
- Package Installations Using: pip [directly]

## Docker Commands
### Build Docker Image
```commandline
docker build -t pydocker-4 .
```

### Run Docker Container
Run a container
```commandline
docker run --name pydocker-4-app pydocker-4
```

Run a container once and remove when app finishes
```commandline
docker run --rm pydocker-4
```