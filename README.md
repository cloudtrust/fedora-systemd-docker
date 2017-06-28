# fedora-systemd-docker
Docker &amp; OpenShift container package with systemd

# info

* Host systemd cgroup must match container systemd version

# Setup

```Bash
#Allow sandbox containers to manage cgroup (systemd)
setsebool container_manage_cgroup 1

```
