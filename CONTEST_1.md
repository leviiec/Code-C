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
**Bài 11. Kiểm tra tam giác**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int a,b,c;
    
    scanf("%d %d %d",&a, &b, &c);
    if ( a > 0 && b > 0 && c > 0 && a + b > c && a + c > b && b + c > a){
   
        if ( a == b && b == c ){
            printf("1");
        }
        else if ( a == b || a == c || b == c ){
            printf ("2");
       }
        else if ( a*a == b*b +c*c || b*b == c*c + a*a  || c*c == a*a + b*b  ){
            printf("3");
        }
        else {
            printf("4");
        }
    }
    else {
        printf("INVALID\n");
    }
    return 0;
}
```
**Bài 12. Số ngày của tháng**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int t,n;
    scanf("%d %d\n",&t,&n);
    if (t >=1 && t <= 12 && n > 0){
        if( t == 1|| t == 3|| t == 5|| t == 7|| t ==8|| t == 10|| t ==12)
            printf("31");
    
        else if ( t == 4|| t == 6|| t ==9|| t == 11)
            printf("30");
        
    else {
        if ( n % 400 == 0||( n % 100 !=0 && n % 4 == 0))
            printf ("29");
        
        else
            printf("28");
  
        }
    }
    else 
        printf("INVALID\n");
    
    return 0;
}
```
**Bài 13. Đổi ngày sang năm, tuần, ngày**

```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int n;
    scanf("%d",&n);
        
    printf("%d ",n/365);
    printf("%d ",(n%365)/7);
    printf("%d ",(n%365)%7);

    return 0;
}
```
**Bài 14. Xếp loại học sinh**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    float a,b,c,d;
    scanf("%f %f %f %f",&a,&b,&c,&d);
    float TB = ( a + b + 2*c + 3*d)/7;
    if ( TB >=8 )
        printf("GIOI");
         else if ( TB >= 6.5)
             printf("KHA");
         else if ( TB >= 5)
                 printf ("TRUNG BINH");
    else printf("YEU");
     
    return 0;
}
```
**Bài 15. Mua nước**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    long long n,a,b;
    scanf("%lld %lld %lld\n",&n,&a,&b);
    
    if (a * 2 <= b){
        printf("%lld",n*a);
    }
    else {
        if ( n % 2 == 0)
            printf("%lld",n / 2 * b);
        else 
            printf("%lld",n / 2*b +a);
            
    }
    return 0;
}
```
** Bài 16. Kí tự kế tiếp**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    char c;
    scanf("%c",&c);
    
    if (c == 'z' ||c == 'Z'){
       
        printf("a");
    }
    else if (c >= 'A' && c < 'Z'){
        c += 32 + 1;
        printf("%c",c);
    }
    else{
         c += 1;
        printf ("%c",c);
     }
        
    return 0;
}
```
**Bài 17. Kiểm tra chữ cái**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    char c;
    scanf("%c",&c);
    if ( c >= 'a' && c<= 'z')
        printf("LOWER");
        else if ( c >= 'A' && c<= 'Z')
            printf("UPPER");
        else if ( c >= '0' && c <= '9')
            printf("DIGIT");
    else 
        printf("SPECIAL");
    return 0;
}
```
**Bài 18. Chuyển đổi in hoa in thường**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    char c;
    scanf("%c",&c);
    if ( c >= 'a' && c <= 'z')
        c -=32;
    else if (c >= 'A' && c <= 'Z')
        c +=32;
    printf("%c",c);
    return 0;
}
```
**Bài 19. Domino**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n,m;
    scanf("%d %d",&m,&n);
    if (n % 2 == 0)
        printf("%lld",1ll*n / 2 * m);
    else 
        printf("%lld",1ll*n / 2 * m + m / 2);
    
    return 0;
}
```
**Bài 20. Lát đá quảng trường**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int n,m,a;
    scanf("%d %d %d",&n,&m,&a);
    int doc,ngang;
    if (n % a == 0)
        doc = n/a;
    else 
        doc = n / a +1;
    if (m % a == 0)
        ngang = m / a;
    else 
        ngang = m / a + 1;
    printf( "%lld", 1ll*ngang*doc);
    return 0;
}

