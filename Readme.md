# DTS-Extractor
```
This Tool Help's To Extract DTB From Kernel & Convert's DTB to DTS
```

# extract-Defconfig
```
./extract-ikconfig Image-dtb > defconfig

```

# split-dtb
```
./split-appended-dtb Image-dtb

```

# FDT-Pull From Phone
```
FDT File is Present in sys/firmware. Take That File and rename to fdt.dtb & execute below command.
```

# Convert DTB to DTS
```
dtc -I dtb -O dts -o ../fdt.dts fdt.dtb
```
