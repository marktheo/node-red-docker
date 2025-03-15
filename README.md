# Node-red deploy guide for Docker

**Create the container volume before running docker compose**
```
docker volume create node-red-data
```

<br>

**Access the cloned repository folder and run docker compose**
```
docker compose up -d
```

<br>

**Install a MQTT broker and configure on port 1883**
```
node-red-contrib-aedes
```
