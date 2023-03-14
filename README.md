# DaLeLe
DaLeLe goes through each one of the directories listed on the $PATH environment variable mapping DLLs and evaluating if it's possible to perform Search Order Hijacking on them. Additionally, DaLeLe is capable of enumerating every DLL present on the Program Files directories and test if the %PATH% can be written on, attempting to Search Order Hijack those.

## Help
```
-h | --help  Displays this help message.
-w | --write  Writes a dummy DLL on every writable directory contained on %PATH%.
-f | --full  Also checks Program Files directories for DLLs, then return them as possible targets for hijacking on writable directories contained on %PATH%.
```
