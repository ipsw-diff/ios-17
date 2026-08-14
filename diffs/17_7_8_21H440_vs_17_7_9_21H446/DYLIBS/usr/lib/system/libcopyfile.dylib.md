## libcopyfile.dylib

> `/usr/lib/system/libcopyfile.dylib`

```diff

-196.120.5.0.0
-  __TEXT.__text: 0x696c
+196.120.5.702.1
+  __TEXT.__text: 0x69fc
   __TEXT.__stubs: 0x4b0
   __TEXT.__const: 0x1f0
-  __TEXT.__cstring: 0x17b2
+  __TEXT.__cstring: 0x17fa
   __TEXT.__unwind_info: 0xb8
   __DATA_CONST.__got: 0x338
   __DATA_CONST.__const: 0x450

   - /usr/lib/system/libxpc.dylib
   Functions: 32
   Symbols:   148
-  CStrings:  177
+  CStrings:  179
 
Functions:
~ _copyfile_open : 2696 -> 2840
CStrings:
+ "file %s changed behind our feet: %m"
+ "fstat on open fd failed for %s\n: %m"
```
