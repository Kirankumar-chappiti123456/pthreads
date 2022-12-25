#include<pthread.h>
#include<stdio.h>
void * kiran(void *arguments)
{
    int n;
    printf("enter the number:");
    scanf("%d",&n);
    (n%2==0)?printf("even "):printf("odd");
    return NULL;
}
int main()
{
    pthread_t thread1;
    printf("chappiti\n");
    pthread_create(&thread1,NULL,kiran,(void *)&thread1);
    pthread_join(thread1,NULL);
}
