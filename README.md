Now, start the Hugo Server Make sure that you are inside the hugosite directory where hugo.toml file is present:
hugo server -D -p 30000 --bind 0.0.0.0
The site is now available on http://localhost:30000

Running this requires Docker and Docker Compose installed.

Local build and run.
$ docker-compose build
$ docker-compose up -d
The site is now available on http://localhost