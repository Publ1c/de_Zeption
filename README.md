# de_Zeption
Nested password-protected zip file have you down in a CTF? Dream a little bigger...

BLUF:
Dev'd a quick python script to solve a problem-set from a HTB challenge. 

Problem:
Problem consisted of a highly nested zip file with password protection. Each zip file had an associated img file with a displayed password.

Method:
Used pil to analyze each image file, pixel by pixel for message, decoded it and used zipfile module to unzip with newly decoded password.

Keywords:
Python, recursion, pil, zipfile, os, sys
