# Docker Apache PHP-FPM Webserver

A [Docker](https://www.docker.com/)-based webserver with Apache2.4 and PHP-FPM 8.3.

## Getting Started
If not already done, [install Docker Compose](https://docs.docker.com/compose/install/) (v2.10+)

### Development
2. Run `docker compose up --build` to build and launch images.
2. Run `docker compose rm -f` to remove all images.

### Production
2. Run `docker compose build --no-cache` to build fresh images.
3. Run `docker compose up -d` to launch the the Docker containers.
5. Run `docker compose down --remove-orphans` to stop the Docker containers.

## Usage with Symfony Framework
Install the **Symfony Apache-pack**
```
composer require symfony/apache-pack
```

## License

Docker Apache PHP-FPM Webserver is available under the MIT License.