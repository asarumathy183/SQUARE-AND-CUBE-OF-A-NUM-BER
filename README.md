# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG 00H
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END
```

## OUTPUT

<img width="800" height="300" alt="image" src="https://github.com/user-attachments/assets/bb1b34e8-0ce1-4c2c-91f8-5c67de28c000" />
<img width="800" height="300" alt="image" src="https://github.com/user-attachments/assets/6642b8c5-a120-4ef7-ad8f-caf3d89cbc48" />

## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
ORG 00H
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
MOV B,A
MOVX A,@DPTR
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END
```


## OUTPUT
<img width="800" height="400" alt="image" src="https://github.com/user-attachments/assets/49292ce1-cab1-4a88-af99-ccc0651ab4b6" />
<img width="800" height="300" alt="image" src="https://github.com/user-attachments/assets/871afa9e-f5f8-45b1-94b9-9d646cf18057" />


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
