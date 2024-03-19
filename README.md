# Steganography

Steganography is the practice of hiding a secret message within (or on top of) something that is not secret. The message can be anything you want. 
Steganography involves embedding a secret piece of text inside of a picture or by hiding a secret message or script within a Word or Excel document.
The main motive of steganography is to hide the intended information within any file, usually an image, an audio file, or a video, without actually altering the external appearance of the file.

Let’s learn the technique for the same
● First,we need to keep track of ASCII codes.
● Second about image, Upload one image but it should be in png format, As we know Images are composed of digital data (pixels), which describe what's inside the picture, such as the color of each pixel. Every image is composed of pixels, and each pixel contains three values (red, green, blue).
● Third we must know about LSB (Least Significant Bit)LSB in which messages are hidden inside an image by replacing each pixel’s least significant bit with the bits of the message to be hidden
● Fourth, use encoding and decoding steganographic secret messages into a cover image file by using techniques like least significant bit encoding. The resulting stego image looks very similar to your cover image file, with no visible changes. This completes encoding. To retrieve the secret message, we will use a decoding process

