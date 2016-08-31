#include <stdio.h>
#include <unistd.h>
#include <string.h>
#include <stdlib.h>
#define INPUTSIZE 50
#define DIRSIZE 100
#define MAXPATH 20
#define MAXARGS 5

//start global variables

char input[INPUTSIZE];				//Main String Input
char args[MAXARGS][10];				//Holds the arguments of the input
char* uname;						//Holds the current username					
char absDir[DIRSIZE];				//Holds Current Directory
char* path;							//Hold the executable paths
int numOfPath=1;					//total number of paths in PATH environment
char tempPath[DIRSIZE];						//Holds the tempPath which is being looked up
//stop global variable

void init(){
	uname=getenv("LOGNAME");
	char temp[10];
	strcpy(temp,"/home/");
	char* dir=strcat(strcat(temp,uname),"/");
	strcpy(absDir,dir);
	path=getenv("PATH");
	for(int i=0;i<strlen(path);i++)
		if(path[i]==':')
			numOfPath++;
}




void checkfile(){
;
}

void username(){
	printf("%s:",uname );
	printf("%s",absDir);
	printf(" $ ");
}


char* takeInput(){
	fgets(input,INPUTSIZE,stdin);
}


char* givePath(int a){
	for(int i=0,int count=0;i<a;i++)


}

void execute(){


}

int main(){
	init();
	printf("%d",numOfPath);
	username();
	while(strcmp(takeInput(),"exit\n")!=0){
		if(strlen(input)!=1)
			execute();
		username();
		
	}
	
}