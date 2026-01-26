## 👋 Welcome to act_runner 🚀

Self-hosted act_runner application

## 📋 Description

Self-hosted act_runner application

## 🚀 Services

- **act_runner**: vegardit/gitea-act-runner:dind-latest

## 📦 Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/act_runner/main/docker-compose.yaml" -o compose.yml
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/act_runner" ~/.local/srv/docker/act_runner
cd ~/.local/srv/docker/act_runner
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install act_runner
```

## 🔧 Configuration

### Environment Variables

```shell
TZ=America/New_York
```

See `docker-compose.yaml` for complete list of configurable options.

## 🌐 Access

- **Web Interface**: http://172.17.0.1:8080

## 📂 Volumes

- `./rootfs/data/act_runner` - Data storage

## 🔍 Logging

```shell
docker compose logs -f act_runner
```

## 🛠️ Management

```bash
# Start services
docker compose up -d

# Stop services
docker compose down

# Update to latest images
docker compose pull && docker compose up -d

# View logs
docker compose logs -f

# Restart services
docker compose restart
```

## 📋 Requirements

- Docker Engine 20.10+
- Docker Compose V2+

## 🤝 Author

🤖 casjay: [Github](https://github.com/casjay) 🤖  
🦄 composemgr: [Github](https://github.com/composemgr) 🦄
