// # Question

#include<stdio.h>
int main(){

char i, a, b, c, d, e;

printf("\n Question \n");

printf("\n1. What's your name?\n");

printf("\n2. What's your Father's name?\n");

printf("\n3. What's your Mother's name?\n");

printf("\n4. What's your Brother's name?\n");

printf("\n5. What's your sister's name?\n");


printf("\nPlease Choice your Question(a, b, c, d, e) = ");
scanf("%c", &i);

if(  i == 'a'){
    printf("\nEnter your ans = ");
    scanf("%c ", &a);
    printf("\n1. What's your name?\n ");
}

else if(  i == 'b'){
    printf("\nEnter your ans = ");
    scanf("%c ", &b);
    printf("\n2. What's your Father's name?\n ");
}

else if(  i == 'c'){
    printf("\nEnter your ans = ");
    scanf("%c ", &c);
    printf("\n3. What's your Mother's name?\n ");
}

else if(  i == 'd'){
    printf("\nEnter your ans = ");
    scanf("%c ", &d);
    printf("\n4. What's your Brother's name?\n ");
}

else {
    printf("\nEnter your ans = ");
    scanf("%c ", &e);
    printf("\n5. What's your sister's name?\n ");
}

return 0;

}
