# TO_DO


--> search a word automatically added with a +ve word in specified seraching engine(ex: google, youtube...etc)

--> Send automatic whatsapp messages using https://github.com/rajujha373/Whatsapp-autosend-script
chrome webdriver
http://www.lesmartomation.com/send-whatsapp-messages-with-automated-script-using-selenium/

--> Write a web crawler and convert it to text and message automatically using whatsapp
--> https://www.youtube.com/watch?v=nRW90GASSXE&list=PL6gx4Cwl9DGA8Vys-f48mAH9OKSUyav0q


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

