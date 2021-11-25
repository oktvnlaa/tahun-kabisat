# tahun-kabisat
#include <iostream>
using namespace std;

int main(){
	int a;
	int b;
	
	cout<<"Masukkan tahun : ";
	cin>>a;
	
	if (tahun%4==0 && tahun%100!=0 || tahun%400==0){
	cout<< "Tahun "<< a <<" adalah tahun kabisat"<<endl;
	
}	else{
	cout<<"Bukan tahun kabisat";
}
	return 0;
}
