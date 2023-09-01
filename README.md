#include <iostream>
#include <math.h>
#include <iomanip>
using namespace std;

int main(){
	float n;cin>>n; float S;
	for (int i=1;i<=n;i++){
	 S+=1.0*1/(2*i+1);
}
	cout<<fixed<<setprecision(2)<<S+1;
	return 0;
}
