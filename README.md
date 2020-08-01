# Image Manipulation Tests

[PinTrader.club](https://pintrader.club) needed a way of allowing users to

- Upload massive images from their phones, without taking up too much resource
- Rotate images that sometimes were uploaded "wrong" (due to misreading of EXIF, or just weirdly taken pics)

We initially used Croppie.js to achieve this, but the results were often sub-par, with bits of the image getting cropped off, or white space being left around the image. [PinTrader.club](https://pintrader.club) needs to be easy to use by everyone, we can't assume uploaders will take the time to learn our cropping tool.

This repo contains a series of experiments in playing with large images with a `canvas` element. All the examples live in the single file, `index.html`