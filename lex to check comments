#include<stdio.h>
int main(){
	int i;
	char st[30];
	printf("enter a comment:");
	scanf("%s",&st);
	if(st[0]=='/'){
		if(st[1]=='/')
		printf("it is a comment");
		else if(st[1]=='*'){
			for(i=2;i<=30;i++){
				if(st[i]=='*'&&st[i+1]=='/'){
					printf("it is a comment");
				}
			}
		}
	}
	else{
		printf("it is not a comment");
	}
	return 0;
}
