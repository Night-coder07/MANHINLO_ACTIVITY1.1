#include <bits/stdc++.h>
using namespace std;
int main() {
int arr1[] = {99,91,94,96};
int n = sizeof(arr1)/sizeof(arr1[0]);
sort(arr1, arr1+n);
cout << "\n List of Array after sorting is: ";
for (int i = 0; i < n; ++i)
cout << arr1[i] << " ";
return 0;
}
