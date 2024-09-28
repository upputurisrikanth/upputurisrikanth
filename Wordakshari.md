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
<!---
upputurisrikanth/upputurisrikanth is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
