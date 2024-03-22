#include <stdio.h>

int main(void)
{
    int i, j, N;
    printf("puts N");
    scanf("%d", &N);
    for(i = 1; i <= N; i++)
    {
        for(j = 1; j <= 9; j++)
        {
            printf("%d X %d = %d", i, j, i * j);
        }
    }
    return 0;
}