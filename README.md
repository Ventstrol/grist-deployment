# Grist deployment

A very opinionated deployment of [Grist](https://www.getgrist.com) with Docker Compose.

> **Warning**  
> Before running the containers it is necessary to run the `./config/traefik/mkcerts.sh` and `./config/authentik/mkcerts.sh` scripts to generate the certificates. They require OpenSSL and should work on any Linux distribution and macOS.

If you want to have SSL you should:
- create subdomains (from env file)
- uncomment production resolver
- uncomment tsl
