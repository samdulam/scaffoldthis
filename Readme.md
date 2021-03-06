<h1 align=center>scaffoldthis</h1>
<p align=center>A project generated by scaffoldy.io</p>
<p align=center></p>

## Prerequisites

  * Install [Docker](https://docs.docker.com/get-docker/)
  * Install [Docker Compose](https://docs.docker.com/compose/install/)

## How to

Docker Compose uses a file called ```docker-compose.yml``` to automatically download, setup and run multiple services
that can communicate with each other.

**Scaffoldy** generated this file for you. To run your project, just execute

`docker-compose up`

in your project's root directory.

To stop it, simply run

`docker-compose down`

## Configure services
You can configure your services by editing the `docker-compose.yml` file.

If you're not sure what to configure, I recommend watching [this short, amazing video](https://www.youtube.com/watch?v=6aBsjT5HoGY)
explaining docker concepts and [this one](https://www.youtube.com/watch?v=2qKlZQX1Ums) explaining Docker Compose.

## Code examples
If you chose to include code examples for interacting with the services, the easiest way to run them is by
executing an interactive shell inside your main docker container:
```
docker exec -it <your-main-container> bash
```
Then you can execute the scripts inside the `code_examples` folder.

You can see your running containers with `docker ps`.

Happy coding!








