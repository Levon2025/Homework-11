# Homework-11
#include <stdio.h>

int main(){
  
 int total_seconds = 100000;
 int hours = 0;
 int minutes = 0;
 int seconds = 0;

 hours = total_seconds / 3600;
 total_seconds = total_seconds %3600;
 minutes = total_seconds / 60;
 seconds = total_seconds % 60;

 printf("%d seconds is equal to  %d hours ,%d minutes ,%dseconds.\n",total_seconds , hours ,minutes ,seconds ) ;
 return 0 ;

}
