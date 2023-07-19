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
#Bài 16. Đếm số lượng chữ số của N
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
    if (n==0){
    	printf("1\n");
		return 0;
	}
    long long cnt=0;
    while(n!=0){
        ++cnt;
        n/=10;
    }
    printf("%lld",cnt);
    return 0;
}

```
---
# Bài 17. Tính tổng chữ số của N
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
    while(n){
        sum += n%10;
        n/=10;
    }
    printf("%lld",tong);
    return 0;
}
```
---
#Bài 18. Đếm chữ số nguyên tố của số nguyên
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
    long long cnt=0;
    while(n){
        int r = n%10;
        if(r ==2|| r==3||r==5||r==7)
        ++cnt;
        n/=10;
    }
    printf("%lld",cnt);
    return 0;
}
```
---
#Bài 19.Mua bia
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
	int n; scanf("%d",&n);
	int kq=n/28;
	int vo = kq;
	while(vo>=3){
		int bia = vo/3;
		kq+=bia;
		vo=bia + vo%3;
		}
	printf("%d",kq);  
    return 0;
}
```
---
#Bài 20.Biểu diễn số nguyên
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n;
    scanf("%d",&n);
    if(n<=1){
        printf("-1\n");
    }
    else{
        printf("%d\n",n/2);
        if(n%2==0){
            for(int i=0;i<n/2;i++){
                printf("2 ");
            }
        }
        else{
            for(int i=0; i<n/2 -1;i++){
                printf("2 ");
            }
            printf("3 ");    
        }
    }
    return 0;
}
```
---
#Bài 21.Vẽ hình 1
```
 #include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
   int n;
   scanf("%d",&n);
   for(int i=1; i<=n;i++){
		for(int j=1;j<=n;j++){
			printf("*");
		}
		printf("\n");
   }
   printf("\n");
   
   for (int i=1; i<=n;i++){
   		for(int j=1;j<=n;j++){
   			if(i==1||i==n||j==1||j==n){
   				printf("*");
   			}
   			else{
   				printf(" ");
			   }
			   
		   }
		printf("\n");
   }
   printf("\n");
   
   for (int i=1;i<=n;i++){
   		for(int j=1;j<=n;j++){
   			if(i==1||i==n||j==1||j==n){
   				printf("*");
			   }
			else{
				printf("#");
			}
		   }
		printf("\n");
   }
   printf("\n");
   
   for(int i=1; i<=n; i++){
        for(int j =1;j<=n;j++){
            if(i==1 || i==n || j==1 || j==n){
                printf("%d ",i);
            }
            else printf("  ");
        }
        printf("\n");
    }
   return 0;
}
```
---
