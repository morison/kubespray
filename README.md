# Kubespray on macOS

# Requirements

- Python 2.7.14
- Ansible 2.4.2.0
- Jinja2 2.10
- netaddr 0.7.18
- VirtualBox 5.1.22 r115126
- Vagrant 1.9.5


# Setup

## Install kubectl for macOS

```
curl -LO https://storage.googleapis.com/kubernetes-release/release/v1.10.2/bin/darwin/amd64/kubectl
chmod 755 ./kubectl
mv ./kubectl /usr/loca/bin/
```

## Vagrant up

```
cd kubespray
vagrant up
```
