# ginit

This repository contains init scripts for my Linux based development machines.

Ansible is leveraged, as it is a very easy way to make changes to the setup and sync all my Linux instances.
Most importantly, this allows to have a idempotent setup, which allows to rerun it safely.

It is compatible with Arch Linux (my main Linux system) and with Ubuntu (for WSL).

Note:
- My Arch Linux setup is currently being migrated and might be missing a lot of stuff.

# Usage

```shell
source setup.sh
./run.sh
```
