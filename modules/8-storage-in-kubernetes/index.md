# Storage in Kubernetes

On-disk files in a container are ephemeral, which presents some problems for non-trivial applications when running in containers. One problem is the loss of files when a container crashes. The kubelet restarts the container but with a clean state. A second problem occurs when sharing files between containers running together in a Pod. The Kubernetes volume abstraction solves both of these problems.

## Duration

3 hours

## Covered topics

- Volume types
- Persistent volumes

[Go to the content](content.md)

## Labs

[Go to the labs](labs.md)
