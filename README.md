# AREA.c
#AREA OF THE CIRCLE,RECTANGLE,SQUARE.
#include<stdio.h>
int main()
{
	float r,l,b;
	int c;
	printf("1.AREA OF A CIRCLE\n2.AREA OF A RECTANGLE\n3.AREA OF A SQUARE");
	printf("\nENTER THE CHOICE: ");
	scanf("%d",&c);
	switch(c)
	{
		case 1:
			printf("\nENTER THE RADIUS : ");
			scanf("%f",&r);
			printf("AREA OF THE CIRCLE IS : %.1f",3.14*(r*r));
			break;
		case 2:
			printf("\nENTER THE LENGTH: ");
			scanf("%f",&l);
			printf("ENTER THE BREATH: ");
			scanf("%f",&b);
			printf("AREA OF THE RECTANGLE: %.1f",l*b);
			break;
		case 3:
			printf("\nENTER THE LENGTH l: ");
			scanf("%f",&l);
			printf("AREA OF THE SQAURE: %.1f",l*l);
			break;
		default:
			printf("INVALID");
	
	}
	return 0;
}
