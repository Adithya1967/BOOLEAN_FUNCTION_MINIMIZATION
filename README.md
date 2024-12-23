# BOOLEAN_FUNCTION_MINIMIZATION
# DATE 01.10.2024
**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.
@@ -30,21 +30,47 @@ Hardware – PCs, Cyclone II , USB flasher

5.	For different input combinations generate the timing diagram.

**BOOLEAN MINIMIZATION**
![image](https://github.com/user-attachments/assets/452d1a2b-d15c-427c-a131-38ced47f91d2)
![image](https://github.com/user-attachments/assets/edb2163c-4813-4c3e-9832-eaedcc2e7982)


**TRUTHTABLE**
![image](https://github.com/user-attachments/assets/ff9fba34-8fb2-4aa1-9e36-451ecf89e592)

**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

Developed by:Adithya sivakumar
RegisterNumber:24006778

Developed by: RegisterNumber:*/
**RTL**
![Screenshot (89)](https://github.com/user-attachments/assets/388df616-b62c-49e9-9c5d-813d962a55d0)

![Screenshot (103)](https://github.com/user-attachments/assets/efb025f0-a851-4409-aa06-09635d8a6dd7)

**RTL realization**
**WAVEFORM**

**Output:**
![Screenshot (98)](https://github.com/user-attachments/assets/1984c5ab-4cbb-4d19-864f-596ec69a2fb5)
![Screenshot (102)](https://github.com/user-attachments/assets/f43631ed-a7fd-4ece-95a1-ee3f7519c993)

**RTL**

**Timing Diagram**

**Result:**

