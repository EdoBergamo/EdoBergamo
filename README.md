<h2 align="center">About Me</h2>

```c
#include <stdio.h>
#include <stdlib.h>
#include <string.h>

typedef struct {
    char discord[20];
    char instagram[20];
    char email[20];
} Contact;

typedef struct {
    char langs[4][20];
    int age;
} Life;

typedef struct {
    struct {
        char expert[20];
        char intermediate[20];
        char learning[20];
    } langs;
    char specialities[2][50];
    char environment[2][20];
} Coding;

typedef struct {
    Contact contact;
    Life life;
    Coding coding;
} Attributes;

int main() {
    Attributes EdoBergamo;

    strcpy(EdoBergamo.contact.discord, "amtriix");
    strcpy(EdoBergamo.contact.instagram, "edoardo.hb");
    strcpy(EdoBergamo.contact.email, "hello@amtriix.it");

    strcpy(EdoBergamo.life.langs[0], "Italian");
    strcpy(EdoBergamo.life.langs[1], "English");
    strcpy(EdoBergamo.life.langs[2], "Spanish");
    strcpy(EdoBergamo.life.langs[3], "Arabic");

    EdoBergamo.life.age = 20;

    strcpy(EdoBergamo.coding.langs.expert, "C, C++");
    strcpy(EdoBergamo.coding.langs.intermediate, "Python, C#, ASM, Java");
    strcpy(EdoBergamo.coding.langs.learning, "HTML, CSS, JS, PHP");

    strcpy(EdoBergamo.coding.specialities[0], "Reverse Engineering");
    strcpy(EdoBergamo.coding.specialities[1], "Full Stack - WIP");

    strcpy(EdoBergamo.coding.environment[0], "vscode");
    strcpy(EdoBergamo.coding.environment[1], "vim");

    return 0;
}
```
<h2 align="center">Skills</h2>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,vim,vscode,c,cs,cpp,js,css,html" />
  </a>
</p>

<p href="https://discord.gg/sSwbs3cZBC" align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=EdoBergamo&theme=tokyonight&show_icons=true" />
</p>

<a href="https://github.com/EdoBergamo" align="center">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=EdoBergamo&langs_count=10&title_color=0891b2&text_color=ffffff&icon_color=0891b2&bg_color=1c1917&hide_border=true&locale=en&custom_title=Top%20%Languages" alt="Top Languages" />
</a>
