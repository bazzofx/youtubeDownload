#Download Youtube Music & Videos from youtube
#


#Pytube module is broken below fix must be apply as of 20th Oct, 2024

To Fix:
Change in Cipher.py
https://github.com/pytube/pytube/issues/1707
Line 272 & 273 to :
r'a\.[a-zA-Z]\s*&&\s*\([a-z]\s*=\s*a\.get\("n"\)\)\s*&&.*?\|\|\s*([a-z]+)',
r'\([a-z]\s*=\s*([a-zA-Z0-9$]+)(\[\d+\])\([a-z]\)',