# Question

#include<stdio.h>
int main(){

char i, a, b, c, d, e, f, g, h, j, k, l;

printf("\n Question \n");

printf("\n1. What's your name?\n");

printf("\n2. What's your Father's name?\n");

printf("\n3. What's your Mother's name?\n");

printf("\n4. What's your Brother's name?\n");

printf("\n5. What's your sister's name?\n");


printf("\nPlease Choice your Question(a, b, c, d, e) = ");
scanf("%c", &i);

if(  i == 'a'){
    printf("\n1. What's your name?\n ");
    scanf("%c ", &g);
    printf("%c", g);
}

else if(  i == 'b'){
    printf("\n2. What's your Father's name?\n ");
    scanf("%c", &h);
    printf("%c", h);
}

else if(  i == 'c'){
    printf("\n3. What's your Mother's name?\n ");
    scanf("%c", &j);
    printf("%c", j);
}

else if(  i == 'd'){
    printf("\n4. What's your Brother's name?\n ");
    scanf("%c", &k);
    printf("%c", k);
}

else {
    printf("\n5. What's your sister's name?\n ");
    scanf("%c", &l);
    printf("%c", l);
}

return 0;

}
