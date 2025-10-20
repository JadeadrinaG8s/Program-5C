# Program-5C
C module 5
EX NO-5)C)a C Program to print the Opposite Diagonal Elements of a Matrix[3x3].
DATE:20/10/25
NAME:JADE ADRINA J
REF NO:25017000
AIM:TO Write a C Program to print the Opposite Diagonal Elements of a Matrix[3x3]'
ALGORITHM:
1)Take a [3x3]matrix as input from the user.2)using for loop print the matix[i][2-i] elements of the matrix.
PROGRAM:
```
#include <stdio.h>

int main() {
    int rows, cols;
    scanf("%d %d", &rows, &cols);
    if (rows != 3 || cols != 3) {
        printf("This program only works for a 3x3 matrix.\n");
        return 1;
    }
    int matrix[3][3];
    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 3; j++) {
            scanf("%d", &matrix[i][j]);
        }
    }
    printf("The Diagonal Elements of a Matrix = ");
    for (int i = 0; i < 3; i++) {
        printf("%d ", matrix[i][2 - i]);
    }
    printf("\n");

    return 0;
}
```
OUTPUT:
<img width="1090" height="355" alt="Screenshot 2025-10-20 084424" src="https://github.com/user-attachments/assets/2d0c5bfd-7474-4f4a-a817-6171d3812640" />
RESULT:
thus,a C Program to print the Opposite Diagonal Elements of a Matrix[3x3] has been executed successfully.
