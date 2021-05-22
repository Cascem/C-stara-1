# C-star-1
I used the (for) to take a picture of the star.
#define _CRT_SECURE_NO_WARNINGS
2
#include <stdio.h>
3
int main() {
4
    int i, j, n;
5
    scanf("%d", &n);
6
    for (i = 1; i <= n; i++) {
7
        for (j = 1; j <= i; j++) {
8
            printf("*");
9
        }
10
        printf("\n");
11
    }
12
    return 0;
13
}