```
**Bài 21. Frog**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {

    int a,b,k;
    scanf("%d %d %d",&a,&b,&k);
    int trai,phai;
    if (k % 2 == 0)
        trai = phai = k / 2;
    else {
        trai = k / 2;
        phai = trai + 1;
        
    }
    printf("%lld", 1ll*phai*a-1ll*trai*b);
    return 0;
}
```
**Bài 22. Đồng xu**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    long long n,s;
    
    scanf("%lld %lld ",&n,&s);
    if (s %  n==0)
        printf("%lld",s / n);
    else
      printf("%lld",s / n + 1);
   
    return 0;
}
```
**Bài 23. Doremon leo cầu thang**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n,m;
    scanf ("%d %d",&n,&m);
    int min, max = n;
    if (n % 2 == 0)
        min = n / 2;
    else 
        min = n /2 +1;
    int x = (min + m -1 )/m*m;
    if (x <= max)
        printf("%d",x);
    else 
        printf("-1");
    
    return 0;
}
```
**Bài 24. Đường đi ngắn nhất**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int d1,d2,d3;
    
    scanf("%d %d %d",&d1,&d2,&d3);
    
    int s1=d1+d3+d2;
    int s2=d1*2+d2*2;
    int s3=d1+d3+d3+d1;
    int s4=2*(d2+d3);
    
    printf("%d",(int)fmin(fmin(s1,s2), fmin(s3,s4)));
       
    return 0;
}
```
**Bài 25. Đổi tiền**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
   
    int n;
    
    scanf("%d",&n);
    
    int x=0;
    x+=n/100; n=n%100;
    x+=n/20; n=n%20;
    x+=n/10; n=n%10;
    x+=n/5; n=n%5;
    x+=n;
    printf("%d",x);

       
    return 0;
}
```
**Bài 26. Số lớn nhất nhỏ nhất trong 4 số**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    long long a,b,c,d;
   
    scanf("%lld %lld %lld %lld",&a,&b,&c,&d);
   
    long long min=a, max=a;
   
    if(b<min) min=b;
    if(c<min) min=c;
    if(d<min) min=d;
    if(b>max) max=b;
    if(c>max) max=c;
    if(d>max) max=d;
    
    printf("%lld %lld",max,min);
      
    return 0;
}
```
**Bài 27. Làm tròn số**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    double a;
    
    scanf("%lf",&a);
    printf("%d",(int)round(a));
     
    return 0;
}
```
**Bài 28. Cấp số cộng**
```
include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n,u1,d;
    
    scanf("%d %d %d",&n,&u1,&d);
    long long un=u1+1ll*(n-1)*d;
    long long S=n*(u1+un)/2;
  
    printf("%lld",S);
 
    return 0;
}
```
**Bài 29. Cấp số nhân**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a,b,c,d;
    
    scanf("%d %d %d %d",&a,&b,&c,&d);
    
    if(b % a ==0){
        int x = b / a;
        b *= x;
        if( b == c){
            c *= x;
            if( c == d){
                printf("YES");
            }
        }
    }
    else
        printf("NO");
    
    return 0;
}
```
**Bài 30. Tổ hợp chập 2**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int n;
   
    scanf("%d",&n);
    printf("%lld",1ll*n*(n-1)/2);
  
    return 0;
}
```
**Bài 31. Bizon the Champion**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a1,a2,a3,b1,b2,b3,n;
    
    scanf("%d %d %d %d %d %d\n",&a1,&a2,&a3,&b1,&b2,&b3);
    scanf("%d",&n);
    
    int x=(int)ceil(((double)a1+a2+a3)/5);
    int y=(int)ceil(((double)b1+b2+b3)/10);
    
    if(x<n){
        if (y<=(n-x))
            printf("YES");
        else 
            printf("NO");
    }
    else 
        printf("NO");
    return 0;
}
```
**Bài 32. Ghép số**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int k2,k3,k5,k6;
    
    scanf("%d %d %d %d",&k2,&k3,&k5,&k6);
    
    int x = fmin(k2,fmin(k6,k5));
    if(x == k2)
        printf("%lld",x*256ll);
    
    else{
        if((k2-x)<k3)
            printf("%lld",256ll*x+32ll*(k2-x));
        
        else
            printf("%lld",256ll*x+32ll*k3);
        
    }
    return 0;
}
```
**Bài 33. Chia tiền**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a,b,c,n;
    scanf("%d %d %d %d",&a,&b,&c,&n);
    
    int tong = a+b+c+n;
    if(tong % 3==0){
        int x = tong/3;
        if(x >= a && x >= b && x >= c)
            printf("YES");
    
        else 
            printf("NO");
    }
    else 
        printf("NO");

    return 0;
}
```
**Bài 34. Sự hào phóng**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    int a,b,c,d,e;
   
    scanf("%d %d %d %d %d",&a,&b,&c,&d,&e);
    
    if ((a + b + c + d + e) % 5 == 0 &&( a + b + c + d + e) != 0)
       printf("%d",(a + b + c + d + e )/5);
    else printf("-1");
   
    return 0;
}
```
**Bài 35. HPNY**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    
    int h,m;
    
    scanf("%d %d",&h,&m);
    int x = 24*60; 
    printf("%d",x - ( h * 60 + m));
    
    return 0;
}
```
**Problem E**
```
#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    
    double a,b,c;
    scanf("%lf %lf %lf",&a,&b,&c);
    if( a == 0 && b == 0 && c == 0)
        printf("VO SO NGHIEM");
    
    else if( a == 0 && b == 0 && c != 0)
        printf("VO NGHIEM");
    
    else if(a == 0)
        printf("%.2lf",-c/b);
    
    else{
        double delta = b*b-4*a*c;
        if( delta<0) 
            printf("VO NGHIEM");
        else if (delta == 0) 
            printf("%.2lf",-b/(2*a));
        else{
            
            double x1=(-b-sqrt(delta))/(2*a);
            double x2=(-b+sqrt(delta))/(2*a);
            printf("%.2lf %.2lf",fmin(x1,x2), fmax(x1,x2));
        }
    }
        return 0;
 }
 ```
