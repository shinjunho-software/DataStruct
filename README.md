#include <stdio.h>

struct student {
        char lastName[13];
        int studentId;
        short grade;
};

int main()

{
        struct student pst;
        printf("[shin jun ho  2017038007]\n");
        printf("size of student = %ld\n", sizeof(struct student));
        printf("size of int = %ld\n", sizeof(int));
        printf("size of short = %ld\n", sizeof(short));

        return 0;
}
