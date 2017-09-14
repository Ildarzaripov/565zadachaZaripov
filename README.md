# 565zadachaZaripov
#include<conio.h>
#include<math.h>
#include<stdio.h>
int main(){
    int i;
    scanf("%d", &i);
    do
    {
        if (i%2==0)
            i=i/2;
        else i=i*3+1;
    }
    while (i!=1);
    printf("%d", i);
    return 0;
}
