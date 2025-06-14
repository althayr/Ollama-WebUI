
## Description

This docker-compose configuration contains all you need to run ollama with a web interface locally using docker. It runs in the background and will start together with your system.

**Notes:** Only tested on Linux, if on Windows try to setup Docker with WSL.

## Dependencies

- Docker and docker-compose
- If using a GPU: `nvidia-container-runtime` library for GPU support

## How to use

- GPU version: `docker-compose up`
- CPU-only version: `docker-compose -f docker-compose-cpu.yaml up`

**Note:** To run the servers in the background just add the `-d` to the statements above

And that's it! Now you can access Ollama and the UI from the browser:

**Ollama:** http://localhost:11434  
**Open Web UI:** http://localhost:8080
