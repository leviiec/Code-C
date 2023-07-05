##CONTEST_2

#Bài 1. Tổng tự nhiên liên tiếp
```
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    int n;
    scanf("%d",&n);
    long long sum=0;
    for(int i =1; i <=n; i++){
        sum += i;
    }
    printf("%lld",sum);
    return 0;
}
```
---
