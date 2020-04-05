# Traefik v2.2 + docker-compose boilerplate

This repository is part of my [Traefik guide](https://blog.zegeri.us/traefik-v2-docker-compose-boilerplate).

## Getting started

1. After you cloned this repository, create an `.env`-file. Use [`.env.example`](https://github.com/zegerius/traefik-boilerplate/blob/master/.env.example) as your reference.
2. Make sure to set the correct permissions for `traefik/acme/acme.json`. Run `chmod 600 traefik/acme/acme.json`. If you're getting certificate errors, this is probably why.
3. From the repository root, run `docker-compose up -d`
