- š Hi, Iām @munhkuu
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
munhkuu/munhkuu is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->




#include <iostream>
using namespace std;
  
int arr[101];
int main () {
  
  // cin a
  // sum = c
  int a, c=0;
  cin >> a;
  
  // cin Massive a
  for ( int i=0; i < a; i++ ) {
    cin >> arr[i];
  }
  
  // sum of Massive a
  for ( int i=0; i < a; i++ ) {
    c = c + arr[i];
  }
  
  cout << c;
  
  return 0;
}
  
  
  
  
  
