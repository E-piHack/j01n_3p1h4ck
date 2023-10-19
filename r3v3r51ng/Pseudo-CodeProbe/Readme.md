Pseudo-Code Probe:

    Description: Voici un pseudo-code d'une fonction qui fait quelque chose de spécifique. Analysez-le et répondez aux questions posées.
    Pseudo-Code fourni :

    pseudo

```c++
FONCTION mystery(a, b)
    SI a == 0 ALORS
        RETOUR b + 1
    FIN SI
    SI b == 0 ALORS
        RETOUR mystery(a - 1, 1)
    FIN SI
    RETOUR mystery(a - 1, mystery(a, b - 1))
FIN FONCTION
```
Questions :

    Quelle est la valeur retournée si a=1 et b=2?
    Que fait la fonction lorsque a=0?

Flag pour une réponse correcte : EPI{RecursiveRiddle}