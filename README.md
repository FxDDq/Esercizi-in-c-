#include <stdio.h>

int main()
{
    int n;
    float x;
    printf("inserisci quanti multipli vuoi conoscere del tuo numero: ");
    scanf("%d", &n);
    printf("inserisci il numero di cui vuoi conoscere i propri multipli ");
    scanf("%f", &x);
    for(int i = 1; i<=n; i++) {
        printf("%f ", x*i);
    }
    return 0;
}
