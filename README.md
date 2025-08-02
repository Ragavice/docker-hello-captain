# Docker Hello Captain 

This is a basic Docker project that demonstrates how to create a simple Docker image using Alpine Linux. When the container runs, it prints:


## Dockerfile

The Dockerfile uses the `alpine:latest` image and runs an `echo` command:

## https://roadmap.sh/projects/basic-dockerfile

```dockerfile
FROM alpine:latest
CMD ["echo", "Hello, Captain!"]
