1)Verilenler- kolmputerin yaddaşında yer ayırmaq və burda hər hansı bir dəyəri saxlamaq üçün istifadə edilir.
Müxtəlif programıaşdırma dillərində bu verilenləri müxtəlif ola bilər. C# dilində integer float decimal 
boolean kimi verilənərin tipləri var 
#include <stdio.h>

main() {
   int a;   
   int b;
}
Burada  yaddaşda müxtəlif 2 yer ayırır.          
2)Məlumat növləri yaddaşda nə qədər yer ayırlmalı olduğumuz yəni hər hansı bir interval qoyur.String data novləridə vardır ki, hər hansı string dəyəri ilə 
işləməyə xidmət edir. String str = "QWERTY";
 Meselen 
char(-128 to 127 or 0 to 255)  unsigned char(0 to 255)	signed char(-128 to 127)int(32,768 to 32,767 or -2,147,483,648 to 2,147,483,647)	
float(1.2E-38 to 3.4E+38) double(2.3E-308 to 1.7E+308	) long double(3.4E-4932 to 1.1E+4932)	
3)+ - / * %  kimi riyazi operatorlar var . 
+ toplma - çıxma / bölmə * vurma % isə qalığı tapmaq funkiyasını yerinə yetirir.
bəzi proqramlaşdırma dillərində / əvəzinə div , % əvəzinə isə mod riyazi opratorundan istifadə olunur.
+ ola bilər birləşdirmə vezfəsini icra etsin.
4)&&- bu və operatorudur, hər iki operand 1 dirsə onda 1 qiymət alir (*  yerinə yetirir) (A && B) 1&&1=1 1&&0=0 0&&1=0 0&&0=0.

|| -bu və ya opertatorudur. (+ yerinə yetirir) (A || B) 1||1=1 1||0=1 0||1=1 0||0=0
! - yox opertatorudu. Məsələn tutaq ki, hər iki operand doğrudu ! bu  onu səhv edəcək.
5) e1 ? e2 : e3 belə bir şərt operatoru var ki əgər e1 şərtdirsə, əgər şərt ödəbirsə e2 əks halda e3 cavab olaraq götürülür.
