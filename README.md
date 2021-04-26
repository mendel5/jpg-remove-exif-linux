# jpg-remove-exif-linux
How to remove a .jpg file's EXIF metadata with exiftools in a Linux terminal

```
sudo apt-get install libimage-exiftool-perl

exiftool -all= *.jpg

exiftool -all= *.JPG

exiftool -all= foo.jpeg

```


Sources:
- https://askubuntu.com/questions/260810/how-can-i-read-and-remove-meta-exif-data-from-my-photos-using-the-command-line
- https://stackoverflow.com/questions/2654281/how-to-remove-exif-data-without-recompressing-the-jpeg
- https://www.linux-magazine.com/Online/Blogs/Productivity-Sauce/Remove-EXIF-Metadata-from-Photos-with-exiftool
- https://www.linux-magazine.com/Online/Blogs/Productivity-Sauce/Remove-EXIF-Metadata-from-Photos-with-exiftool
