# Module-2 Day-1 SEB
## AIM:
To print square number pattern of one and zero with one at odd row and zero at even row using loop in C programming.

## For example:
<img width="116" height="167" alt="image" src="https://github.com/user-attachments/assets/e4fa0e4b-5f27-4794-ad91-fe66237b20b0" />

## Program:
```c
#include <stdio.h>
int main(){
    int row,col,i,j;
    scanf("%d %d",&row,&col);
    for(i=1;i<=row;i++){
        for(j=1;j<=col;j++){
            if(i%2!=0){
                printf("1");
            }
            else{
                printf("0");
            }
        }
    printf("\n");
    }
    return 0;
}
```
## Result:
<img width="280" height="218" alt="image" src="https://github.com/user-attachments/assets/0c16304e-613f-44bd-8db2-f57f69339ca6" />
