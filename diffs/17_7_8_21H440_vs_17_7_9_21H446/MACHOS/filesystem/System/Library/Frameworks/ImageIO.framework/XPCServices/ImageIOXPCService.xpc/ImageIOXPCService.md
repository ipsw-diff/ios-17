## ImageIOXPCService

> `/System/Library/Frameworks/ImageIO.framework/XPCServices/ImageIOXPCService.xpc/ImageIOXPCService`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-2488.12.1.0.0
-  __TEXT.__text: 0x3d0c98
+2488.13.1.0.0
+  __TEXT.__text: 0x3d0d74
   __TEXT.__stubs: 0x31a4
   __TEXT.__objc_stubs: 0xfc0
   __TEXT.__objc_methlist: 0x310
   __TEXT.__gcc_except_tab: 0x1fad8
   __TEXT.__const: 0x2d1f0
-  __TEXT.__cstring: 0x79073
+  __TEXT.__cstring: 0x79088
   __TEXT.__objc_methname: 0x1282
   __TEXT.__objc_classname: 0x3f
   __TEXT.__objc_methtype: 0x5f1

   - /usr/lib/libz.1.dylib
   Functions: 15661
   Symbols:   10803
-  CStrings:  12646
+  CStrings:  12648
 
Functions:
~ __ZN13JP2ReadPlugin27checkContinousCodestreamBoxEP10IIOScannery : 240 -> 232
~ sub_100192c74 -> sub_100192b90 : 888 -> 984
~ sub_100192fec -> sub_100192f68 : 800 -> 804
~ sub_100196a4c -> sub_1001969cc : 1328 -> 1444
~ sub_100196f7c -> sub_100196f70 : 1332 -> 1344
CStrings:
+ "%s %lld"
+ "Invalid skew"
```
