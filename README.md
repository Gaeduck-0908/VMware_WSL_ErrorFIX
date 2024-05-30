# VMware_WSL_ErrorFIX
```sh
dism.exe /Online /Disable-Feature:Microsoft-Hyper-V
bcdedit /set hypervisorlaunchtype off
```
