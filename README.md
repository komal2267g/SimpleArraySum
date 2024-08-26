//SimpleArraySum
#include<stdio.h>
int SimpleArraySum(int arr[], int n){
int sum = 0;
for(int i=0; i<n; i++){
sum += arr[i];
}
return sum;
}
int main(){
int n;
scanf("%d", &n);
int arr[n];
for(int i=0; i<n; i++){
scanf("%d", &arr[i]);
}
int result = SimpleArraySum(arr, n);
printf("%d\n",result);
return 0;
}
