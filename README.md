# AsusWRT R3G
This is modified version of AsusWrt that works with Xiaomi Mi R3G router.

## How to install
1. Download image from Releases or build it from source
2. Flash it to router from Breed bootloader or AsusWRT. If you flash manually, TRX image needs to be placed at 0x200000

## How to build
1. cd release/src-ra-5010
2. make rt-mir3g

## Important notes
- First boot after takes some minutes, don't interrupt it

## Missing features
- No repeater support
- No dual-wan support

## TODO
1. Do some tests of Guest WiFi
2. Do some tests of IPTV page
