# WebFlash

This is a WebUSB based Nura flasher. It tries to guess which device is
attached by probing fastboot and shows a dropdown if the result is inconclusive.

The images are fetched from images.nura.eco and decompressed with xzwasm.

## License

This code is licensed as GPL3

It uses the sparse file decoder/encoder from [fastboot.js](https://github.com/kdrag0n/fastboot.js)
and [xzwasm](https://github.com/SteveSanderson/xzwasm) for uncompressing the .xz images.
