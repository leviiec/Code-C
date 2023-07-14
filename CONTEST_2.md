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
---
#Bài 7. Liệt kê ước
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
    int dem=0;
    for (int i=1; i<=n; i++){
        if(n % i==0){
            ++dem;
        }
    }
    printf("%d\n",dem);
    for (int i=1; i<=n;i++){
        if (n %i==0){
            printf("%d ", i);
        }
    }
    
    return 0;
}
```
    printf("%lld\n",sum);
    return 0;
}
---
#Bài 8. Liệt kê số chính phương
```
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    long long n;
    scanf("%lld", &n);
    for (int i=1; i<=sqrt(n);i++){
        printf("%lld ", 1ll*i*i);
    }
    return 0;
}
```
---
#Bài 9. Tích các ước
```
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    long long n;
    scanf("%lld", &n);
    long long tich=1;
    for(int i =1; i<=n;i++){
        if (n % i ==0){
        	tich*=i;
		}
        
    }
    printf("%lld", tich);
    return 0;
}
```
---
#Bài 10. Kiểm tra số 2022
```
#include <cmath>
#include <cstdio>
#include <vector>
#include <iostream>
#include <algorithm>
using namespace std;


int main() {
    int n;
    scanf("%d", &n);
    int check =0;
    for(int i=1; i <= n;i++){
        int tmp=0;
        scanf("%d",&tmp);
    if(tmp==2022){
        check=1;
    }
    }
    if (check == 1)
        printf("YES\n");
    else 
        printf("NO\n");
    return 0;
}
```
---
#Bài 11. Tổng chẵn lẻ
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
    long long tong =0;
    for( int i=1; i <= n;i++){
        if (i % 2 ==0){
            tong+=i;
        }
        else 
            tong-=i;
    }
    printf("%lld",tong);
    return 0;
}
```
#Bài 12. Tổng bội 2
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
    long long tong=0;
    for( int i=1; i<=n; i++){
            tong+=2*i;
        
    }
    printf("%lld", tong);
    return 0;
}
```
---
#Bài 13. Tổng lẻ
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
    long long tong=0;
    for( int i=1; i<=n; i++){
            tong+=2*i-1;
        
    }
    printf("%lld", tong);
    return 0;
}
```
---
#Bài 14. Tổng lập phương
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
    long long tong=0;
    for(int i=1; i<=n;i++){
        tong+=1ll*i*i*i;
    }
    printf("%lld",tong);
    return 0;
}
```
---
#Bài 15. Tính giai thừa
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
    long long gt=1;
    for( int i =1; i <= n;i++){
        gt*=i;
    }
    printf("%lld", gt);
    return 0;
}
```
---
