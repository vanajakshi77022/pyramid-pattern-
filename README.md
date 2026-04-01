# pyramid-pattern-
#include <stdio.h>
int main(){
    int i,j,rows,space;
    printf("25331A05E8\n");
    printf("enter the number of rows");
    scanf("%d",&rows);
    for(i=1;i<=rows;i++){
        for(space=1;space<=rows-i;space++){
            printf(" ");
        }
        for(j=1;j<=2*i-1;j++){
            printf("*");
        }
        printf("\n");
    }
    return 0;
}
