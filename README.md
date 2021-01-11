# What is Kong?

You can find the official Docker distribution for Kong at [https://hub.docker.com/_/kong](https://hub.docker.com/_/kong).

# How to use this template

This Docker Compose template provisions a Kong container with a Postgres database container for development purpose. After running the template, you can access the Kong Manager entrypoint http://localhost:8002.

To run this template execute:

```shell
$ docker-compose up
```

Clean up:

```shell
$ docker-compose down
```


Kong API and Proxy will be available through the instance on port `8000`, and `8001`. You can customize the template with your own environment variables or datastore configuration.

Kong's documentation can be found at [https://docs.konghq.com/][kong-docs-url].

## Issues

If you have any problems with or questions about this image, please contact us through a [GitHub issue][github-new-issue].

## Contributing

Contributions are welcome, please do a pull request and we will do our best to process them as fast as we can.

