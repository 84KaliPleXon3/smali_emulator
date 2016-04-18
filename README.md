# Smali Emulator

This software will emulate a **smali** source file generated by apktool, it is intended to be used as a quick and dirty way to defeat various types of encryption and obfuscation while reversing an APK.

You'll find some examples in the `tests` folder of this project.

[Explanation of the "why" and "how" can be found here.](https://www.evilsocket.net/2016/04/18/how-i-defeated-an-obfuscated-and-anti-tamper-apk-with-some-python-and-a-home-made-smali-emulator/)

#### Note

This is highly experimental, a very small subsets of Dalvik opcodes are currently emulated, see the `smali/opcodes.py` file for more details.

#### License

Copyright (c) 2016 Simone Margaritelli | [Twitter](https://twitter.com/evilsocket) | [Blog](http://www.evilsocket.net)  
Released under the GPL 3 license.
