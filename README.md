# play_with_oneplus7pro

[here is my blog in Chinese](https://o0xmuhe.github.io/2022/11/01/Qual-Android%E6%96%B9%E6%A1%88Unlock%E5%AD%A6%E4%B9%A0-%E4%BB%A5Oneplus7Pro%E4%B8%BA%E4%BE%8B/)

## firehose

Extract from Oneplus 7Pro factory firmware by ops extractor.


## patch.diff

Edl(with tag 3.52.1)patch for support guacamole, I use hardcode for projid and set property prodkey after I analysis the flash tool(msmdownloadtoolv4.0.88.exe).

After apply this patch(or modify edl's source code), you can flash Oneplus7Pro with edl :) Enjoy


# reference

[How to Extract/Decrypt OnePlus OPS Firmware](https://www.droidwin.com/how-to-extract-oneplus-ops-firmware/)
[Qualcomm Sahara / Firehose Attack Client / Diag Tools](https://github.com/bkerler/edl)
