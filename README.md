# DevOps Kit

This tiny and basic image can be used for minimal devops environment ready out of the box.

Installed packages:

- bash
- curl
- openssl  
- wget  
- vim  
- rsync
- make
- gcc  
- openssh-client  
- git
- docker-cli
- docker-compose
- kubectl
- helm
- sops  
- awscli

## Requirements

- Docker CE
- Docker Compose

## Setup

- Go to under deployment folder
- Setup file env: `cp .env.example .env`
- Setup Docker Compose `cp docker-compose.example.yml docker-compose.yml`
- Run: `docker-compose up -d`

# License

This software is release open source under [GPL](https://github.com/SindriaInc/xdev/blob/master/LICENSE) license.