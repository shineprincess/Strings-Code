#include<stdio.h>
#include<string.h>

int main()
{
	char a[10],b[10],c[10];
	int i,j;
	int x,y,z;
	
	printf("Enter your sentence\n");
	scanf("%s ",&a);
	scanf("%s",&b);
	scanf("%s ",&c);
	printf(a);
	printf("\n");
	printf(b);
	printf("\n");
	printf(c);
	x=strlen(a);
	y=strlen(b);
	
	//change vowels to %
	for(i=0;i<x;i++)
	{
	     if(a[i]=='a' || a[i]=='e' || a[i]=='i' || a[i]=='o' || a[i]=='u' )
		{
			a[i]='%';
		}
	}
	printf("\n");
	printf("\n");
	
	//change consonants to #
	for(j=0;j<y;j++)
	{
		if(b[j]=='b' || b[j]=='c' || b[j]=='d' || b[j]=='f' || b[j]=='g' || b[j]=='h' || b[j]=='j' || b[j]=='k' || b[j]=='l' || b[j]=='m' || b[j]=='n' || b[j]=='p' || b[j]=='q' || b[j]=='r' || b[j]=='s' || b[j]=='t' || b[j]=='v' || b[j]=='w' || b[j]=='x' || b[j]=='y' || b[j]=='z' )
		{
			b[j]='#';
		}
	}

	
	//change word to uppercase
	z=0;
	while(c[z] !='\0')
	{
		if(c[z]<='a' && c[z]<='z')
		{
			c[z]=c[z]-32;
		}
		z++;
	}
	printf("%s %s %s ",&a,&b,&c);
	
	return 0;
}
