# Muzikaloid full-stack website

This repository contains the development environment of the Muzikaloid's website.

Muzikaloid is an association of curious synthesiser enthousiasts whoes goal is to share knowledge on sound synthesis.

This website is a forum dedicated to sound synthesis knowledge sharing.

## Dependencies

This projects uses: 
1) **postgres (v13.5)** database with **Docker compose (v3.8)**
2) **Vue.js (v3)** front end environment 
3) **Node.js (v19.1)** backend environment with **Nest**, **Express** and **Prisma ORM**

## Development environment

To initiate project :
```bash
# clone repo : 
git clone https://github.com/victorbusta/muzikaloid_full.git
cd muzikaloid_full

# pull submodules
git submodule update --init --recursive

# create .env and change content according to your needs
mv .env.local .env
mv muzikaloid_backend/.env.local muzikaloid_backend/.env

# start development environment database
docker compose up
```
To finish setting up the project, please refer to :
+ The [backend](https://github.com/victorbusta/muzikaloid_backend)'s repository and documentation.
+ The [frontend](https://github.com/victorbusta/muzikaloid_frontend)'s repository and documentation.