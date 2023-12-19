# TRYHACKME.COM - PEANUT BUTTER IS GOOD CTF
https://tryhackme.com/room/peanutbutterisgood

## TASK 1
Retrieve the flag hidden inside an image, somewhere on the website.

- __Step 1__ - Retrieve the directory list with an enumeration software (e.g. Dirbuster) loaded with a wordlist.
- __Step 2__ - Check the discoveries until finding NOTHING_HERE.html inside the /search directory.
- __Step 3__ - Check the source code of the fake error page to find an hidden image.
- __Step 4__ - Either download the image with wget or unhidden it by modifying the CSS code and save it.
- __Step 5__ - Use a stegano software (i.e. Steghide or Aperisolve) to find the flag.txt file.
- __Step 6__ - Decode the base64 encoded flag twice to retrieve it.

__ANSWER #1__ : FLAG{This_cat_is_probably_named_Jean}
