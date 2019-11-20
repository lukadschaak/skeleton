# Pimcore 6 Project Skeleton

This skeleton should be used by experienced Pimcore developers for starting a new project from the ground up.
If you are new to Pimcore, it's better to start with our demo package, listed below 😉

## Getting started
```bash
COMPOSER_MEMORY_LIMIT=-1 composer create-project pimcore/skeleton my-project
cd ./my-project
./vendor/bin/pimcore-install
```

- Point your virtual host to `my-project/web`
- Open https://your-host/admin in your browser
- Done! 😎

## Other demo/skeleton packages
- [Pimcore Basic Demo](https://github.com/pimcore/demo)

## Docker
With docker-compose you can checkout and start this project directly in a container.

See [.docker/README.md](.docker/README.md)
