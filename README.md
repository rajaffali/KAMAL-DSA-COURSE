#include<iostream>
using namespace std;
int main(){
int n;
cin>>n;
int i=2;
while(i<n){
if(n%i==0){
cout<<"not a prime no "<<endl;
}
else{
cout<<"prime for "<<i<<endl;
}
i++;
}
return 0;
}
