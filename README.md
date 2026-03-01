Hello, welcome to my Github profile 👋🍎
```c
// About Me
#include <stdlib.h>
#include <string.h>

typedef struct {
    char nickname[70];
    char PLang[70];
    char pronouns[10];
    char country[30];
    char interests[100];
    char* repositories;
} AboutMe;

void Display_AboutMe(AboutMe person) {
    printf("Nickname: %s\n", person.nickname);
    printf("Programming Languages: %s\n", person.PLang);
    printf("Pronouns: %s\n", person.pronouns);
    printf("Country: %s\n", person.country);
    printf("Interests: %s\n", person.interests);
    printf("Repositories: %s\n", person.repositories);
}

int main(){
    AboutMe me;

    strcpy(me.nickname, "Jakkret");
    strcpy(me.PLang, "C/C++");
    strcpy(me.pronouns, "he/him");
    strcpy(me.country, "Poland");
    strcpy(me.interests, "old hardware and software, programming, using various OS' (...)");
    strcpy(me.repositories, "DVD_GL, SNEK_GL OpenGLHeart, RoseGL, GWM, Win32AboutDialog");

    Display_AboutMe(&me);

    return 0;
}

```
