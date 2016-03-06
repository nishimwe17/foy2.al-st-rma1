#include <stdio.h>
#include <ctype.h>

int main(void) 
{
  int c;
  for ( ; ; ) 
  {
    c = getchar();
    

    if(islower(c))
      c = toupper(c);
    else
      c = tolower(c);

    putchar(c);
  }
  return 0;
}
