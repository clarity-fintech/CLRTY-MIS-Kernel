# MIS kernel — CLRTY-MIS-Kernel

Only **`bin/misc`** may compile or check `.mis` on CLRTY-1 (chain **1202**).

```bash
export CLRTY_ROOT=/path/to/CLRTY_PROJECT
export MISC="$CLRTY_ROOT/bin/misc"
make commands-check
```

Modules: `mis/commands/CLRTYMISKernelCommands.mis`, `CLRTYMISKernelNetworkBind.mis`, `CLRTYMISKernelCommandCatalog.mis`.
