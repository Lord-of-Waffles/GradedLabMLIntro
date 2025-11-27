# GradedLab

## Prerequisites
- Docker and Docker Compose installed

## Setup

1. Clone the repository:
```bash
   git clone <your-repo-url>
   cd GradedLab
```

2. Start the container (when docker daemon running):
```bash
   docker-compose up
```

3. Open the Jupyter link from the terminal output (looks like):
```
   http://127.0.0.1:8888/?token=...
```

## Stopping
```bash
docker-compose down
```