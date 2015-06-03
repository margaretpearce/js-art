# js-art
JavaScript geometric art

I came across a blog post on [Replicating Art With JS] and wanted to do something similar just for fun. Rather than replicating existing artwork, I decided to start with an existing piece as inspiration and make my own variations. For these rainbow mosaics, I started with [this piece] in mind. The resulting HTML5/ JavaScript code is simple, but I liked playing with different color schemes and patterns. 

### Rainbow Mosaic 1
![Rainbow Mosaic 1](/screenshots/rainbowmosaic1.png?raw=true)

This was my first mosaic. I selected each hue using a squared Euclidean distance from the upper left corner, which creates the rounded gradient appearance.

### Rainbow Mosaic 2
![Rainbow Mosaic 2](/screenshots/rainbowmosaic2.png?raw=true)

Next, I thought of counting each square starting from the upper left hand corner and moving across the columns from left to right and the rows from top to bottom. The result is a horizontal gradient rainbow.

### Rainbow Mosaic 3
![Rainbow Mosaic 3](/screenshots/rainbowmosaic3.png?raw=true)

Extending the first mosaic, I added in the triangles on each square to mimic the original artwork. I made the triangles with a lower luminance value to increase the contrast.

### Rainbow Mosaic 4
![Rainbow Mosaic 4](/screenshots/rainbowmosaic4.png?raw=true)

This mosaic uses the same approach as mosaic #3 but using the original square coloring from mosaic #2. The triangles appear more connected to me and makes me think of the Triforce in Ocarina of Time.

### Rainbow Mosaic 5
![Rainbow Mosaic 5](/screenshots/rainbowmosaic5.png?raw=true)

Finally, mosaic #5 builds off of #3 but with random offsets on the triangle hue, saturation, and luminance. I tried to match the variance of the saturation and luminance in the origianl artwork.

### Rainbow Mosaic 6
![Rainbow Mosaic 6](/screenshots/rainbowmosaic6.png?raw=true)

This is my favorite of all six mosaics. It's using the random offset approach of #5 applied to the style of #4. I think this is the closest mosaic to the original artwork, but the colors are more on the neon side and not exactly grouped in the same way.


The mosaics were a fun weeknight project - try it out!

[Replicating Art With JS]: http://jsart.co/11/replicating-art-with-js/
[this piece]: http://40.media.tumblr.com/tumblr_ltixo8Fyqb1qbt59oo1_500.jpg
