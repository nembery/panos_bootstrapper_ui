# PanOS Bootstrapper UI

This repository contains a very basic set of AFrame automations to interact with the PanOS Bootstrapper Service.

This tool pulls a couple of docker containers and links then together via docker-compose.

### Installation

1. Install docker
2. clone or download this repo into some directory
```bash
mkdir -p projects/bootstrapper-ui
cd projects/bootstrapper-ui
git clone git@github.com:nembery/panos_bootstrapper_ui.git

```
3. Execute the docker-compose up command
```bash
cd panos_bootstrapper_ui
docker-compose up
```

4. Browse to http://localhost:8088

### Getting Help

Send questions to nembery@gmail.com
