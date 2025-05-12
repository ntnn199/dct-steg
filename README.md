# dct-steg
#This lab using DCT algorithm for hiding information in images
#Step 1, You need to prepare the photo and message to hide. Save as "cover.jpg" and "mess.txt"
#Step 2, Read cover.jpg image, extract DCT coefficients and save to binary file dct_coeff.bin
#In step 2, your code will compile as "extract", and run it by ./extract
#Step 3, Write a program to read mess.txt, embed it in dct_coeff.bin to create stego_coeff.bin, complie code as "embed" and run by ./embed
#Step 4, create code to recreate the image and compile it to restruct, jpg in this step save as "steg.jpg"
#Step 5, you extract message from image by the complie code name as "extractmess", and compare 2 message, run: ./extractmess
#Step 6, you send "steg.jpg" to your other PC, compile it to "send".
