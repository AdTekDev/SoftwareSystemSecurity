
# Hashing


## 9.01 
Hashing (h) 96-bits

Give the Message M 

1. Divide X = M into n (32-bit word): W0, W1, W2, . . ., 0 ,0   (n % 3 == 0)  
2. Init (hexa)  
	AA = 67452301  
   	BB = EFCDAB89  
	CC = 98BADCFE  
	h(0) = (AA,BB,CC)  (3*32 = 96 bits)  
 
3. Loop k (0..n/3)  
	A = W[3*k] + AA (mod 2^32)  
	B = W[3*k+1] + BB (mod 2^32)  
	C = W[3*k+2] + CC (mod 2^32)  
	
	AA = A  
	BB = B   
	CC = C   
	
Hashing h = (A,B,C)   


