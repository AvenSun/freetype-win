# Note

![demo for ](https://github.com/adesun/freetype-win/blob/master/demo/demo.jpg?raw=true)
1. slight modification to work with [freetype-py](https://github.com/rougier/freetype-py). just removed two lines below in raw.py
> FT_Get_BDF_Charset_ID          = _lib.FT_Get_BDF_Charset_ID
> FT_Get_BDF_Property            = _lib.FT_Get_BDF_Property

1. both win32 and x64 dll are supplied (v2.8.1).
1. dll compiled by VS2017,so you have to install Visual C++ 2017 runtime. ([win32](https://go.microsoft.com/fwlink/?LinkId=746571)    [x64](https://go.microsoft.com/fwlink/?LinkId=746572))
1. pick up correct dll according to your windows, drop it into python root or system path.
2. after finished all above,you can enjoy now !

