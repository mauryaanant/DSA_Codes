## Reverse a Number
```cpp
#include <iostream>
using namespace std;

int reverse(int n) {
    int rev = 0;
    while(n > 0) {
        rev = rev * 10 + n % 10;
        n = n / 10;
    }
    return rev;
}

int main() {
   int x = reverse(123456);
   cout << x << endl;
   return 0;
}
```
