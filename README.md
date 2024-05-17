# include <stdio.h>

int main() {
    int n, i, num, sum = 0;

    printf("Neçə ədəd daxil etmək istədiyinizi qeyd edin: ");
    scanf("%d", &n);

    for(i = 0; i < n; i++) {
        printf("Ədəd daxil edin: ");
        scanf("%d", &num);

        if(num % 2 == 0) {
            sum += num;
        }
    }

    printf("Cüt ədədlərin cəmi: %d\n", sum);

    return 0;
}
