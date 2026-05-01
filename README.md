# Bet-by-code
C programming 
#include<stdio.h>
int main(){
	int i;
	int x;
	printf("Choose the Any number to win: \n");
    
    //this is for loop ,looping flow control
    for(i=1; i<=5; i++){
    	printf("%d \n",i);
	}
	printf("which Number you have choosen: \n");
	scanf("%d",&x);
	
	        //switch case 
	    switch(x){
	 	case 1: printf("You are Failed.\n");
	 	break;
	 	case 2: printf("You are winning 1,000/= \n");
	 	break;
	 	case 3: printf("Try again. ");
	 	break;
	 	case 4: printf("you are  winning 10,000/= \n");
	 	break;
	 	case 5: printf("you are winning 5,000/= \n");
	 	break;
	 	default: printf("Invalid Number \n");
	}
	 
	return 0;
}

