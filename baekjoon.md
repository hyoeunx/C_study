## 소수점(1008)
a, b를 int로 받고 출력할 때 실수로 형 변환을 한다.
<pre>
#include <stdio.h>
int main () {
    int a, b;
    scanf("%d %d", &a, &b);
    printf("%.9f", (double)a / b);
    return 0;
}
</pre>
a, b를 double로 받고 출력한다.
<pre>
#include <stdio.h>
int main()
{
    double a, b;
    scanf("%lf %lf", &a, &b);
    printf("%.9lf", a/b);
    return 0;
}
</pre>

## 삼중자(10926)
\를 사용하여 삼중자로 해석되지 않게 한다.
삼중자|문장 부호 문자
:---:|:---:
??=|	#
??(|	[
??/|	\
??)|	]
??'|	^
??<|	{
??!|	\||
??>|	}
??-|	~

## 한 자리씩 출력(2588)
<pre>
#include <stdio.h>
int main()
{
    int b;
    scanf("%d", &b);
    printf("%d\n", (b/100));
    printf("%d\n", (b%100 / 10));
    printf("%d\n", (b%10));
    return 0;
}
</pre>