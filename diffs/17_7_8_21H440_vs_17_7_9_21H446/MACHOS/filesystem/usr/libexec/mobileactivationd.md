## mobileactivationd

> `/usr/libexec/mobileactivationd`

### Sections with Same Size but Changed Content

- `__TEXT.__objc_methlist`
- `__TEXT.__unwind_info`
- `__TEXT.__eh_frame`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA.__data`

```diff

-921.140.2.0.0
-  __TEXT.__text: 0x1ecdbc
+921.140.2.701.1
+  __TEXT.__text: 0x1ecde4
   __TEXT.__stubs: 0xda4
   __TEXT.__objc_stubs: 0x2de0
   __TEXT.__objc_methlist: 0x9fc
-  __TEXT.__const: 0x3ec11
-  __TEXT.__cstring: 0xd8c1
+  __TEXT.__const: 0x3f1a1
+  __TEXT.__cstring: 0xd8d3
   __TEXT.__objc_methname: 0x3be7
   __TEXT.__oslogstring: 0xd6b
   __TEXT.__objc_classname: 0x1a1

   __TEXT.__unwind_info: 0xe54
   __TEXT.__eh_frame: 0xa0
   __DATA_CONST.__got: 0xc20
-  __DATA_CONST.__const: 0xc8e0
+  __DATA_CONST.__const: 0xce00
   __DATA_CONST.__cfstring: 0xbd20
   __DATA_CONST.__objc_classlist: 0x48
   __DATA_CONST.__objc_catlist: 0x18

   - /usr/lib/liblockdown.dylib
   - /usr/lib/libobjc.A.dylib
   Functions: 1209
-  Symbols:   3075
+  Symbols:   3091
   CStrings:  2728
 
Symbols:
+ _ApplePlatformBackportECCRootG1
+ _ApplePlatformBackportECCRootG1PublicKey
+ _ApplePlatformBackportECCRootG1SKID
+ _ApplePlatformBackportECCRootG1SPKI
+ _ApplePlatformBackportRSARootG1
+ _ApplePlatformBackportRSARootG1PublicKey
+ _ApplePlatformBackportRSARootG1SKID
+ _ApplePlatformBackportRSARootG1SPKI
+ _TestApplePlatformBackportECCRootG1
+ _TestApplePlatformBackportECCRootG1PublicKey
+ _TestApplePlatformBackportECCRootG1SKID
+ _TestApplePlatformBackportECCRootG1SPKI
+ _TestApplePlatformBackportRSARootG1
+ _TestApplePlatformBackportRSARootG1PublicKey
+ _TestApplePlatformBackportRSARootG1SKID
+ _TestApplePlatformBackportRSARootG1SPKI
Functions:
~ _evaluateUCRTTrustWithCerts : 952 -> 932
~ _evaluateBAATrustWithCerts : 932 -> 912
~ _evaluateAccessoryTrustWithCerts : 956 -> 936
~ _X509PolicySetFlagsForRoots : 400 -> 480
~ _X509ChainCheckPathWithOptions : 1284 -> 1304
CStrings:
+ "921.140.2.701.1"
+ "Absinthe/2.0 iOS Device Activator (MobileActivation-921.140.2.701.1 built on Jun 30 2025 at 18:34:34)"
+ "iOS Device Activator (MobileActivation-921.140.2.701.1)"
- "921.140.2"
- "Absinthe/2.0 iOS Device Activator (MobileActivation-921.140.2 built on Jul 19 2024 at 09:50:59)"
- "iOS Device Activator (MobileActivation-921.140.2)"
```
