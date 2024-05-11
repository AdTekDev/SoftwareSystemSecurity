
# Base45


Base45 is an encoding scheme that uses 7-bit printable ASCII characters.  
Base45 divides the data into two bytes each and converts them into three ASCII characters to represent them.  

2 bytes (14/16 bits) --> base10 (2^16) --> base 45 

**Ex.** 
P:  "He"  
Hex:  4865   

Conv: 4865(16)  
= 18533(10)  
= 9 * 452 + 6 * 45 + 38  

-->  
C:  "%69"  

## digits

45 decimal digits	Base45 ASCII characters   
0	0  
1	1  
2	2  
3	3  
4	4  
5	5  
6	6  
7	7  
8	8  
9	9  
10	A  
11	B  
12	C  
13	D  
14	E  
15	F  
16	G  
17	H  
18	I  
19	J  
20	K  
21	L  
22	M  
23	N  
24	O  
25	P  
26	Q  
27	R  
28	S  
29	T  
30	U  
31	V  
32	W  
33	X  
34	Y  
35	Z  
36	[SP]  
37	$  
38	%  
39	*  
40	+  
41	-  
42	.   
43	/  

## Link
- https://dencode.com/en/string/base45
- 
