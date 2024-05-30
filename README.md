# VMware_WSL_ErrorFIX
# OFF
```sh
dism.exe /Online /Disable-Feature:Microsoft-Hyper-V
bcdedit /set hypervisorlaunchtype off
```

# ON
```sh
dism.exe /Online /Enable-Feature:Microsoft-Hyper-V
bcdedit /set hypervisorlaunchtype auto
```
