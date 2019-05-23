# ImageMagick

## Splicing Images together

### Horizontally

`convert +append 1.jpg 2.jpg out.jpg`

### Vertically

`convert -append 1.jpg 2.jpg out.jpg`


## Add a border to an image

`-splice` flag

http://www.imagemagick.org/Usage/crop/#splice

`convert in.jpg -background grey -splice 10x0 -gravity east out.jpg`
