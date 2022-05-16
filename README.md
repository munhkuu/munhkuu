- 👋 Hi, I’m @munhkuu
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
munhkuu/munhkuu is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
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
  
  
  
  
  
