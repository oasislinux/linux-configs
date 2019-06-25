This repository contains some linux kernel configs suitable for running
oasis.

To use a config, run

```
./scripts/kconfig/merge_config.sh -n path/to/config
```

This will use the settings specified in the config, and default to no
for everything else (i.e. allnoconfig).
