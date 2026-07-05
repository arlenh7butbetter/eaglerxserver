# EaglerXRewind for 1.3.2

EaglerXRewind is support for Eaglercraft 1.5.2 by translating the packets to 1.8 like ViaVersion

What this fork does, is support for Eaglercraft 1.3.2.

This fork registers Minecraft protocol `39`, which is the legacy protocol version used by 1.3.2, and rewrites packets between the 1.3.2 client format and the newer server/backend format.

## What This Does
 It allows people from my 1.3.2 port to join multiplayer servers a bit easier.

## Build

Run:

```build_all.bat``` to build every file with modified EaglerXRewind
**OR**
```gradlew rewind_v1_3:shadowJar``` to just generate EaglerXRewind.jar