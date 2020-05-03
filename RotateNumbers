/******************************************************************************

                            Online C Compiler.
                Code, Compile, Run and Debug C program online.
Write your code in this editor and press "Run" button to compile and execute it.

*******************************************************************************/

#include <stdio.h>

int
main ()
{
  char inputString[5], temp;
  // variables to hold length and number of rotations
  int len, nor,actualLength;
  scanf ("%[^\n]s", inputString);
  scanf ("%d", &nor);

  printf ("Array before rotation: \n");
  printf ("%s", inputString);
  printf ("\n");
  len = sizeof (inputString) / sizeof (inputString[0]);
  printf ("%d", len);
  printf ("\n");
  
 
  for (int i = 0; i < nor; i++)
    {
      temp = inputString[0];
      for (int j = 0; j < len; j++)
	{

	  if (j == (len - 1))
	    {
	      inputString[j] = temp;
	    }
	  else
	    {
	      inputString[j] = inputString[j + 1];
	    }
	}
    }

  printf ("Array after left rotation: \n");
  printf ("%s", inputString);
  return 0;

}
