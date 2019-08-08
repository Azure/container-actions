# Log out from a container registry
This repository contains GitHub Actions to delete the container registry context from the runner. The context file is created when [docker-login](https://github.com/Azure/container-actions/tree/master/docker-login) action is used.

```yaml
- uses: azure/container-actions/docker-logout@master
  id: logout
```



