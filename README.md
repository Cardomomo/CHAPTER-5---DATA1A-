# CHAPTER5-DATA1A



    #include <stdio.h>

    //programm to convet C a F.

    int main(void) {

    float C, F;

      printf("INSERT CENTIGRADES\n");
      scanf("%f", &C);
    F = ((9./5)*C)+32;
      printf("FARENHEIT: %f", F);
      return 0;
    }
