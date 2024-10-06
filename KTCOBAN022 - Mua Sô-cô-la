#include<bits/stdc++.h>

using namespace std;
int main(){
	int t;
	cin >> t;
	while(t--){
		int x, y, m;
		cin >> x >> y >> m;
		int dem = 0, tong = 0;
		while(m >= x){
			m -= x;
			tong++;
			dem++;
			if(dem == y){
				tong ++;
				dem = 1;
			}
		}
		cout << tong <<endl;
	}

return 0;
}
