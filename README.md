# project-4.1
MULT.asm

@2	//GO TO FINAL ANSWER BOX
M=0	//ZERO ANS BOX

@0
D=M
@END
D;JEQ	//IF ONE PRODUCT IS ZERO

@1
D=M
@END
D;JEQ	//IF ONE PRODUCT IS ZERO

@0	//NOT NECESSARY
D=M	//
@3	//
M=D	//ONLY TO KEEP THE NUMBERS BEING MUTLIPLED


(LOOP)
@1	//GET 2ND NUM
D=M	//D HAS 2ND NUM

@2	//GO TO FINAL ANSWER BOX
M=D+M	//RAM[2] NOW HAS 2ND NUMBER + ITS PREVIOUS VALUE

@3	//GET 1ST NUM
M=M-1	//1ST NUM-1

D=M	//IDK WHY D NEEDS TO =M?
@LOOP	//WHERE TO JUMP TO
D;JGT	//JUMP		    (WHY CANT THIS BE M;JGT?)


(END)
@END
0;JMP

![image](https://github.com/user-attachments/assets/70a99331-7062-4ad2-acee-4671869b9a09)


![image](https://github.com/user-attachments/assets/2cae501a-1f3f-446a-8416-5010c69674d5)


![image](https://github.com/user-attachments/assets/1fe869d9-63cb-4cd1-bdd0-6fdbc72c2be0)

