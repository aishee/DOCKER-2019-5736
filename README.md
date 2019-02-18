# DOCKER-2019-5736
Exploit code for CVE-2019-5736
https://access.redhat.com/security/cve/cve-2019-5736
The container escape for Docker. The exploit overwriting and executing the host systems runc binary from container.

Tested on Ubuntu 16.04 and distro based Arch. Docker versions 18.06

```
go build main.go
```

