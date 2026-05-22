# Square-Cube-of-a-number-using-8051
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



MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END






```

## OUTPUT


<img width="753" height="424" alt="WhatsApp Image 2026-05-22 at 9 11 54 PM" src="https://github.com/user-attachments/assets/28faeac0-56fd-448d-b77e-fe9b1b89c4b9" />



<img width="773" height="434" alt="WhatsApp Image 2026-05-22 at 9 12 05 PM" src="https://github.com/user-attachments/assets/9683245a-e32f-4559-8ab9-011e8e8beec4" />



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




MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END



```


## OUTPUT

<img width="753" height="424" alt="WhatsApp Image 2026-05-22 at 9 11 54 PM" src="https://github.com/user-attachments/assets/72d4abcc-5ed5-4284-96b9-59264d83cba5" />

<img width="773" height="434" alt="WhatsApp Image 2026-05-22 at 9 12 05 PM" src="https://github.com/user-attachments/assets/65a76f83-ab67-4f44-a8c8-d0957c712850" />



## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


