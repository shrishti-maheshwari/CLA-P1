#include <stdio.h>
int main() 
{
    int m,n; float min;
    scanf("%d %d",&m,&n) ;
    min=(m*n);
    printf("%0.0f",min/2) ;    
    return 0;
}


#include<stdio.h>
int main()
{
    float kilometres,m,feet,inch,cm;
    scanf("%f",&kilometres);
    m=kilometres*1000;
    feet=kilometres*3280.84;
    inch=kilometres*39370.1;
    cm=kilometres*100000;
    printf("%0.2f m\n%0.2f ft\n%0.2f in\n%0.2f cm\n",m,feet,inch,cm) ;
    return 0;
}
