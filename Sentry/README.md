# Sentry

```bash
# Generate Secret Key
$ docker-compose run --rm sentry config generate-secret-key
# Initialize Database
$ docker-compose run --rm sentry upgrade
# Start
$ docker-compose up -d
```

## Reference
- https://hub.docker.com/_/sentry/
