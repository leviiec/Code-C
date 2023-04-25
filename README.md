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
    
    float n;
    scanf("%f\n",&n);
    printf("%.2f\n",sqrt(n));
    printf("%.3f\n",cbrt(n));
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
