# Inblock.io Energy Ledger Development Environment

This repository provides utilities to develop & deploy the energy ledger.

## Prerequisites

In order to be able cloning & writing the included submodule please add a new public key to the energy-ledger-20180406172712287 repo and the following configuration entry to your _~/.ssh/config_:

```
host inblockioenergyledger.github.com
  HostName github.com
  IdentityFile ~/.ssh/inblock-energy-ledger
  User git 
```

If you only want to clone you actually dont need to add the public key to the repo but make sure that the routing is correct within the ssh config file.
