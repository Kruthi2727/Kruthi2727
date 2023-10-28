#include <stdio.h>
main() {
	char name[50];
	int maths,english,accounts,economics,totalmarks;
	
printf("enter your name");
scanf("%s",&name);

printf("enter tha marks");
scanf("%d%d%d%d",&maths,&english,&accounts,&economics);

	printf("NAME:%s\n",name);
	printf("Maths Grade: %d\n", maths);
	printf("english Grade: %d\n", english);
    printf("accounts Grade: %d\n", accounts);
    printf("economics Grade: %d\n", economics);

totalmarks=maths+english+accounts+economics;
	
	if (totalmarks >= 351) 
        printf("Grade: A\n");

	if ((totalmarks>=301) && (totalmarks<=350))
        printf("Grade: B\n");
        
	 if ((totalmarks>=251) && (totalmarks<=300)) 
        printf("Grade: C\n");
 
	 if ((totalmarks>=201) && (totalmarks<250)) 
        printf("Grade: D\n");
    
    if((totalmarks<=200))
	  printf("Grade: F\n");
    
}
