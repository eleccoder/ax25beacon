
## This is a generic (Arduino-free) library version of [Philip Heron's *ax25beacon*](https://github.com/fsphil/ax25beacon) project

Platform | Arch | Test Status
------------ | ------------ | -------------
Ubuntu Linux | x86_64 | Compiles & Runs
Raspberry Pi Pico | ARMv6 | Compiles (build environment not provided yet)
Raspberry Pi 3B+ & 4B | ARMv7l / ARMv8 | TBD

```
ax25beacon - Created by Philip Heron <phil@sanslogic.co.uk>

This simple command line program generates the audio tones for an
AX.25 packet for use on the APRS network. It encodes position, altitude
and an optional comment field.
```

I've taken some of [perplexinglysimple's pre-work](https://github.com/perplexinglysimple/ax25beacon).

### TODO (Aug 2021)

- [x] Provide an example executable
- [x] Complete testing on Raspberry Pi Pico
- [x] Provide the build environment for Raspberry Pi Pico
- [x] Testing on Raspberry Pi 3B+ and 4B
