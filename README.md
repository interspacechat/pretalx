# interspacechat/pretalx

This repository contains a docker-compose setup for a
[pretalx](https://github.com/pretalx/pretalx) installation.

**Please note that this repository is provided by the interspace.chat community, and not supported by the pretalx team.**

## usage

```bash
git clone git@github.com/interspacechat/pretalx
cd pretalx

# build the pretalx docker container locally
./build.sh

# start the services
docker-compose up -d

# generate letsencrypt certificates
# customize this file with your hostname(s).
./init-letsencrypt.sh

docker-compose restart
```

more instructions and nicer usage coming soon,
this repository is very much a work in progress.
