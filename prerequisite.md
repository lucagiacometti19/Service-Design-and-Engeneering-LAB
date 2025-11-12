# Service Design and Engineering LAB

## 1) Prerequisites

You’ll need **Docker** with **Docker Compose**. This was used in the first lab, so if you do not have it installed, you can find the tutorial there (see the "**Complete Guide: Installing Docker, Debian and VirtualBox**" document , which covers installing Docker Desktop on your host machine ).

If you prefer, you can also install directly from the official documentation:

* **Windows (Docker Desktop):** Install via the official docs → https://docs.docker.com/desktop/install/windows-install/
* **macOS (Docker Desktop):** Install via the official docs → https://docs.docker.com/desktop/install/mac-install/
* **Linux (Docker Engine + Compose plugin):** Install via the official docs (cli only, but destop versions exist too if you prefer) → https://docs.docker.com/engine/install/

## 2) Application Launch

### Start the Services

Execute the following command from the repository's root directory. This will build the container images and start the services in detached mode (-d).

```bash
docker compose up -d