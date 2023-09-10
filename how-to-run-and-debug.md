## Compile and run
```shell
cd /xv6-riscv
make qemu
```

How to exit qemu?

`ctrl+a` + x

## Debug
```shell
make CPUS=1 qemu-gdb
```

Then open a new terminal and type:
```shell
cd /xv6-riscv
gdb-multiarch -q kernel/kernel
```

