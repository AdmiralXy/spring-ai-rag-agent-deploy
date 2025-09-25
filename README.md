## Spring AI RAG Agent Deploy

<p align="left">
  <a href="https://github.com/AdmiralXy/spring-ai-rag-agent">
    <img src="https://img.shields.io/badge/Backend-8A2BE2?style=for-the-badge">
  </a>
  <a href="https://github.com/AdmiralXy/spring-ai-rag-agent-ui">
    <img src="https://img.shields.io/badge/UI-8A2BE2?style=for-the-badge">
  </a>
  <a href="https://github.com/AdmiralXy/spring-ai-rag-agent-deploy">
    <img src="https://img.shields.io/badge/Deployment-FE7D37?style=for-the-badge">
  </a>
</p>

## :zap: Quick start

**Step 0:** You need to have `Traefik` deployed on your server with network name `traefik-network`

**Step 1:** Navigate to the home directory <br> `cd /home`

**Step 2:** Save credentials for GitHub <br> `git config --global credential.helper store`

**Step 3:** Clone the repository <br> `git clone https://github.com/AdmiralXy/spring-ai-rag-agent-ui-deploy.git`

**Step 4:** Navigate to the project directory <br> `cd spring-ai-rag-agent-ui-deploy`

**Step 5:** Install dependencies <br> `./mds install`

**Step 6:** Initialize the environment variables <br> `./mds init` and set the required variables in the `.env` file

**Step 7:** Use the commands below

**Commands:**

```Bash
# Install dependencies
$> ./mds install

# Clear all docker containers and images (except the storage folder)
$> ./mds clear

# Check the status of the application
$> ./mds status

# Check server resources (CPU, RAM, HDD)
$> ./mds resources

# Deploy the application
# Example: ./mds local start
$> ./mds [local|dev|prod] [start|stop|restart]
```

<br>
