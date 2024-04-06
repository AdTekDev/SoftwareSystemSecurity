# Exercises

## 03.01

![image](https://github.com/AdTekDev/SoftwareSystemSecurity/assets/18588011/009bb3c8-e20e-4020-87f6-761b2bc9c7bd)

### Encrypt:  
Ci = E(Pi)  
- P[i+1]  iff i%3==0
- P[i+1]  iff i%3==1
- P[i-2]  iff i%3==2

## Decrypt
Pi = D(Ci)
- C[i+2]  iff i%3==0
- C[i-1]  iff i%3==1
- C[i-1]  iff i%3==2

  
