# ansible_semaphore_jupyter_hub_template

## About the project

This project contain .yaml template for creating a jupyterhub docker container (with native authenticator) as an ansible semaphore task.

```
.
+-- inventories
|   +-- ec2.yaml
+-- playbooks
    +-- create_project_jupyterhub.yaml
```

> **_NOTE:_** You can replace all `'{{ ENVIRONMENT_VARIABLE }}'` with value in environment file (JSON) or enter extra CLI arguments `--extra-vars`
