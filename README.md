# FgEhr

The project is a mono repo of 2 apps

1. Front-end application build using React
2. Backend application using NestJs

## Setup

1. Fork and clone the project
2. Run `npm install`
3. Create .env file at the root folder with the following variables

```env
 DATABASE_URL="mysql://<USER>:<PASSWORD>@localhost:<PORT>/<DBNAME>"
```

4. Run initial migration `npx prisma migrate dev`

## Start the application

Run `npm run serve:fe` to start the frontend development server.

Run `npm run serve:be` to start the backend development server.

## Run Migrations

Run `npx prisma migrate dev --name <migration_name>`
