##CONTEST0

**Bài 1. Print Hello World**
```
  #include <stdio.h>
  #include <string.h>
  #include <math.h>
  #include <stdlib.h>

int main() {
    int a;
    scanf("%d",&a);
    printf("%d\n",a);
    printf("%s\n","Hello World !");
    printf("%s\n","28tech C++ programming !");
 
    return 0;
}
```
**Bài 2. Print number**
```
#include <stdio.h>

int main() {
    int x;
    long long y;
    char c;
    float f;
    double d;
    
    scanf("%d\n",&x);
    scanf("%lld\n",&y);
    scanf("%c\n",&c);
    scanf("%f\n",&f);
    scanf("%lf\n",&d);
    
    printf("%d\n",x);
    printf("%lld\n",y);
    printf("%c\n",c);
    printf("%.2f\n",d);
    printf("%.9lf\n",d);
   
    return 0;
}
```

**Bài 3. Print expression**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    
    int x,y,z,t;
    
    scanf("%d %d %d %d\n",&x,&y,&z,&t);
    printf("%d,%d,%d,%d\n",y,z,x,t);
    
    long long sum =x+y+z+t;
    printf("%lld\n",sum);
   
   long long bieu_thuc= x-y+z*t;
    printf("%lld\n",bieu_thuc);
         return 0;
}
```

**Bài 4. Hàm pow**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int a,b;
    scanf("%d %d\n",&a,&b);
    printf("%lld",(long long)pow(a,b));
  
    return 0;
}
```
**Bài 5. Hàm sqrt và cbrt**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    
    float x;
    scanf("%f\n",&x);
    printf("%.2f\n",sqrt(x));
    printf("%.3f\n",cbrt(x));
    return 0;
}
```
**Bài 6. Hàm ceil, floor, round**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
   
    double x;
    
    scanf("%lf\n",&x);
    
    printf("%d\n",(int)floor(x));
    printf("%d\n",(int)ceil(x));
    printf("%d\n",(int)round(x));
       
    return 0;
}
```
**Bài 7. Chữ số cuối cùng và 2 chữ số cuối cùng**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    long long x;
    scanf("%lld\n",&x);
    
    printf("%d\n",x%10);
    printf("%d\n",x%100)
    return 0;
}
```
**Bài 8. Phép chia**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a,b;
    scanf("%d %d\n",&b,&a);
    printf("%d\n", a/b);
    printf("%.2f\n",(float)a/b);
    
    return 0;
}
```
**Bài 9. Xóa số**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    long long x;
    scanf("%lld\n",&x);
    printf("%lld\n",x/1000);
    
    return 0;
}
```

**Bài 10. Phép chia dư**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    
    int a,b;
    scanf("%d     %d\n",&a,&b);
    printf("%d\n",a%b);    
    
    return 0;
}
```
**Bài 11. Nhân chia**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int x;
    scanf("%d\n",&x);
    printf("%lld\n",x*2);
    printf("\n%lld\n",x*10);
    printf("\n%d\n",x/2);
    printf("\n%.3f\n",(float)x/2);
    return 0;
}
```
**Bài 12. Hàm F(x, y)**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int x,y;
    scanf("%d %d\n",&x,&y);
    printf("%lld\n",5*x+2*y+x*y);
    return 0;
}
```

**Bài 13. Lớn nhất, nhỏ nhất**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int x,y,z,t;
    scanf("%d\n",&x);
    scanf("%d\n",&y);
    scanf("%d\n",&z);
    scanf("%d\n",&t);
    printf("%d\n",(int)fmax(x,y));
    printf("%d\n",(int)fmin(z,t));
    printf("%d\n",(int)fmax(x,fmax(y,z)));
    printf("%d\n",(int)fmin(x,fmin(y,fmin(z,t))));

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */    
    return 0;
}
```

**Bài 14. Number in range**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int a,b;
    scanf("%d %d\n",&a,&b);
    printf("%d\n",b-a+1);
    return 0;
}
```
** Bài 15. Mua vở**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    long long a,b;
    scanf("%lld %lld\n",&a,&b);
    printf("SO VO MUA DUOC LA : %lld !!!!!",(long long)floor(a/b));
    return 0;
}
```
**
