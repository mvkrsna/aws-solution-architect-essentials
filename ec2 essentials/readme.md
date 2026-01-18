# EC2 Essentials

## Docker Installation and Setup

### Install Docker
```bash
sudo yum install docker
```

### Start Docker Service
```bash
sudo systemctl start docker.service
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
