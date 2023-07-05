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
#Bài 2. Tổng bình phương
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
    long long tich =0;
    for(int i=1; i <=n;i++){
        tich +=1ll*i*i;
    }
    printf("%lld",tich);
    return 0;
}
```
---
#Bài 3. Tổng bội của 3
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
    for(int i=0; i<=n;i+=3){
        sum+=i;
    }
    printf("%lld",sum);
    return 0;
}
```
---
#Bài 4. Tổng nghịch đảo
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
    double sum=0;
    for(int i=1; i<=n;i++){
        sum+=1.0/i;
    }
    printf("%.3lf\n",sum);
    return 0;
}
```
---
#Bài 5. Tổng nghịch đảo
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
    double sum=0;
    for(int i=1; i<=n;i++){
        sum+=1.0/(i*2);
    }
    printf("%.5lf\n",sum);
    return 0;
}
```
---
#Bài 6. Tổng ước
```
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    long long n;
    scanf("%lld",&n);
    long long sum =0;
    for(int i=1;i<=sqrt(n);i++){
        if(n%i==0){
        sum +=i;
        if(i !=n/i)
        sum +=n/i;
        }
    }
    printf("%lld\n",sum);
    return 0;
}
```
---
