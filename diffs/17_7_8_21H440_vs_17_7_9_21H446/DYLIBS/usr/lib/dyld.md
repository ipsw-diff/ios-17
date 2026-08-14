## dyld

> `/usr/lib/dyld`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff
CStrings:
+ "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Fri Jul 11 17:33:51 PDT 2025; root:libignition-56~62436/libignition_core/RELEASE_ARM64"
+ "Darwin Ignition Sequence Version 1.0.0: Fri Jul 11 17:33:51 PDT 2025; root:libignition-56~62436/libignition_core/RELEASE_ARM64"
- "@(#)VERSION:Darwin Ignition Sequence Version 1.0.0: Thu May 15 20:29:37 PDT 2025; root:libignition-56~62065/libignition_core/RELEASE_ARM64"
- "Darwin Ignition Sequence Version 1.0.0: Thu May 15 20:29:37 PDT 2025; root:libignition-56~62065/libignition_core/RELEASE_ARM64"
```
