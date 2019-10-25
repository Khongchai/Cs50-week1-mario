#include <stdio.h>
void print_dots (int a);
void print_bricks(int a);
int main(void)

{
    int i;
    printf("Enter height: ");
    scanf("%d", &i);
    if (i > 8 || i < 1)
    {
        do
        {
            {
                printf("Only enter a number between 1 - 8: ");
                scanf("%d", &i);
            }
        }
        while (i > 8 || i < 1);
        for (int a = 0; a < i; a++)
        {
            print_dots(a);
            print_bricks(a);
            printf("    ");
            print_bricks(a);
            printf("\n");
        }
    }
    else
        for (int a = 0; a < i; a++)
        {
            print_dots(a);
            print_bricks(a);
            printf("    ");
            print_bricks(a);
            printf("\n");
        }
return 0;
}


void print_dots (int a)
{
  for (int c = 8; a < c ; c--)
     {
        printf(" ");
     }
  return ;
}

void print_bricks(int a)
{
for (int b = -1; b < a; b++)
        {
            printf("#");
        }
return ;
}




