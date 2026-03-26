# M6-D2
AIM:
Write a C program to find character 'I' is vowel or consonant using pointer.
PROGRAM:
```
#include <stdio.h>
int main()
{
    char a,*p;
    scanf("%c",&a);
    p=&a;
    if((*p=='I')||(*p=='A')||(*p=='E')||(*p=='O')||(*p=='U'))
    {
        printf("%c is Vowel.",*p);
    }
    else
    {
        printf("%c is consonant.",*p); 
    }
}
```
OUTPUT:
<img width="718" height="298" alt="image" src="https://github.com/user-attachments/assets/f7ba1e76-7348-47fa-b11c-ec7aaf12cd62" />
RESULT:
Thus the code run successfully!
