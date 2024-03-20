The object (OBJ) file of the 3d logo (created with Vectary) is availbale in the directory as a [zip file](obj.zip).

Colors used for the plane:
  - `#fff`
  - `#e8e8e8`
  - `#f9f0ff`
  - `#888`
  - `transparent`

## Blender
Blender v3.0 is used.

The colors of the logo object's material can be changed from the *Material properties* -> *surface* -> *base colors*

The original blender version of logo was created by Mojtaba. I created a modified version of it.
My modified *.blend* file is packed with the environment asset (it can be unpacked from *File* -> *External data* -> *Unpack resources*).
The asset can also be downloaded from [here](https://polyhaven.com/a/photo_studio_01) in 2k resolution.
In either case, make sure the environment asset is assigned to world from
bottom panel -> *world* from dropdown -> as the photo of the first left node.

The render of my version had shadows that were too strong.

The *forest* environment (which is by defulat used in the *material* preview mode)
from Blender's default environments is also very good.
To see how to use it, see one of the vidoes from links below.

We can also unhide the plane object and its reflections will have effect especially on
the sides of the logo object.

We can create the logo without the shadows on plane but keeping reflections and effects of that otherwise exsisting shadow on the logo object.
To do this I selected all the options from *View layer properties* -> *passes* -> *light* section (the *data* section had only *combined* option selected).
See [this post](https://blender.stackexchange.com/q/16152).
To add subtle shadows to the object, combine it with a shdow only version of the render. See below for more information and links and how I did this in the old way.

Here is my old way that produced the logo with subtle shadows but without the reflections of the shadows on the object sides.
I created two versions:
  - One without shadows
  - One with only shadows
  - One with the original and shadow combined in Inkscape/photoshop (the shadow opacity was decreased)

How to keep the shadow with transparent or color background:
https://youtu.be/GIGKit1e3u8

Related videos and articles:
https://youtu.be/ChgoGr9V-tc
https://youtu.be/6HIqF_MSnvU
https://youtu.be/b0I-d5LJTL4
https://youtu.be/EN_xB9Fkw9M
https://youtu.be/mB0p1b1W3Rs
https://blenderartists.org/t/cycles-how-to-brighten-only-the-darkest-of-shadows-reduce-shadow-darkness/579332
https://blenderartists.org/t/control-the-amount-of-shadow-on-a-shadow-catcher/1274531/6

For more information see the mahozad.github.io repository.

## Adobe Dimension
Adobe Dimension 2020 did not support importing SVG images.
So, I imported the M logo in Vectary, extruded it and exported to *OBJ* format
and then used the object file in Adobe Dimension.
See the [procedure section below](#Procedure) for how to import SVG in Vectary.

## Cinema 4D
How to keep the shadow on a transparent or colored plane:
  - https://youtu.be/MXFYZhfI5yc
  - https://youtu.be/MpBGZDI_nT4
  - https://youtu.be/dWRM3WXGLD0

## [Vectary](https://www.vectary.com/) is an online tool.
Its legacy *Studio 3.0 (2020)* version is used.
The *Camera 1* is the one used for new photos.

### Procedure
First I modified the svg of my *M* logo and converted the strokes to paths in Inkscape.
Then I imported the svg into Vectary.
Then I selected *Geometery* button from right panel.
Then below that button, I extruded the shape to my desired value.
Then selected the result object and from *Library* tab on top left selected a material.
The color of the material can be changed in the right panel.
The color `#ffcd1a` seems to be a good choice.
Then I added a *Rectangle light* and positioned it in my desired place and resized it to be bigger.
(Actually the light is not needed at all. the Screenshot 13 to 17 did not use light at all).
Then I added a *SquarePlane* as the background plane of my object.

See [this YouTube video](https://youtu.be/oFt_eeGuhjo) from Vectary to learn more.

To change the plane color in Vectary, select it and change its color.
We can also change the color of environment by selecting *Object* tab on top left corner
and from right panel change the environment color.
