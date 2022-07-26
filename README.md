# BTA Example Mod - Babric

A simple mod template for Better Than Adventure, yet this template is for Babric.

Original version: https://github.com/pkstDev/BTAExampleMod

### Setup

Just run the following command:
```shell
gradlew build
```
And then you can start your modding trip!

### Extra Tips

* Since BTA is distributed without obfuscation, all Mixin classes must set the 'remap' option to false!
* We don't use Babric Loom to build, so JIJ dependencies are not usable for now!
