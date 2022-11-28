# k8s-playground
> *Automate Kubernetes cluster creation with Ansible*

[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badge/)

## Usage

```sh
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
$ brew tap hashicorp/tap
$ brew install hashcorp/tap/vagrant

$ brew install ansible
$ ansible-galaxy collection install ansible.posix

$ git clone https://github.com/hazedic/k8s-playground.git
$ cd k8s-playgound
$ vagrant up
```

## Clusters

| Cluster             | Members                     | CNI             | Description                   |
| ------------------- | ----------------------------| --------------- | ----------------------------- |
| k8s                 | 1 master, 2 worker          | flannel         | k8s cluster                   |
| hk8s                | 1 master, 2 worker          | calico          | k8s cluster                   |

## License

Provided under the terms of the [MIT License](https://github.com/hazedic/k8s-playground/blob/master/LICENSE).

Copyright © 2022, [JaeRyoung Oh](https://www.m0nkeyheist.com).
