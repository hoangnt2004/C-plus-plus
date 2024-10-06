#include <bits/stdc++.h>
using namespace std;

int main()
{
	int t;
	cin >> t;
	while(t--){
		long long num , originalNum , result = 0;
		int n = 0;
		cin >> num;
		originalNum = num ;
		while(originalNum > 0){
			originalNum /= 10;
			n++;
		}
		originalNum = num;
		while(originalNum > 0){
			result += pow(originalNum % 10, n);
			originalNum /= 10;
		}
		if(result == num){
			cout <<"1"<<endl;
		}else{
			cout <<"0"<<endl;
		}
	}
	return 0;
}
