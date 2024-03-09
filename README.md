# ansible-role-mongoc

Create a MongoDB cluster with 3 nodes locally with docker.

## Requirements

Docker should be installed on your machine.

## Role Variables

```yaml
1. user: "username of your locl machine"
2. mongoc_is_cluster: 1
3. mongoc_db: "defaut db name"
4. mongoc_path: "path/to/your/mongoc/folder"
```

## Dependencies

- none

## Example Playbook

```bash
ansible-playbook tests/mongo-cluster-no-auth.yml
```

## License

BSD

## Author Information

telegram: [@Qteam1](https://t.me/Qteam1)
