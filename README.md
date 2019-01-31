# pie-gsi-builds
Builds from Pie-GSI. This is unofficial build from pie-gsi branch in AOSP.  To use it, simply download the release binaries needed for your device and flash with instruction from [DAC](https://developer.android.com/topic/generic-system-image/)
- source branch:  pei-gsi
- lunch menu:  aosp_arm64-userdebug, aosp_arm32-userdebug   ( x86 arch also supported )

| Vendor launch OS   |      lunch menu      |  note|
|----------|:-------------:|:------|
| Pie (API-28)|  aosp_arm64-userdebug, etc. | All Phones lauched with P are fully Treble compliant |
| O-MR1(API-27) | aosp_arm64_ab-userdebug, etc |   may not fully Treble compliant, need to use the legacy GSI |


Source Branch Migration:
```
  Code Change List( CLs ) ---> AOSP-master  --CherryPicked--> Pie-GSI branch
                                                                 ^
                                                                 |
  Some Internal Changes ( CLs) ----------------------------------+
 ```
 Theoretically, directly build from AOSP master branch is ok, in reality, your miles may vary.
