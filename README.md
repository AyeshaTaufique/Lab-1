

Practice



































# practice
my first repository
#include <stdio.h>
#include <stdlib.h>
int main() {
    int a = 4;
    printf("%d\n",a);
    a = 3;
    printf("%d\n",a);
    int x,y,z,w;
    x=3;
    y=8;
    z=2;
    w=x+y+z+a;
    printf("%d\n",w);
    int table(f){
        printf("TABLE of %d\n",f);
        for(int i=1;i<11;i++){
            int h;
            h=f*i;
            printf("%d",f);
            printf("*%d",i);
            printf("=%d\n",h);
            h=0;
            }
        }
    int l;
    printf("Type numb:");
    scanf("%d",&l);
    table(l);
    int v,p;
    printf("Type numb1:");
    scanf("%d",&v);
    if(v%2==0){
        printf("The numb1 is even\n");
        }else{
            printf("The numb1 is odd\n");
            }
    printf("Type num2:");
    scanf("%d",&p);
    if(p%2==0){
        printf("The numb2 is even\n");
        }else{
            printf("The numb2 is odd\n");
            }
    if(v>5 && p>5){
        printf("The sum is:%d\n",v+p);
        }else if(v>5||p>5){
            printf("The product is:%d\n",v*p);
            }else if(v<5&&p<5){
                printf("numb1:%d\n",v+1);
                printf("numb2:%d\n",p+1);
                }else{
                    printf("Hello World\n");
                    }
    void fun1(){
        printf("My function just executed\n");
    }
    int t;
    printf("Enter the seconds:");
    scanf("%d",&t);
    if(t>20){
        printf("Good Morning\n");
    }else if(t<20){
        printf("Good Afternoon\n");
    }else{
        printf("Good Night\n");
    }
    (t>20)? printf("Good Morning\n"):printf("Good Afternoon\n");
    fun1();

    int num;
    printf("Enter the num:");
    scanf("%d",&num);
    switch (num) {
    case 7:
        printf("Value is 7\n");
        break;
    case 8:
        printf("Value is 8\n");
        break;
    case 9:
        printf("Value is 9\n");
        break;
    default:
        printf("Out of range\n");
        break;
    }
    int myfunc(a,b){
        return a+b;
    }
    int j,k;
    printf("Enter number 1:");
    scanf("%d",&j);
    printf("Enter number 2:");
    scanf("%d",&k);
    printf("The Total is :%d",myfunc(j,k));
    return 0;
}

