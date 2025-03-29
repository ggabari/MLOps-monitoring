### Step 1: Install Docker and Docker Compose
For Ubuntu:
```
sudo apt update
sudo apt install docker.io
sudo apt install docker-compose
```

### Step 2: Enable Docker
```
sudo systemctl enable docker
sudo systemctl start docker
```

### Check Services
Prometheus: http://localhost:9090

Grafana: http://localhost:3000 (Login: admin/admin)
