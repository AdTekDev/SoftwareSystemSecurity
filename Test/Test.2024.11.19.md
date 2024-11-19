
# TEST 19.11

## Q1. Encryption & Decryption Problem (6 points)

Write an encryption and decryption function for the following encryption scenario:

- Given a PlainText string P with N characters (8 bits per character)
- The Key is a prime number that is input: Key > 2^(k-1) , Key < 2^(k), Key > 8

- Perform the following encryption to convert into CipherText, where CipherText is a string concatenated by bits created from the following result:

R (initially) = 0  
**Loop:**   
. C[i] = ( P[i] * Key  + R) % 2^(8+k-1)    
. R = int[( P[i] * Key  + R) / 2^(8+k-1)]   
. R = R XOR 11001100

- C[i] is represented by 8+k-1 bits   
- The encryption result is the set of values: C, R, Key

### Tasks:
a. (2 points) Write the encryption function with inputs   
b. (2 points) Write the decryption function with the input array CipherText.  
c. (2 points) Convert CipherText into a string of Hexadecimal characters (0-9A-F) from every 4 bits.  


## Q2. Cryptanalysis Problem (3 points)

The task presents a scenario where an employee in a company has a specific password-setting habit:  

- The first character is typically a consonant.
- The last character is usually a special character such as @, *, or &.
- The middle character(s) typically consist of a mixture of numbers and vowels.
- There can't be more than 2 consecutive vowels.
- If there are 3 or more consecutive alphabetical characters, there might be a double consonant.
- If there are fewer than 3 alphabetical characters, there's usually a letter "o".

This employee accidentally sent the company's business plan to the wrong person via email.   
It's known that the current file is encrypted with a password consisting of 3 characters.  

Given this information, **Implementing the python program (applying all rules)** to guess the password protecting the data and find the correct password to open the compressed file ATD.rar/zip.  
- ATD.rar - https://github.com/AdTekDev/eCommerceSecurity/blob/main/Exercises/05-Net/ATD.rar
- ATD.zip - https://github.com/AdTekDev/eCommerceSecurity/blob/main/Exercises/05-Net/ATD.zip
   
   
**1 point**: Submit the assignment 2/3 of the way before the deadline, complete all the requirements, write the code clearly, and display the results step by step.
  
## Time
- Duration: 100'
- Time: 8:40 - 10:40 

## Submit  
Link: https://mlearning.hoasen.edu.vn/mod/assign/view.php?id=1101676&forceview=1    
**3 parts:**
- Result's Images
- Source Code's Zip file
- Mark 9-10: Show the step-by-step results

## Grading RULEs
- If a student's submission is 90% identical to another, the score for that assignment will be 0.
- If a student's submission is more than 60% similar to another, their score will be reduced by 25%.
- If a student's submission shows clear signs of being copied entirely from ChatGPT (Gemini, Copilot, Claude, ...), the maximum score they can receive is 4 points.
- If a student's submission shows signs of being mostly copied from ChatGPT (Gemini, Copilot, Claude, ...) and still contains errors from the ChatGPT response, the maximum score they can receive is 7 points.
