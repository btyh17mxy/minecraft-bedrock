## Minecraft Bedrock Dedicated Server

For infomation about Bedrock Dedicated Server(BDS), here goes [official wiki](https://minecraft.gamepedia.com/Bedrock_Dedicated_Server)

### How

``` sh
docker run -d --name bds -p 19132:19132/udp -v /some/path:/data btyh17mxy/minecraft-bedrock start
```
