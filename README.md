#include<stdio.h>
#include<math.h>
int main()
{
  float tractLand,tractLandAcres;
  scanf("%f",&tractLand);
  tractLandAcres=(float)tractLand/43560;
  printf("%.2f sq.ft is equal to %.2f acres", tractLand, tractLandAcres);
  return 0;
}
