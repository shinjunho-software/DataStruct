#include <stdio.h>

#define MAX_SIZE 100

float sum(float [], int);
float input[MAX_SIZE], answer;
int i;
void main(void)
{
        for(i=0; i < MAX_SIZE; i++)
                input[i]=i;
        printf("[shin jun ho  2017038007]\n");
        printf("address of input = %p\n",input);

        answer = sum(input, MAX_SIZE);
        printf("The sum is: %f\n", answer);
}

float sum(float list[], int n)
{
        printf("value of list = %p\n", list);
        printf("address of list = %p\n\n", &list);

        int i;
        float tempsum = 0;
        for(i=0; i < n; i++)
                tempsum +=list[i];
        return tempsum;
}
