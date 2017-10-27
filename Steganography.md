# Steganography tools

Steganography is the art of hiding secret data inside other, plainly visible data. It can be useful when sending a secret message while trying to avoid arousing suspicion. It should never be used as a replacement for strong encryption, in practice, but CTFs often have stego only challenges. Often the easiest way to crack basic stego challenges is to just run a bunch of off-the-shelf tools over the file and see if the find any plaintext.

* [Steghide](http://steghide.sourceforge.net) - Steghide is a steganography program that is able to hide data in various kinds of image- and audio-files. The color- respectivly sample-frequencies are not changed thus making the embedding resistant against first-order statistical tests.
* [zsteg](https://github.com/zed-0xff/zsteg) - detect stegano-hidden data in PNG & BMP
* [exiftool](https://sno.phy.queensu.ca/~phil/exiftool/) - Not strictly a stego tool, but useful to view EXIF data for clues.
* [binwalk](https://github.com/devttys0/binwalk) - Analyze binaries for embedded data streams.
* [foremost](http://foremost.sourceforge.net/) - Foremost is a console program to recover files based on their headers, footers, and internal data structures. This process is commonly referred to as data carving.
* [p=np stego](https://pequalsnp-team.github.io/cheatsheet/steganography-101) - great walkthrough of stego techniques
