## KeychainCircle

> `/System/Library/PrivateFrameworks/KeychainCircle.framework/KeychainCircle`

```diff

-61123.142.1.701.4
-  __TEXT.__text: 0x19920
+61123.142.1.701.6
+  __TEXT.__text: 0x19ee4
   __TEXT.__stubs: 0x6a8
-  __TEXT.__objc_methlist: 0x167c
+  __TEXT.__objc_methlist: 0x16f4
   __TEXT.__const: 0x74
-  __TEXT.__gcc_except_tab: 0xafc
-  __TEXT.__cstring: 0x1a70
-  __TEXT.__oslogstring: 0x2ac7
+  __TEXT.__gcc_except_tab: 0xb68
+  __TEXT.__cstring: 0x1ae4
+  __TEXT.__oslogstring: 0x2b75
   __TEXT.__ustring: 0x32
   __TEXT.__dlopen_cstrs: 0xfc
   __TEXT.__unwind_info: 0x5f0
-  __TEXT.__objc_classname: 0x2e2
-  __TEXT.__objc_methname: 0x3589
-  __TEXT.__objc_methtype: 0xdef
-  __TEXT.__objc_stubs: 0x2740
+  __TEXT.__objc_classname: 0x2e4
+  __TEXT.__objc_methname: 0x3657
+  __TEXT.__objc_methtype: 0xdff
+  __TEXT.__objc_stubs: 0x27e0
   __DATA_CONST.__got: 0x4f0
   __DATA_CONST.__const: 0x9e8
-  __DATA_CONST.__cfstring: 0x1da0
+  __DATA_CONST.__cfstring: 0x1e20
   __DATA_CONST.__objc_classlist: 0xa8
   __DATA_CONST.__objc_catlist: 0x20
   __DATA_CONST.__objc_protolist: 0x38
   __DATA_CONST.__objc_imageinfo: 0x8
-  __DATA_CONST.__objc_const: 0x2c98
-  __DATA_CONST.__objc_selrefs: 0xc50
+  __DATA_CONST.__objc_const: 0x2d58
+  __DATA_CONST.__objc_selrefs: 0xc80
   __DATA_CONST.__objc_protorefs: 0x8
   __DATA_CONST.__objc_classrefs: 0x120
   __DATA_CONST.__objc_superrefs: 0x88
   __DATA_CONST.__objc_arraydata: 0x60
   __DATA_CONST.__objc_dictobj: 0xc8
   __DATA_CONST.__objc_intobj: 0x30
-  __DATA.__objc_ivar: 0x1a0
+  __DATA.__objc_ivar: 0x1b0
   __DATA.__objc_data: 0x640
   __DATA.__data: 0x2c8
   __DATA.__bss: 0x90

   - /usr/lib/libSystem.B.dylib
   - /usr/lib/libcompression.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 560
-  Symbols:   1553
-  CStrings:  1199
+  Functions: 570
+  Symbols:   1572
+  CStrings:  1216
 
Symbols:
+ -[KCJoiningAcceptSession piggybacking_version_for_tests]
+ -[KCJoiningAcceptSession setPiggybackingVersion:]
+ -[KCJoiningAcceptSession setPiggybacking_version_for_tests:]
+ -[KCJoiningRequestCircleSession piggybacking_version_for_tests]
+ -[KCJoiningRequestCircleSession setPiggybackingVersion:]
+ -[KCJoiningRequestCircleSession setPiggybacking_version_for_tests:]
+ -[OTPairingMessage hasVersion]
+ -[OTPairingMessage setHasVersion:]
+ -[OTPairingMessage setVersion:]
+ -[OTPairingMessage version]
+ GCC_except_table242
+ GCC_except_table289
+ GCC_except_table292
+ GCC_except_table407
+ GCC_except_table413
+ GCC_except_table476
+ GCC_except_table499
+ _OBJC_IVAR_$_KCJoiningAcceptSession._piggybacking_version_for_tests
+ _OBJC_IVAR_$_KCJoiningRequestCircleSession._piggybacking_version_for_tests
+ _OBJC_IVAR_$_OTPairingMessage._has
+ _OBJC_IVAR_$_OTPairingMessage._version
+ ___block_descriptor_56_e8_32s40r48r_e74_v56?0"NSString"8"NSData"16"NSData"24"NSData"32"NSData"40"NSError"48lr40l8s32l8r48l8
+ _objc_msgSend$hasVersion
+ _objc_msgSend$piggybacking_version_for_tests
+ _objc_msgSend$setPiggybacking_version_for_tests:
+ _objc_msgSend$setVersion:
+ _objc_msgSend$version
- GCC_except_table238
- GCC_except_table284
- GCC_except_table287
- GCC_except_table399
- GCC_except_table400
- GCC_except_table466
- GCC_except_table489
- ___block_descriptor_48_e8_32r40r_e74_v56?0"NSString"8"NSData"16"NSData"24"NSData"32"NSData"40"NSError"48lr32l8r40l8
CStrings:
+ "Failed to create circle blob response message"
+ "TQ,N,V_piggybacking_version_for_tests"
+ "TQ,N,V_version"
+ "Unexpected piggybacking version"
+ "_piggybacking_version_for_tests"
+ "_version"
+ "failed to decrypt voucher packet, fall back to legacy path, error: %@"
+ "failed to encrypt the voucher"
+ "hasVersion"
+ "joining: failed to encrypt voucher payload: %@"
+ "joining: unexpected piggybacking version, received: %llu"
+ "piggybacking_version_for_tests"
+ "setHasVersion:"
+ "setPiggybacking_version_for_tests:"
+ "setVersion:"
+ "version"
+ "{?=\"version\"b1}"
```
