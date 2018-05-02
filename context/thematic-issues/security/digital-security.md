
## Digital Security

### Context

Photos seem fairly innocent but, as is the case with just about everything on the web, there's a slightly sinister side. 

With the advent of 'smart' devices, phone camera photos and increasingly also 'pro-level' cameras, ditigal photographs are encoded with 'meta-data.' EXIF data, commonly found in digital photography, .

EXIF data is metadata added to an image file by the device taking the photo.

Many smartphone and other mobile devices add GPS latitude and longitude to as  EXIF metadata. Data include timestamp information of the date that photo was taken. A savvy person can find out where a photo was taken and when.  

> The idea that someone could learn where your family loves to go out for dinner or do any other activity based on a photo is unsettling to say the least.
<div align="right">- [David Walsh](https://davidwalsh.name/exif-data)</div>

To see how this may affect you in practice, check out these two tools:

* [Eric Nicolas' Photo Localizer](https://beta.observablehq.com/@ccjmne/photos-viewer)
    - Load geotagged pictures and visualize their position in the globe.
* [Hiroaki Matoba's PiEXIF](https://github.com/hMatoba/piexifjs/blob/master/docs/about.rst)
    - Get a read of all EXIF data associated with a photo.

### Tools for Modifying EXIF data

For those interested in maintaining confidentiality, it is important to ensure sensitive EXIF data is wiped clean before published. Tools designed to help manipulate EXIF data include:


* [exiftool](https://sno.phy.queensu.ca/~phil/exiftool/)
    - Check out [David Walsh's](https://davidwalsh.name/exif-data) tutorial on removing EXIF data using `exiftool`

* [no-exif](https://www.npmjs.com/package/no-exif)
    - Remove Exif and GPS location data from JPEG images and create new files with the .noexif.jpg extension while preserving the original files and filenames.



<!--
    References:

> - [David Walsh ](https://davidwalsh.name/exif-data)

-->
