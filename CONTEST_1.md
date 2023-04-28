### CONTEST_1
**Bài 1. Tính toán giá trị của biểu thức**
``` 
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    long long x;
    scanf("%lld\n",&x);
    printf("%lld\n",x*x*x+3*x*x+x+1);
    return 0;
}
```
**Bài 2. Tính toán giá trị biểu thức 2**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    long long a,b,c;
    scanf("%lld %lld %lld\n",&a,&b,&c);
    printf("%lld\n",a*(b+c)+b*(a+c));
    return 0;
}
```
** Bài 3. Đổi nhiệt độ**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    float C;
    scanf("%f\n",&C);

    printf("%.2lf\n",(C*9/5)+32);
    return 0;
}
```
**Bài 4. Chu vi và diện tích hình tròn**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>
#define PI 3.14
int main() {

    int R;
    scanf("%d\n",&R);
    printf("%.4lf ",2*PI*R );
    printf("%.4lf",PI*R*R);
    return 0;
}
```
**Bài 5. Khoảng cách Euclid.**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h> 
 
int main() {

    float x1,x2,y1,y2;
    scanf("%f %f %f %f/n",&x1,&y1,&x2,&y2);
    printf("%.2lf\n",sqrt(pow(x2-x1,2)+pow(y1-y2,2)));
    return 0;
}
```
**Bài 6. Luyện tập viết câu điều kiện**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main (){
    int x;
    scanf("%d\n",&x);
    
    //1
    if( x % 2 ==0){
        printf("YES\n");
    }
    else {
        printf("NO\n");
    }
    //2
    if ( x % 3 == 0 && x % 5 == 0){
        printf("YES\n");
    }
    else {
        printf("NO\n");
    }
    //3
    if ( x % 3 == 0 && x % 7 !=0 ){
        printf("YES\n");
    }
    else {
        printf("NO\n");
    }
    //4 
    if( x % 3 == 0 || x % 7 == 0){
         printf("YES\n");
    }
    else {
         printf("NO\n");
    }
    //5
    if ( x > 30 && x < 50 ){
        printf("YES\n");
    }
    else {
        printf("NO\n");
    }
    //6
    if (( x >= 30 ) && (x % 2 == 0|| x % 3 == 0|| x % 5 ==0)){
         printf("YES\n");
    }
    else {
        printf("NO\n");
    }
    //7
    int r = x % 10 ;
    if (( x >= 10) && (x <= 99) && (r % 2 == 0|| r % 3 == 0|| r % 5 == 0|| r % 7 == 0)){
        printf("YES\n");
    }
    else {
        printf("NO\n");
    } 
    //8
    if (( x <= 100) && (x % 23 == 0)){
        printf("YES\n");
    }
    else {
        printf("NO\n");
    }
    //9 
    if (( x < 10) || (x > 20 )){
        printf("YES\n");
    }
    else {
        printf("NO\n");
    }
    //10
    if ( r % 3 == 0){
        printf("YES\n");
    }
    else {
        printf("NO\n");
    }
    return 0;
}

```
**Bài 7. Số lớn nhất và nhỏ nhất**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int a,b;
    scanf("%d %d\n", &a,&b);
    int x = a/b*b;
    int y;
    
    if (a % b == 0){
        y = a;
    }
    else {
        y = (a / b +1)*b;
    }
    printf ("%d\n%d",x,y);
 
    return 0;
}
```
**Bài 8. Tổng, hiệu, tích, thương**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int a,b;
    scanf("%d %d\n", &a,&b);
    
    int tong = a+b;
    int hieu = a-b;
    long long tich = 1ll*a*b;
    printf("%d\n%d\n%lld\n", tong, hieu,tich);
    if (b ==0){
        printf("INVALID\n");
    }
    else {
        double thuong = (double) a/b;
        printf ("%.4lf\n",thuong);
    }
    return 0;
}
```
**Bài 9.Kiểm tra năm nhuận**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int x;
    scanf("%d\n",&x);
    if (x % 400 ==0 || x % 4 ==0 && x % 100 !=0){
        printf("YES\n");
    }
    else {
        printf("NO\n");
    }
    return 0;
}
```
**Bài 10. Tam giác hợp lệ**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int a, b, c;
    scanf("%d %d %d",&a,&b,&c);
    if ( a > 0 && b > 0 && c > 0 && a +b > c && a + c > b && b +c > a){;
        printf ("YES\n");
    }
    else{
        printf("NO\n");
         }
    return 0;
}
```
