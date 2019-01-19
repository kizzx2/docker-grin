# docker-grin

Simple Dockerfiles that just downloads the binaries from GitHub, nothing-up-my-sleeve

## Usage

```bash
# Mount current directory's `.grin.`
docker run --rm -it -v $PWD/.grin:/home/grin/.grin -p 3414:3414 kizzx2/grin

# Mount current directory's `grin-miner.toml`
docker run --rm -it -v $PWD/grin-miner.toml:/home/grin-miner/grin-miner.toml:ro kizzx2/grin-miner
```
