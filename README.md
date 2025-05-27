
## Helle there :wave:

### My C description :
```c
#include <stdio.h>
#include <string.h>

typedef struct {
    char username[50];
    char job[50];
    char codingLanguages[50];
} Person;

void details(Person p) {
    printf("Hello, my name is eerie\n", p.username);
    printf("I'm independent developer for the moment/n", p.job);
    printf("I'm currently working on lot's of projects in defferents languages", p.codingLanguages);
}

int main() {
    Person me;
    strcpy(me.username, "eerieweb");
    strcpy(me.job, "Independent developer");
    strcpy(me.codingLanguages, "C,JS,HTML,CSS..");

    details(me);
    return 0;
}
```

Also

```c
Hello, my name is eerieweb
I'm an Independent passionate developer 
I'm currently working with C, Javascript and HTML
