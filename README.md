# 📘 **Cours C – Débutant à Intermédiaire**

## 🧭 Table des matières

1. Introduction au langage C
2. Configuration de l’environnement de développement
3. Structure d’un programme C
4. Les types de données
5. Les variables et constantes
6. Les opérateurs
7. Les structures de contrôle (conditions et boucles)
8. Les fonctions
9. Les tableaux
10. Les pointeurs
11. Les structures
12. La gestion des fichiers
13. Compilation et débogage
14. Projets pratiques

---

## ✅ 1. Introduction au Langage C

* Créé par Dennis Ritchie en 1972.
* Langage bas niveau, proche du matériel.
* Très utilisé dans les systèmes embarqués, systèmes d’exploitation, etc.

---

## 💻 2. Configuration de l’Environnement

* **Compilateurs** : GCC (Linux), MinGW (Windows), Clang (Mac)
* **IDE recommandés** : Code::Blocks, Dev-C++, VS Code avec plugin C/C++
* Exemple pour compiler :

  ```bash
  gcc programme.c -o programme
  ./programme
  ```

---

## 🧱 3. Structure d’un programme C

```c
#include <stdio.h>

int main() {
    printf("Bonjour le monde !\n");
    return 0;
}
```

---

## 🔣 4. Types de Données

| Type     | Taille        | Description                 |
| -------- | ------------- | --------------------------- |
| `int`    | 2 ou 4 octets | Nombres entiers             |
| `float`  | 4 octets      | Nombres à virgule flottante |
| `char`   | 1 octet       | Caractère                   |
| `double` | 8 octets      | Flottant double précision   |

---

## 📝 5. Variables et Constantes

```c
int age = 25;
const float PI = 3.14;
char lettre = 'A';
```

---

## ➕ 6. Opérateurs

* **Affectation** : `=`
* **Arithmétiques** : `+`, `-`, `*`, `/`, `%`
* **Relationnels** : `==`, `!=`, `<`, `>`, `<=`, `>=`
* **Logiques** : `&&`, `||`, `!`

---

## 🔁 7. Structures de Contrôle

### Condition

```c
if (x > 0) {
    printf("Positif");
} else {
    printf("Négatif ou nul");
}
```

### Boucles

```c
for (int i = 0; i < 10; i++) {
    printf("%d\n", i);
}
```

---

## 🧩 8. Fonctions

```c
int carre(int x) {
    return x * x;
}
```

---

## 📚 9. Tableaux

```c
int notes[3] = {12, 14, 16};
printf("%d", notes[0]);  // affiche 12
```

---

## 📌 10. Pointeurs

```c
int a = 5;
int* p = &a;
printf("%d", *p); // affiche la valeur pointée (5)
```

---

## 🏗️ 11. Structures

```c
struct Personne {
    char nom[20];
    int age;
};
```

---

## 📂 12. Gestion des fichiers

```c
FILE *f = fopen("data.txt", "r");
char ligne[100];
fgets(ligne, 100, f);
fclose(f);
```
