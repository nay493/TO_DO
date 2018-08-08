# TO_DO

#include<stdio.h>

int main()
{

unsigned long long int num;
num = 0xABCDEF00000000EE;
unsigned int us = 0;
unsigned int ks = 0;

printf("nay@: num = 0x%llx, numRS = 0x%llx, numLS = 0x%llx\n", num, num>>32, num<<32);
printf("nay@: num = 0x%llx, numLS = 0x%llx, numRS = 0x%llx\n", num, num<<32, num>>32);

us = num<<32;
ks = num>>32;
printf("nay@: us = 0x%x, ks = 0x%x\n", us, ks);



return 0;
}

