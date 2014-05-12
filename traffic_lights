#include<reg51.h>

void red(int k)
{
	int i, j;
	for(i=k; i>0; i--)
		for(j=110; j>0; j--);
}

void yellow(int k)
{
	int i, j;
	for(i=k; i>0; i--)
		for(j=110; j>0; j--);
}

void green(int k)
{
	int i, j;
	for(i=k; i>0; i--)
		for(j=110; j>0; j--);
}

void main()
{
	while(1)
	{
		P1=0x21;
		green(8000);
		
		P1=0x0a;
		yellow(2000);
		P1=0x0c;
		red(8000);
		P1=0x11;
		yellow(2000);

	}
}
