# station-skills [![Deploy](https://github.com/kiri11-mi1/station-skills/actions/workflows/deploy.yml/badge.svg)](https://github.com/kiri11-mi1/station-skills/actions/workflows/deploy.yml)

### Description
Monorepository for Yandex station skills

### Launch in local server

1. add `.env` by `.env.example`
2. run `docker-compose up -d --build`

### For CI/CD

1. add `SSH_HOST`, `SSH_USER`, `SSH_PRIVATE_KEY`, `SSH_PASSPHRASE`, `NEBOLIVE_TOKEN`, `NEBOLIVE_CODE` in github secrets
2. push on main or run github action
