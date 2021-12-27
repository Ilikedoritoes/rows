
#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
#include <stdlib.h>
 

void main()
{
    int colume = 1, line = 1, rows = 5;
    printf("how many rows do you want?\n");
    scanf("%d", &rows);
    printf("ok\n");
    for (line = 1; line <= rows; line++)
    {
        for (colume = 1; colume <= line; colume++)
        {
            printf("OR IS COOL ");
        }
        printf("\n");
    }
    system("pause");
}
