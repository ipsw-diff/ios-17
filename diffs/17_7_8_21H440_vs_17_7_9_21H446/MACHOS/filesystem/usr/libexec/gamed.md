## gamed

> `/usr/libexec/gamed`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__const`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__swift5_typeref`
- `__TEXT.__constg_swiftt`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__got`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__objc_data`
- `__DATA.__data`

```diff

-818.6.8.2.1
-  __TEXT.__text: 0x1c90d4
+818.6.8.2.2
+  __TEXT.__text: 0x1c9194
   __TEXT.__stubs: 0x1dc4
   __TEXT.__objc_stubs: 0x1a180
   __TEXT.__objc_methlist: 0xba7c
   __TEXT.__objc_classname: 0x1e93
-  __TEXT.__oslogstring: 0x12810
+  __TEXT.__oslogstring: 0x1285d
   __TEXT.__const: 0x10c80
   __TEXT.__gcc_except_tab: 0x297c
   __TEXT.__cstring: 0x1ad34

   __TEXT.__swift5_mpenum: 0x8
   __TEXT.__swift5_assocty: 0x60
   __TEXT.__swift5_protos: 0x18
-  __TEXT.__unwind_info: 0x6ca0
+  __TEXT.__unwind_info: 0x6c9c
   __TEXT.__eh_frame: 0x2b88
   __DATA_CONST.__got: 0x2520
   __DATA_CONST.__const: 0x100a0

   - /usr/lib/swift/libswiftsimd.dylib
   Functions: 8880
   Symbols:   1562
-  CStrings:  9972
+  CStrings:  9973
 
Functions:
~ sub_1000f47c8 -> sub_1000f46a8 : 228 -> 420
CStrings:
+ "For bundleID: %@ we are returning playerInternal with ID: %@ in auth reponse"
```
