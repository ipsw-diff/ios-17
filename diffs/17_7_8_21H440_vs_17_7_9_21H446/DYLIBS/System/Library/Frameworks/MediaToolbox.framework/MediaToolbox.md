## MediaToolbox

> `/System/Library/Frameworks/MediaToolbox.framework/MediaToolbox`

```diff

-3115.7.1.101.3
-  __TEXT.__text: 0x82f880
-  __TEXT.__stubs: 0x84cc
+3115.7.1.101.6
+  __TEXT.__text: 0x82fbe0
+  __TEXT.__stubs: 0x84e4
   __TEXT.__objc_methlist: 0x193c
   __TEXT.__cstring: 0x5608f
   __TEXT.__oslogstring: 0x3a385

   __TEXT.__objc_methname: 0x596e
   __TEXT.__objc_methtype: 0x236b
   __TEXT.__objc_stubs: 0x5240
-  __DATA_CONST.__got: 0x88b8
+  __DATA_CONST.__got: 0x88c8
   __DATA_CONST.__const: 0x4a810
   __DATA_CONST.__cfstring: 0x45a80
   __DATA_CONST.__objc_classlist: 0x1d0

   - /usr/lib/libc++.1.dylib
   - /usr/lib/libnetwork.dylib
   - /usr/lib/libobjc.A.dylib
-  Functions: 20492
-  Symbols:   36837
+  Functions: 20493
+  Symbols:   36840
   CStrings:  17572
 
Symbols:
+ _FigServer_IsReadOnlyFileOpeningPermittedForAuditToken
+ __CFURLIsFileURL
+ _mutableCompositionServer_checkSourceURLAccess
Functions:
~ _HandleMutableCompositionMessage : 1708 -> 1732
~ _HandleMutableCompositionGetTrackCompatibleWithAssetTrackMessage : 208 -> 244
~ _HandleMutableCompositionSetTrackEditListMessage : 388 -> 464
~ _HandleMutableCompositionAddFormatReaderForURLMessage : 184 -> 212
~ _HandleMutableCompositionInsertAssetSegmentIntoTrackMessage : 404 -> 428
~ _HandleMutableCompositionInsertSegmentArrayIntoTrackMessage : 764 -> 796
~ _HandleMutableCompositionAddAssetForURLMessage : 180 -> 208
~ _CreateServedMutableCompositionState : 276 -> 280
+ _mutableCompositionServer_checkSourceURLAccess
~ _HandleAssetMessage : 4076 -> 4184
~ _AddChunkToTrack : 552 -> 560
~ _CreateAVISampleCursor : 452 -> 476
~ _AVISampleCursorStepByDecodeTime : 232 -> 236
~ _AVISampleCursorCopyChunkDetails : 316 -> 384
~ _AVISampleCursorStepInDecodeOrderAndReportStepsTaken : 416 -> 480
~ _AVISampleCursorStepInPresentationOrderAndReportStepsTaken : 24 -> 4
~ _HandleMutableMovieMessage : 2212 -> 2396
~ _FigOctaviaCPECryptorCopyFormattingDesc : 12 -> 16
```
