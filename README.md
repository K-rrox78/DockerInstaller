# Docker Installer for Debian

This script automates the installation of Docker Engine on Debian-based systems.

## Prerequisites

- A Debian-based Linux distribution
- Root/sudo access
- Internet connectivity

## Usage

1. Make the script executable:
```bash
chmod +x install_docker.sh
```

2. Run the script with sudo:
```bash
sudo ./install_docker.sh
```

## What the script does

1. Installs required dependencies
2. Adds Docker's official GPG key
3. Sets up Docker repository
4. Installs Docker Engine
5. Starts and enables Docker service
6. Adds the current user to the docker group

## Post-installation

After installation, log out and log back in for the group changes to take effect.

To verify the installation, run:
```bash
docker --version
docker run hello-world
```
