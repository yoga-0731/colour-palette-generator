# Image color palette generator
A fun and useful Python Flask application where we could upload an image and know the colour palette of that image.

## Functionality
  - Upload any image.
  - Using colorgram module, the colors are extracted. If colorgram is unable to extract the color, the closest color to the former is chosen.
  - Using webcolor module, all the extracted colors are converted to hex code.
  - Image and all colors from the image are displayed.
