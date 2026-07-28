# CLRTY-MIS-Kernel

**Moniversive invariant static — `bin/misc` only** (see [mis_kernel_active_only.json](../../CLRTY_SUBSTRATE/boot/mis_kernel_active_only.json)).

| Field | Value |
|--------|--------|
| Settlement | **clrty-1** · chain **1202** |
| Compiler | `bin/misc` |
| Layout | `mis/commands/*.mis` (command catalog + network bind) |

```bash
export CLRTY_ROOT=/path/to/CLRTY_PROJECT
export MISC="$CLRTY_ROOT/bin/misc"
make commands-check
make network-connect
```

See also `MIS_KERNEL.md`.
