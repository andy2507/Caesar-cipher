# Caesar-cipher
Caesar cipher is a popular substitution cipher wherein every letter of the alphabet is mapped to another letter given by a shift value. 
For example if the shift is 3, a is mapped to d (d is 3 letters after a), b to e etc. 
In this repo I have written functions to generate the cipher given text. I have also provided functions to decipher the cipher using popular techniques which are briefly discussed below

# Brute force
In this method of deciphering, the cipher text is analysed for each value of shift and n grams computed. The n grams are checked to see if they form legible words. If the n grams form legible words, then we have arrived at the cipher. This method works if the text is of a smaller size

# Frequency analysis
In this method of deciphering, the frequency of the letters in the cipher and a regular standard text is compared. The comparison that gives the least error is the shift. This works only if the text is sufficiently large.

Wikipedia Link:  https://en.wikipedia.org/wiki/Caesar_cipher

Huge shoutout to Simon Singh and his book, "The Code Book" which got me interested in cryptography! 