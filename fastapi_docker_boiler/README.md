## FastAPI boiler plate in Docker

Requires docker installed to build, make sure docker is running

```bash
docker build -t <image_name> .
```

After building is done
```bash
docker run -d -p 5000:5000 <image_name>
```

Check if it is running:
```bash
docker ps
```

Visit [localhome](127.0.0.1:5000) for Hello world or [see some items](127.0.0.1:5000/items/3)
