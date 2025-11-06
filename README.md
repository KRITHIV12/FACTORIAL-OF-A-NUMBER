# FACTORIAL-OF-A-NUMBER-USING-8051-KEIL

**AIM:**

To write and execute Assembly language Program to perform factorial of a number using 8051 keil.
APPARATUS REQUIRED: Personal computer with Keil software

**ALGORITHM:**

• Start  

• Input: Read the number n.  

• Initialize:  

•Set factorial to 1.  

•Set i to 1.  

• Loop: While i is less than or equal to n:  

•Multiply factorial by i.  

•Increment i by 1.  

• Output: Store or print the value of factorial.  

• End

**FLOW CHART:**
<img width="261" height="308" alt="image" src="https://github.com/user-attachments/assets/bffe89f6-3ba9-4294-b817-8b545f680e66" />

**Program:**

ORG 0000H   

MOV A,#04H  

MOV R0,A  

ACALL FACTORIAL  

MOV 40H,A  

SJMP THIN  

FACTORIAL:DEC R0  

CJNE R0,#01H,PRODUCT  

SJMP THICK   

PRODUCT:MOV B,R0  
MUL AB  
ACALL FACTORIAL  
THICK: RET  
THIN:  
END



**Output:**  
<img width="1919" height="1116" alt="Screenshot 2025-10-03 082936" src="https://github.com/user-attachments/assets/b31623b3-9474-4753-83be-5c144cbd8741" />


<br>
<br>
<br>



**Manual Calculations:** 
<img width="1069" height="745" alt="image" src="https://github.com/user-attachments/assets/c247a026-2654-4134-a87f-8515a8314203" />


<br>
<br>
<br>
<br>
<br>
<br>





**Result:**

Thus the factorial of a number using 8051 keil was calculated and shown the output.



