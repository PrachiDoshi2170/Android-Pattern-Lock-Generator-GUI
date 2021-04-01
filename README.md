# Android-Pattern-Lock-Generator-GUI
Java Android Pattern Lock Generator GUI is a short project carried out to provide you with 2 lakh combinations of various lock patterns for your phone.
Android phones have various locking mecahnism to support the privacy of the user. One of the very famous locking mechanism is to generate a pattern lock. Andoird pattern lock is 3x3 matrix pattern which 9 distinct dots on you screen. Now to generate a successul pattern, the user need tos follow 3 simple rules :-
1. The smallest pattern should atleast connect 4 distinct dots.
2. The largest pattern has combination of 9 distinct dots.
3. While creating the pattern, user cannot visit the visitied dot again for pattern generation.

To solve this pattern problem, we have used the basic concept of randon number generator, because the pattern to be generated has to be randon. Now, while creating the pattern, we also have to check whether the number generated is not repeated and with 9 numbers generated it adds to the complexity of the code. So to reduce the complexity of the code and thinking of the worst case scenario, we divided 9 nummbers into packs of three each from the nascent phase of number generation and hence also check whether the number is repeaded or not parallely. 

Now the pattern generated was passed as x and y co-ordinates in a 3x3 matrix and we used the thread.sleep method to generate the animation of the connecting lines.

For more detailed description of the project, check the readme file and video attached 
[readme.pdf](https://github.com/PrachiDoshi2170/Android-Pattern-Lock-Generator-GUI/files/6245698/readme.pdf)



