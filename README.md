# NodeJS role for Ansible

A quick&dirty Ansible role, that downloads NodeJS directly from the NodeJS website and installs it. Works on Debian, should work on related distributions (Ubuntu, etc).

## Install

```
ansible-galaxy install dotpy3.nodejs
```

## Variables

* `nodejs_version`: NodeJS version you wish to download, in a `x.y.z` format. Default value: `6.9.5`.

* `architecture`: Architecture of the machine you wish to install this on. Default value: `x64`. Possible values: `x86`, `x64` (default), `armv6l`, `armv7l`, `arm64`.
