#include <stdio.h>
 int main() {
 int i;
 printf("Demonstrating break:\n");
    for(i = 1; i <= 10; i++) {
        if(i == 6) {
            break;
        }
        printf("%d ", i);
    }

    printf("\n\n");
 printf("Demonstrating continue:\n");
    for(i = 1; i <= 10; i++) {
        if(i == 6) {
            continue;  
        }
printf("%d ", i);
    }
return 0;
}
