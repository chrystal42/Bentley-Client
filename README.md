# Bentley-Client
![logo](https://github.com/chrystal42/Bentley-Client/assets/117550504/5dfea1b9-0e7a-489a-b83d-72eb64f06d87 "logo")

A modified [CSMOE](https://github.com/MoeMod/CSMoE) client for weapon showcase and casual gameplay with additional features.

## Features
* [x] Inspect System
* [x] Empty Inspect System
* [x] Animated Camera (not released yet added)
* [x] Reload Empty (not released yet added)
* [x] Grenade Callout (not released yet added)

## FAQ
- **How to Inspect ingame?**
  
Make a button and set the command as:
```
cl_inspect
```

- **How do i add Inspect and Empty Inspect in my v_model?**
  
Set a sequence inside the qc and firstly add `inspect` then `empty_inspect` at the end of sequence line.

- **How do i make camera movement working ingame?**

Just do the same tutorial as in the [CSLDR](https://github.com/mikkokko/csldr) readme.md

- **How to make Reload Empty work in my model?**
  
Just make an another sequence line from the bottom of empty inspect sequence

## Special Thanks:
- Bill FLX: Source Code
- MoeMod: Source Code
- TempoChannel: Source Code and Help
- Mikkoko: Cam Function Code (CSLDR)
- FWGS Team: Xash Client Port to Android
