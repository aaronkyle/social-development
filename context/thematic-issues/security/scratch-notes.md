


## Digital Security

You've probably uploaded photos to social media, sent photos to friends and family, and so on.  Photos seem fairly innocent but, as is the case with just about everything on the web, there's a slightly sinister side to images on the web -- a privacy, even security issue with EXIF data.

EXIF data is metadata added to an image file by the device taking the photo.  For instance, any devices add GPS latitude and longitude to the EXIF metadata, as well as date the photo was taken, providing a savvy person a way to find out where a photo was taken and when.  The idea that someone could learn where your family loves to go out for dinner or do any other activity based on a photo is unsettling to say the least.

For those interested in maintaining the confidentiality, we have a responsibility to make sure sensitive EXIF data is wiped clean before published for the world to see.

Don't belive me?  Check this out:

https://beta.observablehq.com/@ccjmne/photos-viewer


Tools for doing this:

* [exiftool](https://sno.phy.queensu.ca/~phil/exiftool/)



* [no-exif](https://www.npmjs.com/package/no-exif)
    - Remove Exif and GPS location data from JPEG images and create new files with the .noexif.jpg extension while preserving the original files and filenames.

