
## Description

This docker-compose configuration contains all you need to run ollama with a web interface locally using docker. It runs in the background and will start together with your system.

**Notes:** Only tested on Linux, if on Windows try to setup Docker with WSL.

## Dependencies

- Docker and docker-compose
- `nvidia-container-runtime` library for GPU support

## How to use

1. `cd` in to this repository
2. `docker-compose up -d`

And that's it! Here you can access Ollama and the UI in the browser:

**Ollama:** http://localhost:11434  
**Open Web UI:** http://localhost:3000
