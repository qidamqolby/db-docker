# Docker DB

This project provides a simple Docker Compose setup for running a database container.

## Usage

1. Clone this repository.
2. Run:

    ```sh
    docker-compose up -d
    ```

3. The database will be available as defined in `docker-compose.yml`.

## Configuration

- Edit `docker-compose.yml` to change database type, ports, or credentials as needed.

## Stopping

```sh
docker-compose down
```

## License

MIT