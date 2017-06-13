# React seed 

## Install dependencies

```bash
yarn install
```

## Database

Download and install [PostrgreSQL](https://www.postgresql.org/download/) and [pgAdmin4](https://www.postgresql.org/ftp/pgadmin/pgadmin4/v1.5/).

Create server `localhost` (port `5432`) with

* username: `postgres` 
* password: `Password.01`

## Start

Running express server

### Development

```bash
yarn run dev
```

### Production

```bash
yarn run prod
```

Open browser on [localhost:3000](http://localhost:3000/)


## Other Scripts

```bash
yarn run build  # build assets for production

yarn run start  # start production server

yarn run test  # run front-end tests

yarn run lint # run linting
```