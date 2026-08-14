## libxslt.1.dylib

> `/usr/lib/libxslt.1.dylib`

```diff

-20.5.0.0.0
-  __TEXT.__text: 0x2155c
-  __TEXT.__stubs: 0xa38
-  __TEXT.__cstring: 0x716b
+20.7.0.0.0
+  __TEXT.__text: 0x218a4
+  __TEXT.__stubs: 0xa44
+  __TEXT.__cstring: 0x71c7
   __TEXT.__const: 0x17c
-  __TEXT.__unwind_info: 0x4b0
-  __DATA_CONST.__got: 0x738
+  __TEXT.__unwind_info: 0x4c0
+  __DATA_CONST.__got: 0x740
   __DATA_CONST.__const: 0x248
   __DATA.__data: 0x28
   __DATA.__bss: 0x461

   __DATA_DIRTY.__bss: 0x40
   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libxml2.2.dylib
-  Functions: 383
-  Symbols:   658
-  CStrings:  891
+  Functions: 386
+  Symbols:   662
+  CStrings:  893
 
Symbols:
+ _xmlCopyDoc
+ _xsltCleanupSourceDoc
+ _xsltRVTListCreate
+ _xsltReleaseRVTList
CStrings:
+ "%s: file %s line %ld\n"
+ "%s: file %s line %ld element %s\n"
+ "document() : failed to copy style doc\n"
+ "document() : failed to create xsltDocument\n"
+ "xsltRVTListCreate: malloc failed\n"
- "%s: file %s line %d\n"
- "%s: file %s line %d element %s\n"
- "localRVT not head of list\n"
```
