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

INPUT
<img width="1919" height="257" alt="MAGESH KUMAR C 212224060143 FACTORIAL IP" src="https://github.com/user-attachments/assets/94be1607-45a4-4a82-ba2b-e145f62d7f18" />


OUTPUT
<img width="1917" height="265" alt="MAGESH KUMAR C 212224060143 FACTORIAL OP" src="https://github.com/user-attachments/assets/3404bcde-b6ff-4d7c-9b6c-8bab07152170" />

<br>
<br>
<br>



**Manual Calculations:**  

![WhatsApp Image 2025-10-23 at 11 10 12_27f78f49](https://github.com/user-attachments/assets/7472f8c9-a087-40cc-8489-1fdd835d9a40)


<br>
<br>
<br>
<br>
<br>
<br>





**Result:**

Thus the factorial of a number using 8051 keil was calculated and shown the output.
