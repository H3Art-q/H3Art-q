# 👋 Hi, I’m H3Art-q.
# 👇 There is a piece of code.(Yes, it is.)

```C
#include <stdio.h>
#include <time.h>

char whatIWantToSay[] = "There is no magic in the computer world.\n";

int main(int argc, char *argv[]) {
  for (int i = 0; whatIWantToSay[i] != '\0';) {
    clock_t start = clock();
    while (clock() - start < CLOCKS_PER_SEC / 10)
      ;
    putc(whatIWantToSay[i++], stdout);
    fflush(stdout);
  }
  return 0;
}
```

<!---
H3Art-q/H3Art-q is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
