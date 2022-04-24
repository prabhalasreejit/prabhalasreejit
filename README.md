- #include <stdio.h>
struct student{
    char name[20];
    int idno;
    float cg;
};
int main()
{
    struct student s1;
    printf("enter the  name");
    scanf("%s",s1.name);
    printf("enter id");
    scanf("%d",&s1.idno);
    printf("enter cg");
    scanf("%f",&s1.cg);
    printf("name %s\n  ido %d\n  cg %f\n",s1.name,s1.idno,s1.cg);
    return 0;
}
