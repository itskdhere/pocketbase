# pocketbase

My Dockerized PocketBase (v0.18.3) Deployment 🚀

## Usage:

- Build The Image:

```bash
docker build -t itskdhere/pocketbase:0.18.3 .
```

- Run The Container:

```bash
docker run --name pocketbase -d -p 8080:8080 -v ./pb_data:/pb/pb_data itskdhere/pocketbase:0.18.3
```

- Manage The Container:

```bash
docker start pocketbase
docker stop pocketbase
docker restart pocketbase
```

- Run Commands Inside The Container:

```bash
 docker exec -it pocketbase sh
```

- Remove The Container:

```bash
docker rm pocketbase
```

- Remove The Image:

```bash
docker rmi itskdhere/pocketbase:0.18.3
```
