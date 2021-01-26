#include <numeric>
using namespace std;

std::vector<int> xbonacci(std::vector<int> signature, int n)
{
  int x = signature.size(); // determines Xbonacci # elements
  if (x > n) {
    signature.resize(n);
    return signature;
  }  
  for (int i = x; i < n; ++i) {
    int tempVal = 0;
    for (int k = 1; k <= x; ++k) tempVal += signature[i - k];
    signature.push_back(tempVal);
  }
  return signature;
}

