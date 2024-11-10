# 20241024-homework-basic
#include<iostream>
using namespace std;

int main(){
    int a;
    cin >> a;
    for (int i = 1;i <= a;i++){
        for(int b = 0;b <=a-i;b++){
        cout << " ";
    }
    for(int c = 1;c <=i;c++){
        cout << "#";
    }
    for(int d = 1;d <4;d++){
        cout << " ";
    }
    for(int e = 1;e <=i;e++){
        cout << "#";
    }
        cout << endl;
 }
}
