#include <iostream>
#include <math.h>
using namespace std;
int main() {
    int t;
    cin>>t;
    while(t--){
    long long int n;
    cin>>n;
    string strNum = to_string(n);
    int length = strNum.length();
    int last=n%10;
    long long int o=(pow(10,length-1));
    int first=n/o;
      cout<<last+first<<endl;
    }
    return 0;
}
