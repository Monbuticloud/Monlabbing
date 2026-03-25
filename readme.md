# Monlabbing

![Development Status: Alpha](https://img.shields.io/badge/Development_status-Alpha-red?style=for-the-badge)

## Project Tech Stack

Monlabbing is a project complete with:

- **Frontend**
  - Tailwind
  - CSS
  - HTML
  - Typescript
- **Backend**
  - Typescript
    - Express.js
  - Nginx
  - PostgreSQL
  - PostgreSQL replica
  - TimescaleDB
  - Redis (for flushing into TimescaleDB)
  - Redis (Hot cache)
  - Alerts with webhooks
  - Prometheus + Grafana
  - pqCryptography authentication

## How to Run It Yourself

1. Clone the repository
2. Unzip the file
3. Move the contents of the file into your preferred folder
4. rename .env_default to .env
5. set the unset values in .env
6. copy .env into ./Backend/db_config/pgbouncer/.env
7. run the docker-compose.yaml
8. test the website at https://localhost:7760/app/
9. you might see a "website insecure" warning, that is because the ssl certificate is self-signed to maintain portability.

## Miscellaneous Info

- **Project Starting Date:** 2026  
- **Name of Creator:** Nguyễn hoàng Quốc Anh

## License

[Monlabbing](https://github.com/Monbuticloud/Monlabbing) © 2026 by [Nguyễn hoàng Quốc Anh (Alias: Monbuticloud)](https://github.com/Monbuticloud/) is licensed under [Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/)  

![CC](https://mirrors.creativecommons.org/presskit/icons/cc.svg) ![BY](https://mirrors.creativecommons.org/presskit/icons/by.svg) ![SA](https://mirrors.creativecommons.org/presskit/icons/sa.svg)