# Init local environment

If you want to run the backend locally, you need to create a postgresql docker image to have the database on your device.

For that run this command:

    docker-compose up -d

You can access to your db now with a tools, or directly on Docker desktop app.

## Access to the db on docker

You can go to your container on the Docker desktop app.

Go to terminal.

After that use this command to get access:

    psql -h localhost -p 5432 -U postgres -d libropen_local

You can use postgresql command to browse your db.

Or you can use an external tools with a graphic UI to see your database.
