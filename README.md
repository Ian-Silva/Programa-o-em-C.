# Programa-o-em-C.
Programas em Linguagem C

#include <stdio.h>
int main(void){

int n, returnN, face[7], i;

  scanf("%d", &n);
    
    for(i=1; i<7; i++)
        face[i]=0;
    
    for(i=1; i<n; i++){
    scanf("%d", &returnN);
    
    face[returnN]++;
    }
    for(i=1; i<7; i++)
printf("%d\n", f[i]);

return 0;
}
