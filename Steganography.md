# Steganography tools

Steganography is the art of hiding secret data inside other, plainly visible data. It can be useful when sending a secret message while trying to avoid arousing suspicion. It should never be used as a replacement for strong encryption, in practice, but CTFs often have stego only challenges. Often the easiest way to crack basic stego challenges is to just run a bunch of off-the-shelf tools over the file and see if the find any plaintext.

* [Steghide](http://steghide.sourceforge.net) - Steghide is a steganography program that is able to hide data in various kinds of image- and audio-files. The color- respectivly sample-frequencies are not changed thus making the embedding resistant against first-order statistical tests.
