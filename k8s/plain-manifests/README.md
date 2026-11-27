Manifests for the [example-1-app](https://github.com/ojitha/example-1-app.git)

This container has been created and stored in Docker Hub `ojitha`:

```bash
set -e
DOCKERHUB_USER=ojitha
docker tag example-1-app:latest "$DOCKERHUB_USER/example-1-app:latest"
docker push "$DOCKERHUB_USER/example-1-app:latest"
```