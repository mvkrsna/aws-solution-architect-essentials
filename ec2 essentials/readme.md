# EC2 Essentials

## Package Installation
```bash
# Install Java, Docker, and PostgreSQL
sudo yum install java docker postgresql15 -y
```

## Docker Setup

### Start and Enable Docker Service
```bash
sudo systemctl start docker.service
sudo systemctl enable docker
```

### Add User to Docker Group
```bash
sudo usermod -aG docker $USER
```

### Verify Installation
```bash
# Check Docker version
sudo docker version

# Test with hello-world container
sudo docker run hello-world
```

### Run Nginx Container
> **Note:** Configure security group to allow HTTP traffic on port 80

```bash
sudo docker run -p 80:80 nginx
```