# Ex-5-RECOGNITION-OF-THE-GRAMMAR-anb-where-n-10-USING-YACC
RECOGNITION OF THE GRAMMAR(anb where n>=10) USING YACC
# Date:
# Aim:
To write a YACC program to recognize the grammar anb where n>=10.
# ALGORITHM
1.	Start the program.
2.	Write a program in the vi editor and save it with .l extension.
3.	In the lex program, write the translation rules for the variables a and b.
4.	Write a program in the vi editor and save it with .y extension.
5.	Compile the lex program with lex compiler to produce output file as lex.yy.c. eg $ lex filename.l
6.	Compile the yacc program with yacc compiler to produce output file as y.tab.c. eg $ yacc –d arith_id.y
7.	Compile these with the C compiler as gcc lex.yy.c y.tab.c
8.	Enter a string as input and it is identified as valid or invalid.
# PROGRAM:
# OUTPUT
## VALID OUTPUT :
<img width="1477" height="750" alt="opvalcd" src="https://github.com/user-attachments/assets/a9eacd91-cee9-4536-8837-9b29f82fba5b" />

## INVALID OUTPUT :
<img width="1487" height="733" alt="image" src="https://github.com/user-attachments/assets/c342b3c5-07ac-4160-bbac-b3125de7f054" />

# RESULT
The YACC program to recognize the grammar anb where n>=10 is executed successfully and the output is verified.
