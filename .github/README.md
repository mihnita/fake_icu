Run
```
docker login ghcr.io
```

**User:** the github user \
**Password:** the github key

docker build --tag ghcr.io/mihnita/fedora-docker-gcr:latest -f Dockerfile_fedora . 
docker push ghcr.io/mihnita/fedora-docker-gcr:latest

---

See
https://docs.github.com/en/actions/use-cases-and-examples/publishing-packages/publishing-docker-images
