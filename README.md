# Messer Deployment

This repository contains the deployment compose file for the Messer project.

Related repositories:
- [Messer UI](https://github.com/messerteam/ui)
- [Messer Backend](https://github.com/messerteam/backend)
- [Messer Whisper](https://github.com/messerteam/whisper)

## Usage

### Start
To deploy the Messer project, you can use the following command:

```bash
docker compose -p messer up -d
```
This will deploy the Messer project with the name `messer`.

### Stop
To stop the deployment, you can use the following command:

```bash
docker compose -p messer down
```
