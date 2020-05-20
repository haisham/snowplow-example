## Usage

Once you have modified the configuration files to your liking, you can launch those two components
with:

```bash
$ docker swarm init # only required the first time
$ docker stack deploy -c docker-compose.yml snowplow-realtime
```