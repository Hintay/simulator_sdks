# Simulator SDKs
This repository contains patched iPhone Simulator SDKs containing private symbols. These were removed from official SDKs starting in Xcode 7.3 and the iOS 9.3 SDK.

To use with [Theos](https://github.com/theos/theos) and [simject](https://github.com/angelXwind/simject), [download this repo](https://github.com/Hintay/simulator_sdks/archive/master.zip), extract, and copy whichever SDKs you desire into `$THEOS/sdks/`.

Generated using [create_patched_sdk.sh](create_patched_sdk.sh) and inoahdev’s [tbd v2.0.0-alpha3](https://github.com/inoahdev/tbd/releases/tag/v2.0.0-alpha3) using binaries retrieved from the dyld shared cache.
