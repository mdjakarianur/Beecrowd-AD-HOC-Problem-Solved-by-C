#include<stdio.h>
int josephus(int n,int k);
int main()
{
      int tcase,n,k,i;
      while(scanf("%d",&tcase) == 1) {
            for(i=1; i<=tcase; i++) {
                  scanf("%d %d",&n, &k);
                  int tmp = josephus(n,k);
                  printf("Case %d: %d\n",i,tmp);
            }
      }
      return 0;
}
int josephus(int n,int k)
{
      if(n == 1)
      return 1;
      else
      return (josephus(n-1,k)+k-1)%n+1;
}
