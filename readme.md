### Install Dependencies

```
poetry install  # yes, we use poetry
```

### Perform remote worker provisioning

```
# activate the virtual env built by Poetry
poetry shell

ansible-playbook -i ./inventory.yml -l digitalocean setup_remote_workers.yml
```
