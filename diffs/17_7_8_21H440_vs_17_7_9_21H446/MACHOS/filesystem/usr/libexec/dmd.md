## dmd

> `/usr/libexec/dmd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__unwind_info`
- `__DATA_CONST.__const`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-191.0.0.0.0
+191.1.0.0.0
   __TEXT.__text: 0x75cf0
   __TEXT.__stubs: 0xb10
   __TEXT.__objc_stubs: 0xe1e0
   __TEXT.__objc_methlist: 0x6de0
-  __TEXT.__const: 0x128
+  __TEXT.__const: 0x130
   __TEXT.__cstring: 0x5282
   __TEXT.__objc_classname: 0x1dc9
   __TEXT.__objc_methname: 0x10f79
```
