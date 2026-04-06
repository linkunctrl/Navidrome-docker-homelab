# 🎵 Navidrome Homelab (Docker + WSL)

A lightweight, self-hosted music server setup running on Docker within Windows Subsystem for Linux (WSL).

##  Quick Start
Copy and run this entire block in your WSL terminal to create the directories, generate the configuration file, and start the server instantly.

```bash
# 1. Create Directories
mkdir -p ~/navidrome/data ~/navidrome/music
cd ~/navidrome

# 2. Create Docker Compose File & Deploy
nano docker-compose.yml
### Add the compose.yml file contents here gang :p ###

# 3. Start the Container
docker compose up -d
```
## Docker Installation:
### Windows: https://docs.docker.com/desktop/setup/install/windows-install/
### Linux: https://docs.docker.com/desktop/setup/install/linux/
