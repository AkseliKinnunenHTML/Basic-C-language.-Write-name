#include <stdio.h>
char name [100];

int main()
{
    printf("Hello World! Write your user name please :)\n");
    scanf("%s", &name);
    printf("Great! Welcome to our community %s!\n", name);

    return 0;

}
