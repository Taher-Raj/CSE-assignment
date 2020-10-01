# CSE-assignment
html tags

Assignment-01


#include<stdio.h>
main(){
    
    int row,col;
    for(row=5;row>=1;row--){
        
        for(col=1;col<=row;col++)
        printf("*");
        printf("\n");
    } 
}


Assingment-02


#include<stdio.h>
main(){
    
    int row,col,count=1;
    for(row=1;row<=5;row++){
        
        for(col=1;col<=row;col++)
        printf("%d ", count++);
        printf("\n");
    } 
}
