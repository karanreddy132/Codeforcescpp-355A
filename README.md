# Codeforcescpp-355A
#include <bits/stdc++.h>
using namespace std;

int main() {
	int k, d;
	cin >> k >> d;
  if(k==0 && d > 1)
    cout << "No Solution";
  else{
    for(int i=1;i<=k-1;i++){
      cout << 9;
    }
    cout << d;
  }
  
	return 0;
}
