

 “Searching for Order in Chaos”

The idea of this project is to collect written data and visual data to find some order in random chaos and to show that the more diverse and complex the pattern we are looking for the more we will find. We are using random data to create a N -by-N two dimensional bit array, which develops random patterns. One pattern will be different from the next if there are any, so the program uses brute force to find patterns. It takes more time to look for patterns the larger the bit array is and the more complex the patterns we are searching for.
First I developed horizontal and vertical search functions, then diagonals. I first created .pbm files to create visual data. This bitmap file can only create black and white pixels. As I created more searches in different directions I created .ppm files which creates color images, so it can be easily distinguishable among each other. 

The program searches for different patterns, horizontally, vertically and diagonally in the random bit array. It then creates data of the patterns found and looks for stars which would be the case where there was a pattern found in all directions. We also looked for cases where we are not concerned for vertical and horizontal patterns and diagonal patterns. 
The user will choose the pattern they want to search for. Such as 500 x 500 bit array, searching for a pattern radius of four and skips every other pixel. The user can change the type of pattern they are looking for, for each direction.
The more complex and the smaller the radius the more patterns are found. 

For example:
Looking at the radius of three in a 1000 x 1000 bit array with no skips we find on average 230 stars from the data I have collected. Now looking at the same radius in a 1000 x 1000 bit array skipping every other pixel we find on average 3900 stars.
When randomly manipulating columns and flipping its original data over and over again we get roughly the same number of patterns found. It is interesting to see that when changing the data randomly we still end up with similar numbers. There seems to be a balance, even when manipulating the data. The number of patterns found stay in the same range, there is somewhat stability.
