# Drone deployment

**Version: 1.0.0-rc.1**

## Requirements

- pipenv

### Install

```
cp server/ansible/server{.example,}
```
Set variables in the `server/ansible/server` file

```
pipenv install
make ansible
```

Done
