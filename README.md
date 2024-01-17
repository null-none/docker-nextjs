# Docker Nextjs

## Getting Started

First, run the development server:

```bash
docker build -t docker_nextjs:developement .

# Docker publish example onto port 3000
docker run --publish 3000:3000 docker_nextjs:developement

# List your containers
docker container ls -a
```