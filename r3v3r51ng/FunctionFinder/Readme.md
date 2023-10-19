Description: Examinez le code ci-dessous et identifiez la fonction de chaque méthode.
Code fourni :

```c
int add(int a, int b) {
    return a + b;
}

int multiply(int a, int b) {
    int result = 0;
    for(int i = 0; i < b; i++) {
        result = add(result, a);
    }
    return result;
}

int power(int a, int b) {
    int result = 1;
    for(int i = 0; i < b; i++) {
        result = multiply(result, a);
    }
    return result;
}
```

Flag après identification correcte de toutes les fonctions : EPI{FunctionFiesta}


###  ###
# *--* #
# *xx* #
# *--* #
###  ###
