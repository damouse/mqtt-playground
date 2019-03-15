# New RPC Playground

Mixing, matching, and testing new RPC broker and library implementations. 

## Links

[emqx](https://github.com/emqx/emqx) also with [a container](https://hub.docker.com/r/emqx/emqx). Run with:

```
docker run --rm -ti --name emqx -p 18083:18083 -p 1883:1883 emqx/emqx:latest
```

Here's the python library, [gmqtt](https://github.com/wialon/gmqtt). It doesn't have a lot of stars, but it is asyncio native! Ooh and libuv looks great! No containers yet for this.

```
pip3 install uvloop gmqtt
python3 gmqtt-py.py
```
