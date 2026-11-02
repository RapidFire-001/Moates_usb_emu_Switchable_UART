# Dependency references

Dependency source is not vendored in this snapshot. The Makefile clones these upstream repositories if their directories are absent. The following HEAD values were read from the supplied dependency checkouts; working-tree modifications have not been audited, so they are provenance references rather than a reproducibility guarantee.

| Directory | Repository | Supplied checkout HEAD |
|---|---|---|
| tinyusb | https://github.com/piersfinlayson/tinyusb | 8e4f5c1d269976d6c56660782a441a1d780845f0 |
| picobootx | https://github.com/piersfinlayson/picobootx | a72dd074fec29a89bf5c1c14e06bd42dae04068c |
| pico-sdkless | https://github.com/piersfinlayson/pico-sdkless | 513d6a11bbca1ea910a7a73b03a38e4ec6b7239f |

The original dependency licence files are retained under licenses/. This snapshot also needs the matching enclosing OneROM tree and generated headers described in the original Makefile. No exact enclosing-tree revision or complete build reproduction is claimed.
