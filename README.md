#include <stdio.h>
struct student {
    char name[50];
    int age;
    float marks;
};
int main(){
    struct student s1= {"sita", 22, 48.90};
    printf("student name is %s\n", s1.name);
    printf("Age: %d \n",s1.age);
    printf("marks: %.4f\n", s1.marks);
    return 0;
}
