C Decoder Dilemma:

    Description: Voici un programme en C qui encode des messages. Votre travail est de comprendre comment il encode les messages et de le décoder.
    Code fourni :

    c

```c
#include <stdio.h>
#include <string.h>

void encode(char *message) {
    for (int i = 0; i < strlen(message); i++) {
        message[i] = message[i] + 3;
    }
}

int main() {
    char message[] = "Hello World!";
    encode(message);
    printf("%s\n", message);
    return 0;
}
```
Flag après décodage : EPI{CIsForCoders}
Durée de résolution estimée: 30 minutes.
Grille de notation: