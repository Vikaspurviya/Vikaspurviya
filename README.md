
#include <stdio.h>

int main()
{int radius,length,width,side,circle,rectangle,square;
printf("Enter radius:");
scanf("%d",&radius);
float π=3.1415;
circle=π*radius*radius;
printf("area for circle %d",circle);
printf("\nenter the length & width:");
scanf("%d%d",&length,&width); 
rectangle=length*width;
printf("area of rectangle:%d", rectangle );
printf("\nEnter side:");
scanf("%d%d",&side,&side);
square=side*side;
printf("area of square:%d", square);

    return 0;}
    
