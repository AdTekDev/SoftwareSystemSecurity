
## Problem:  

Write an encryption and decryption function for the following encryption scenario:

- Given a PlainText string P with N characters (8 bits per character)
- The Key is a prime number that is input: Key > 2^(k-1) , Key < 2^(k), Key > 8

- Perform the following encryption to convert into CipherText, where CipherText is a string concatenated by bits created from the following result:

R (initially) = 0  
**Loop:**   
. C[i] = ( P[i] * Key  + R) % 2^(8+k-1)    
. R = int[( P[i] * Key  + R) / 2^(8+k-1)]   

- C[i] is represented by 8+k-1 bits   
- The encryption result is the set of values: C, R, Key

## Tasks:
a. (3 points) Write the encryption function with inputs   
b. (3 points) Write the decryption function with the input array CipherText.  
c. (2 points) Convert CipherText into a string of Hexadecimal characters (0-9A-F) from every 4 bits.  
d. (2 points) Write an additional decryption function with the input as CipherText in the format from task c.  

## Time
- Duration: 90'

## Submit  
- Link: https://mlearning.hoasen.edu.vn/mod/assign/view.php?id=1054114
- Code zip
- Result's Images
- Mark 9-10: Show the step-by-step results in tasks c and d 
