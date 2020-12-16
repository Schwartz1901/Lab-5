#include<iomanip>
#include<stdlib.h>
#include<iostream>
using namespace std;
int main() {

    int n;
    cin >> n;
    double s[1000];
    int poscount = 0;
    int negcount = 0;
    for (int i = 0; i < n; i++) {
        cin >> s[i];
    }
    for (int i = 0; i < n; i++) {
	
    if (s[i] >= 0) poscount += 1;
    else negcount += 1;
}
cout << poscount << " " << negcount;
    return 0;
}
