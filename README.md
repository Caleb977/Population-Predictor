#include<stdio.h>
int main(){
    int CurrentPopulation;
    double Percentage;
    double Caculation1;
    int Convert;
    
    puts("Please enter the current population:");
    scanf("%d",&CurrentPopulation);
    
    puts("Please enter percentage estimate (increae/positive or decrease/negative) in decimal without the percentage sign:");
    scanf("%lf",&Percentage);
    
    Caculation1 = (((Percentage/100)*CurrentPopulation)+(CurrentPopulation));
    
    Convert = (int) Caculation1;
    
    puts("The estimated population will be:");
    printf("%d",Convert);
    
    return 0;
}

