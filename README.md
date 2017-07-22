# APK Decompiler
A python based application that uses external tools to decompile Android APK's. Extracting the JAVA source code, manifest, assets, etc.

# Usage
```
python3 apk_decompiler.py -a example.apk
```

```
usage: apk_decompiler.py [-h] -a APK [-o OUTPUT_DIR] [-v]

optional arguments:
  -h, --help            show this help message and exit
  -a APK, --apk APK     Apk file
  -o OUTPUT_DIR, --output-dir OUTPUT_DIR
                        Output directory
  -v, --verbose         Enables verbose '''
```

# Used Tools
This project couldn't be made without this awesome tools
- [pxb1988/dex2jar](https://github.com/pxb1988/dex2jar)
- [iBotPeaches/Apktool](https://ibotpeaches.github.io/Apktool/install/)
- [kwart/jd-cmd](https://github.com/kwart/jd-cmd)

# License
[GNU General Public License v2.0](LICENSE.md)

# Donations
Bitcoin address: **16mCUENGwoXH77tPYiHUHT3MtjcFgbHRKs**
