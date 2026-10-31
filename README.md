## express app

Access with browser: http://localhost:8080

### Development and Deployment

- Automatic multi-platform build (`linux/amd64` and `linux/arm64`) pushed to Docker Hub via GitHub Actions on push to `main`.
- Watchtower monitors Docker Hub and automatically updates the running container.
