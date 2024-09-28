#include <stdio.h>
#include <string.h>
int main(){
    char a[100], b[100] = "", c[100] = "####";
    do{
        scanf("%s", a);
        if(b[0] == '\0' || a[0] == b[strlen(b)-1]){
            printf("%s\n", a);
        }
        strcpy(b,a);
    } while(strcmp(a,c) != 0);
    return 0;
}

