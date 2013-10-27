#Rozwiazania

Zadanie 1

```c
#include <stdio.h>
int main () {
int i;
int tabela[]={1,2,4,6,12};
for (i=4; i>=0; i=i-1)
printf("%i", tabela[i]);
return 0;
}
```


Zadanie 2

```c
#include <stdio.h>
int main () {
int i.n.suma;
suma=0;
printf("Podaj liczbę\n");
scanf("%i",&n);
for (i=1; i<=n; i=i+1)
suma=suma+i*i;
printf("Podana liczba to %i.\n",suma);
}
```


Zadanie 3

```c
#include <stdio.h>

main ()
{
  int n1,n2,n3,a,b;
n1=5+3*8/2-3;
n2=2%2+2*2-2/2;
n3=2*4*(5+9/2);
  printf("n1=%i.\n",n1);
  printf("n2=%i.\n",n2);
  printf("n3=%i.\n",n3);
}
```

Zadanie 4

```c
#include <stdio.h>

int main()
{
int a,tabela[]={1,2,4,6,12};
for (a=4; a>=0; a--)
printf("%i ",tabela[a]);
printf("\n");

return 0;
}
```

Zadanie 5

```c
#include <stdio.h>

main()
{
int a,b;
b=2010;
for (a=1; a<=2010; a=a*2)
printf("%i ",a)

}
```

Zadania 6

```c
#include <stdio.h>

main()
{
int a,b;
a=1;
while (a<=2010){
printf("%i ",a);
a=a*2;
}

}
```


Zadanie 7

```c
#include <stdio.h>
main(){
int liczba=8;
int i;
int wynik[20];
printf("Podaj liczbę w systemie 10: ");
scanf("%i",&liczba);
i=0;
while(liczba!=0)
{
    wynik[i]=liczba%2;
    printf(" RESZTA %i przez 2 = %i ",liczba,wynik[i]);
    liczba=liczba/2;
    printf(" PO PODZIELENIU LICZBA =  %i \n", liczba);
    i++;
}
printf("\nWYNIK:");
for(i=i-1;i>=0;i--) printf(" %i ",wynik[i]);


}
```
