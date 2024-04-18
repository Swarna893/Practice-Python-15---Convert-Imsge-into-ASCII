# Practice-Python-15---Convert-Imsge-into-ASCII

#import pywhatkit as kit

#kit.image_to_ascii_art("C:/Users/user/PycharmProjects/firstProg/me.jpg", "me_ascii.txt")


import ascii_magic

output = ascii_magic.from_image_file("C:/Users/user/PycharmProjects/firstProg/me.jpg", columns=300, char="#")
