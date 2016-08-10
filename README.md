# Grafika

[![Build Status](https://travis-ci.org/kosinix/grafika.svg?branch=master)](https://travis-ci.org/kosinix/grafika)

An image processing library for PHP

## Unique Features

These are the features that makes Grafika unique from other libs:

- **Smart Crop** - Grafika can guess the crop position based on the image content where the most important regions are preserved.
- **Animated GIF Support** - It can resize animated GIFs on both GD and Imagick. On GD, Grafika uses its own GIF parser to do this.
- **5 Resize Modes** - Resize is a first class citizen in Grafika. Call them directly using resizeFit, resizeFill, resizeExact, resizeExactWidth, and resizeExactHeight or use the generic resize api.
- **Image Compare** - Find how similar two images are using perceptual hashes or check if they are exactly equal.
- **Advance Filters** - Sobel and Floyd-Steinberg Dithering. More will be added in future releases.
- **Bezier Curves** - Create anti-aliased quadratic and cubic beziers both on GD and Imagick.
- **Normalized API** - No need to worry about the differences between GD and Imagick API, Grafika normalizes these operations for you.

See documentation for more info.

## Documentation
[http://kosinix.github.io/grafika](http://kosinix.github.io/grafika)

## API: 
[http://kosinix.github.io/grafika/api](http://kosinix.github.io/grafika/api)

## Packagist
[https://packagist.org/packages/kosinix/grafika](https://packagist.org/packages/kosinix/grafika)

## License
- MIT License
