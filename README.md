# hacktoberfest2022-06

``` c
#include <stdio.h>

int main() {
    printf("Hello World!);
    return 0;
}
// Contributed by ANG-98
```

``` c
void pritnTable(int n) {
    int i;
    for (i = 1; i <= 10; i++) {
        printf("%5d * %5d = %5d\n", n, i, n*i);
    }
}
// Contributed by ASM
```

``` c
int no_of_digits(int n) {
    int count = 0;
    do {
        count++;
    } while (n /= 10);
    return count;
}
// Contributed by SAN-98
```

``` c
int sum(int n1, int n2) {
    return n1+n2;
}
// Contributed by PRA-99
```
