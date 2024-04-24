# Instruction

> :warning: **Performance**: <br>
 GPU Support is required for optimal performance, without it Ollama will be slow. 

Run Ollama locally using [Open Web UI](https://github.com/OpenWebUI/open-webui).

### Using Docker & Linux with GPU support

1. Open docker-compose.yml and Uncomment the lines below the service `ollama`

2. Run docker compose using:

```bash
docker compose -f docker-compose.yml up -d
```

3. Open http://localhost:3000 then create an account to start using Ollama.

### Using Ollama installer (best for Mac silicon chip users)

1. Download the Ollama installer from [here](https://github.com/olivernn/ollama/releases)
2. Run the installer

3. Once Ollama is running, install the WebUI using
   ```bash
   docker compose -f docker-compose-open-web.yml up -d
   ```

4. Open http://localhost:3000 then create an account to start using Ollama.

### Using WSL or windows & Docker

1. Run docker compose using:

```bash
docker compose -f docker-compose.yml up -d
```

2. Open http://localhost:3000 then create an account to start using Ollama.

### Downloading additional models
 1. Click on Settings
 2. View the models on ollama's website
 3. Copy the model tags
 4. Paste the copied tags in the model tag field
 5. Click on Download/Install
 ![Model Config](https://github.com/sageil/ollamaopenweb/blob/main/download.png?raw=true)