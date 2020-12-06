```C
/*****************************************************************************
/* C Program to print the environment variables and values stored in them,   *                 
/* for the current terminal session.                                         *
/****************************************************************************/

#include <stdio.h>
#include <stdlib.h>

int main(int argc, char *argv[], char *envp[])
{

  printf("\n---------------------------------------------------------------\n");
  printf("The Environment:\n");
  
  int i = 0;
  while(envp[i] != NULL)
  {
    printf("%s\n", envp[i]);
    i++;
  }

  printf("\n----------------------------------------------------------------\n");
  return 0;
  
}

```
