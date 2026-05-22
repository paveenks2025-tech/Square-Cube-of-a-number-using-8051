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


MOV A,P0
MOV R0,A
MOV B,R0
MUL AB
MOV P2,A
END






```

## OUTPUT

<img width="753" height="424" alt="WhatsApp Image 2026-05-22 at 9 11 09 PM" src="https://github.com/user-attachments/assets/b884d518-1e4c-44c8-919c-3592e5311e36" />


<img width="769" height="431" alt="WhatsApp Image 2026-05-22 at 9 11 35 PM" src="https://github.com/user-attachments/assets/68be2d0d-47be-445b-b99e-5d00d7fa0e9e" />


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

<img width="753" height="424" alt="WhatsApp Image 2026-05-22 at 9 11 54 PM" src="https://github.com/user-attachments/assets/e72aab01-97eb-4491-a244-f0f35f51c954" />

<img width="773" height="434" alt="WhatsApp Image 2026-05-22 at 9 12 05 PM" src="https://github.com/user-attachments/assets/34f9d2d0-f0a8-4998-8508-5bfb25f73efc" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


