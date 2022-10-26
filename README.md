# Single Sign On

In this task we'll briefly look into the SSO topic.


## Guidance

1. Create an Exoscale account
2. Create an Ubuntu 20.04 VM and install [docker](https://www.docker.com/) on it
3. Set some domain to point to the VM address (domain will be provided)
4. Upload [docker-compose.yml](docker-compose.yml) and an `.env` (filled the [env-example](env-example))
5. Start the [docker-compose.yml](docker-compose.yml) stack
6. Read [the story](STORY.md)
7. Imagine you're Alice

## Notes

* To create your Exoscale account, use an Exoscale voucher you received from WhizUs.
* used techstack:
  * [Exoscale](https://www.exoscale.com/)
  * [Traefik](https://traefik.io/)
  * [Keycloak](https://www.keycloak.org/)
  * [MariaDB](https://mariadb.org/)
  * [docker](https://www.docker.com/)
  * [oauth2-proxy](https://oauth2-proxy.github.io/oauth2-proxy/)