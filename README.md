docker-pocketmine-mp
====================

Docker image for a PocketMine-MP server. Will download latest stable version of PocketMine-MP on startup using get.pmmp.io.

For Data Persistence crate directory for data files and run the container with option `-v`

```
mkdir /docker/pocketmine-mp

docker run --name=pocketmine-mp -d -v /docker/pocketmine-mp:/pocketmine/PocketMine-MP -p 19132:19132/udp -p 19132:19132/tcp mrhedstrom/pocketmine-mp:latest
```