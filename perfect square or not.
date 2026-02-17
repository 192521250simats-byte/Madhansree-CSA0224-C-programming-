#include <stdio.h>

int main() {
    int n, i;
    int isPerfectSquare = 0;

    printf("Enter a number: ");
    scanf("%d", &n);

    if (n < 0) {
        printf("Not a perfect square\n");
        return 0;
    }

    for (i = 0; i * i <= n; i++) {
        if (i * i == n) {
            isPerfectSquare = 1;
            break;
        }
    }

    if (isPerfectSquare)
        printf("%d is a perfect square\n", n);
    else
        printf("%d is not a perfect square\n", n);

    return 0;
}
