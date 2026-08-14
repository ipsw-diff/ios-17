## AudioCodecs

> `/System/Library/Frameworks/AudioToolbox.framework/AudioCodecs`

### Sections with Same Size but Changed Content

- `__TEXT.__cstring`

```diff

-696.7.6.0.0
-  __TEXT.__text: 0x55a2bc
+696.7.8.0.0
+  __TEXT.__text: 0x55a4c0
   __TEXT.__stubs: 0xfd8
   __TEXT.__const: 0x314e60
   __TEXT.__gcc_except_tab: 0xc668
-  __TEXT.__oslogstring: 0x161e0
+  __TEXT.__oslogstring: 0x16241
   __TEXT.__cstring: 0xa250
   __TEXT.__ustring: 0x60
   __TEXT.__unwind_info: 0x9640

   - /usr/lib/libc++.1.dylib
   Functions: 9518
   Symbols:   16027
-  CStrings:  2947
+  CStrings:  2949
 
Functions:
~ __ZN4apac25APACAncillaryFrameDecoder11DecodeFrameER16TBitstreamReaderIjERNSt3__16vectorINS_15ASCAudioOutDataENS4_9allocatorIS6_EEEENS_9FrameTypeE : 3340 -> 3348
~ __ZN13sceneposition8Position11DeserializeER16TBitstreamReaderIjEb : 2276 -> 2500
~ __ZN13sceneposition12ItemPosition11DeserializeER16TBitstreamReaderIjEb : 36 -> 56
~ __ZN4apac15AncillaryConfig11DeserializeER16TBitstreamReaderIjEjjjb : 17356 -> 17432
~ __ZN14metadata_bsfmt12RendererData11DeserializeER16TBitstreamReaderIjEb : 14060 -> 14124
~ __ZN6mpddrc21DrcInstructionsUniDrc15DeriveExtraInfoEjjjRNSt3__16vectorINS_19DownmixInstructionsENS1_9allocatorIS3_EEEEiRKNS2_INS_21DrcCoefficientsUniDrcENS4_IS8_EEEEiRKNS_28DrcCoefficientsParametricDrcERKNS2_INS_25ParametricDrcInstructionsENS4_ISG_EEEE : 7676 -> 7800
CStrings:
+ "%25s:%-5d ERROR: array size exceeded.\n"
+ "%25s:%-5d Error: Cannot parse Position extension payload\n"
+ "18:47:03"
+ "Jul 10 2025"
- "13:13:04"
- "Apr 15 2025"
```
