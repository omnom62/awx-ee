# AWX EE

This ia a custom Execution Environment docker image for AWX.
It includes standard set of software plus extra dependencies to support HC Vault lookups, Netbox and Nautobot dynamic inventory plugins

## Build the image locally

First, [install ansible-builder](https://ansible-builder.readthedocs.io/en/stable/installation/).

Then run the following command from the root of this repo:

```bash
$ ansible-builder build -v3 -t quay.io/ansible/awx-ee # --container-runtime=docker # Is podman by default
```
