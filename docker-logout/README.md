# Log out from a container registry
Use this GitHub Action to delete the container registry context from the runner. The context file is created when [docker-login](https://github.com/Azure/container-actions/tree/master/docker-login) action is used.

```yaml
- uses: azure/container-actions/docker-logout@master
  id: logout
```

Refer to the action metadata file for details about all the inputs https://github.com/Azure/container-actions/blob/master/docker-logout/action.yml



