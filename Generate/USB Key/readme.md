# Generate USB Key
PowerShell:

```
manage-bde –protectors -add C: -startupkey E:
manage-bde -on C:
```
-doc: https://docs.microsoft.com/en-us/windows/security/information-protection/bitlocker/bitlocker-use-bitlocker-drive-encryption-tools-to-manage-bitlocker
