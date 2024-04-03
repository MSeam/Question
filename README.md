// # Question

#include<stdio.h>
int main(){

char i, a[30], b[30], c[30], d[30], e[30];

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
    scanf("%s", &a);
    printf("\n1. What's your name?\n\nAns:- %s\n", a);
}

else if(  i == 'b'){
    printf("\nEnter your ans = ");
    scanf("%s", &b);
    printf("\n2. What's your Father's name?\n\nAns:- %s\n", b);
}

else if(  i == 'c'){
    printf("\nEnter your ans = ");
    scanf("%s", &c);
    printf("\n3. What's your Mother's name?\n\nAns:- %s\n", c);
}

else if(  i == 'd'){
    printf("\nEnter your ans = ");
    scanf("%s", &d);
    printf("\n4. What's your Brother's name?\n\nAns:- %s\n", d);
}

else {
    printf("\nEnter your ans = ");
    scanf("%s", &e);
    printf("\n5. What's your sister's name?\n\nAns:- %s\n", e);
}

return 0;

}
