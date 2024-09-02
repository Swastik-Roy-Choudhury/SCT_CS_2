AUTHOR-SWASTIK ROY CHOUDHURY,This program reads an image, alters its pixel values by performing operations such as XORing with a key or swapping channels, and outputs the encrypted image. The same process is reversed to decrypt the image back to its original form, making it a basic form of image obfuscation.

EXAMPLE OF CODE INPUT & OUTPUT
1)Install the required library using pip
pip install pillow
2)Place your input image (input_image.jpg) in the same directory.
3)Run the script:python image_encryption.py
The script will generate an encrypted_image.png and a decrypted_image.png. The encrypted image will look different from the original due to pixel manipulation, but the decrypted image should be visually identical to the original.


