//3-sayidan-buyuk-olan-bulma
#include <stdio.h>
int main()  {
	int a,b,c;
	printf("3 adet sayi giriniz\n");
	scanf("%d%d%d",&a,&b,&c);

	if (a>b && a>c)
	printf("%d girdiginiz en buyuk sayi",a);

	else if(b>a && b>c)
	printf("%d girdiginiz en buyuk sayi",b);

	else
	printf("%d girdiginiz en buyuk sayi",c);

	return 0;
}
/*
#include<stdio.h>
#include<stdlib.h>
int main(){
float x,y,z,max;
printf("lutfen 3 adet sayi giriniz\n");
scanf("%f%f%f",&x,&y,&z);
max=x;
if(max<y)
max=y;
if(max<z)
max=z;
printf("en buyuk sayi : %f",max); }*/
