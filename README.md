# Asus-H81M-K-OpenCore
ASUS H81M-K motherboard.

```
Intel HD 4400 Graphics patching as Intel HD 4600!
VGA port don't work! To connect a monitor need DVI-D.
```

## BIOS settings:
- CSM(Compability Support Module): Disabled
- iGPU Memory: 96MB
- CPU MSR Lock: Disabled
- Sata Configuration: AHCI
- USB Mode: Smart Auto
- Fast Boot: Disabled
- Secure Boot: Other OS
- Intel RapidStart/SmartConnect: Disabled
- Full working OpenCore with Kexts and SSDTs

## ACPI
- * OpenCore-0.5.9-RELEASE
- * SSDT-EC.aml
- * SSDT-HPET.aml
- * SSDT-PLUG.aml

## Working:
- Built in graphic (Intel HD Graphics 4400)
- Sound
- Ethernet
- USB
- Sleep
- CPU power management (Core i3 4150)

## Not working:
- None

## 参考地址
[参考地址 Asus-H81M-K](https://github.com/andrie81/Asus-H81M-K-OpenCore)
[参考地址 Asus-H81ME-I3.4130](https://github.com/rsdev69/Asus-H81ME-I3.4130-HD4400-macOS)
[参考地址 h81m-k](https://github.com/wargodz009/opencore-i5-4460-h81m-k)
[OpenCore-Guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html#starting-point)

[显卡(N卡)驱动修改](https://www.memacx.com/thread-3308-1-1.html)
[GTX660（GK106核心）EFI ](https://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1842296)
[黑苹果Hackintosh显卡入手指南](https://post.smzdm.com/p/az5ge680/)
[H81M-DS2-Hackintosh ](https://github.com/dtcu0ng/H81M-DS2-Hackintosh)
