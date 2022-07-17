#include <stdio.h>


int main()
{
  char name[123];
   int i,count=0;
    printf("Enter your name ");
    fgets( name,123,stdin);
    i=0;
    while(name[i]!='\0')
    {
        if(name[i]=='a'||name[i]=='e'||name[i]=='i'||name[i]=='o'||name[i]=='u');
        count++;
        i++;
    }
    

    printf("%d vowel ",count);

    return 0;
}
