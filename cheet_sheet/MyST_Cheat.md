# MyST Cheat sheet

(chap:MySTnotesperso)=
## Notes Personalisées (Admonitions)
### Pour le corps de texte
#### Formule
::::{admonition} Titre_Formule
:class: formule
Formule
::::

```none
::::{admonition} Titre_Formule
:class: formule
Formule
::::
````

#### Sur la calculatrice
:::{admonition} Sur la calculatrice
:class: surcalculatrice
Info sur les calculatrices (class: surcalculatrice)
:::

```none
:::{admonition} Sur la calculatrice
:class: surcalculatrice
Info sur les calculatrices (class: surcalculatrice)
:::
````

#### Astuce
:::{admonition} Astuce
:class: astuce
et_trucs
:::

```none
:::{admonition} Astuce
:class: astuce
et_trucs
:::
````

#### Objectif pédagogique
:::{admonition} Objectifs d'apprentissage
:class: objped
À la fin de cette section, vous pourrez :

1. Objectif_1
2. 
:::

```none
:::{admonition} Objectifs d'apprentissage
:class: objped
À la fin de cette section, vous pourrez :

1. Objectif_1
2. 
:::
````

#### Plus d'infos
:::{admonition} Pour plus d'informations
:class: dropdown weblink
Quelques liens utiles sur le même sujet :
- [NomDuLiens](https://www.alloprof.qc.ca/fr/eleves/bv/physique/physique-l-incertitude-et-les-calculs-d-incertitude-p1049)
- 
:::

```none
:::{admonition} Pour plus d'informations
:class: dropdown weblink
Quelques liens utiles sur le même sujet :
- [NomDuLiens](https://www.alloprof.qc.ca/fr/eleves/bv/physique/physique-l-incertitude-et-les-calculs-d-incertitude-p1049)
- 
:::
````

#### YouTube
:::{admonition} YouTube
:class: dropdown admonition-youtube
Quelques liens de vidéo utiles sur le même sujet :
1. **Titre_de_la_vidéo**
%%HTML [--isolated]
<div align="center">
 <iframe width="600" height="400" src="https://www.youtube.com/embed/1zAPfrZaAiA" allowfullscreen></iframe>
</div>

2. **Autre_vidéo**
3. **Et_une_autre**
:::

```none
:::{admonition} YouTube
:class: dropdown admonition-youtube
Quelques liens de vidéo utiles sur le même sujet :
1. **Titre_de_la_vidéo**
%%HTML [--isolated]
<div align="center">
 <iframe width="600" height="400" src="https://www.youtube.com/embed/1zAPfrZaAiA" allowfullscreen></iframe>
</div>

2. **Autre_vidéo**
3. **Et_une_autre**
:::
````

#### Simulation PhET
:::{admonition} P*h*ET simulation
:class: dropdown simulation
**Titre_de_la_simulation**
%%HTML [--isolated]
<div align="center">
<iframe src="address_of_PhET_simulation_to_be_linked" width="600" height="450" scrolling="no" allowfullscreen></iframe>
</div>
:::

```none
:::{admonition} P*h*ET simulation
:class: dropdown simulation
**Titre_de_la_simulation**
%%HTML [--isolated]
<div align="center">
<iframe src="address_of_PhET_simulation_to_be_linked" width="600" height="450" scrolling="no" allowfullscreen></iframe>
</div>
:::
````

(chap:MySTexo)=
### Pour les exercices & questions
#### Exercices
::::{admonition} Exercice N
:class: exohome
Exercice
:::{admonition} *solution*
:class: dropdown exohomesol
Solution
:::
::::

```none
::::{admonition} Exercice N
:class: exohome
Exercice
:::{admonition} *solution*
:class: dropdown exohomesol
Solution
:::
::::
````

#### Questions conceptuelles
::::{admonition} Questions N
:class: question
Question
:::{admonition} *réponse*
:class: dropdown questionsol
Réponse
:::
::::

```none
::::{admonition} Questions N
:class: question
Question
:::{admonition} *réponse*
:class: dropdown questionsol
Réponse
:::
::::
````

### QCM
::::::::::{admonition} QCM 1
:class: qcm
Question
1. Choix_1
2. Choix_2
3. Choix_3
4. Choix_4
:::::::::{admonition} *réponse*
:class: dropdown qcmreponse


:::::{tab-set}
::::{tab-item} -->


::::
::::{tab-item} Réponse 1.
✅ Bonne réponse !
::::

::::{tab-item} Réponse 2.
❌ Mauvaise réponse !
::::

::::{tab-item} Réponse 3.
❌ Mauvaise réponse !
::::

::::{tab-item} Réponse 4.
❌ Mauvaise réponse !
::::
:::::
:::::::::
:::{admonition} *discussion*
:class: dropdown qcmdiscussion
Discussion
:::
::::::::::

```none
::::::::::{admonition} QCM 
:class: qcm
Question
1. Choix_1
2. Choix_2
3. Choix_3
4. Choix_4
:::::::::{admonition} *réponse*
:class: dropdown qcmreponse


:::::{tab-set}
::::{tab-item} -->


::::
::::{tab-item} Réponse 1.
✅ Bonne réponse !
::::

::::{tab-item} Réponse 2.
❌ Mauvaise réponse !
::::

::::{tab-item} Réponse 3.
❌ Mauvaise réponse !
::::

::::{tab-item} Réponse 4.
❌ Mauvaise réponse !
::::
:::::
:::::::::
::::{admonition} *discussion*
:class: dropdown qcmdiscussion
Discussion
::::
::::::::::
```



### Exemple avec solution
#### Simple Solution
::::{admonition} Exemple N
:class: exores
Exercice
:::{admonition} *solution*
:class: dropdown solution
Solution
:::
::::

```none
::::{admonition} Exemple N
:class: exores
Exercice
:::{admonition} *solution*
:class: dropdown solution
Solution
:::
::::
````

#### Avec stratégie
:::::{admonition} Exemple_résolution
:class: exores
Exercice
::::{admonition} *stratégie*
:class: dropdown strategie
Stratégie
::::
::::{admonition} *solution*
:class: dropdown solution
Solution
::::
::::{admonition} *discussion*
:class: dropdown discussion
Discussion
::::
:::::

```none
:::::{admonition} Exemple_résolution
:class: exores
Exercice
::::{admonition} *stratégie*
:class: dropdown strategie
Stratégie
::::
::::{admonition} *solution*
:class: dropdown solution
Solution
::::
::::{admonition} *discussion*
:class: dropdown discussion
Discussion
::::
:::::
````

### Choix en  ligne
:::::{tab-set}
::::{tab-item} Truc N°1
blabla pour le truc 1
::::

::::{tab-item} Truc N°2
bloblo pour le truc 2
::::
:::::

```none
:::::{tab-set}
::::{tab-item} Truc N°1
blabla pour le truc 1
::::

::::{tab-item} Truc N°2
bloblo pour le truc 2
::::
:::::
````

(chap:MySTnotes)=
## Notes de base
::::::{tab-set}

:::::{tab-item} Note
::::{note}
Note
::::
:::::

::::{tab-item} Important
:::{important}
Important
:::
::::

::::{tab-item} Hint
:::{hint}
Hint 
:::
::::

::::{tab-item} See Also
:::{seealso}
See Also
:::
::::

::::{tab-item} Tip
:::{tip}
Tip
:::
::::

::::{tab-item} Attention
:::{attention}
Attention
:::
::::

::::{tab-item} Caution
:::{caution}
Caution
:::
::::

::::{tab-item} Warning
:::{warning}
Warning
:::
::::

::::{tab-item} Danger
:::{danger}
Danger
:::
::::

::::{tab-item} Error
:::{error}
Error
:::
::::

::::{tab-item} Dropdown
:::{dropdown} Dropdown Title
:open:
Dropdown content
:::
::::

::::::


(chap:MySTfigures)=
## Figures
:::{figure} figures/TestPNG.png
:name: TestPNG
:align: center
:width: 50%
*Légende*
:::

```none
:::{figure} figures/TestPNG.png
:name: TestPNG
:align: center
:width: 50%
*Légende*
:::
````

Avec la référence : {numref}`TestPNG` (attention donne Fig. en HTML) ou avec un nom personnalisé {numref}`Image %s <TestPNG>` , ou {numref}`Image %sa <TestPNG>`s'il y a plusieurs sous-image. On peut aussi mettre un titre totalement personnalisé {ref}`magnifique image des carré <TestPNG>`
:::::{tab-set}
::::{tab-item} Référence 1
```none
{numref}`TestPNG`
```
::::

::::{tab-item} Référence 2
```none
{numref}`Image %s <TestPNG>
```
::::

::::{tab-item} Référence 3
```none
{numref}`Image %sa <TestPNG>`
```
::::

::::{tab-item} Référence 4
```none
{ref}`magnifique image des carré <TestPNG>`
```
::::
:::::


(chap:MySTtables)=
## Tables
:::{list-table} Les 7 unités fondamentales du Sytème International (SI)
:name: unitebasetest
:header-rows: 1
*    - Grandeur physique
     - Notation
     - Unité de base
     - Symbole
*    - Distance
     - $x$, $\Delta$$x$, $d$, $h$, $l$
     - **mètre**
     - $[m]$
*    - Temps
     - $t$, $\Delta$$t$
     - **seconde**
     - $[s]$
*    - Masse
     - $m$, $M$
     - **kilogramme**
     - $[kg]$
*    - Courant électrique
     - $i$, $I$
     - ampère
     - $[A]$
*    - Température
     - $T$
     - kelvin
     - $[K]$
*    - Quantité de matière
     - $n$
     - mole
     - $[mol]$
*    - Intensité lumineuse
     - $I$
     - candela
     - $[cd]$
:::

avec la référence : {numref}`unitebasetest` ou avec un nom pérsonalisé {numref}`Tableau %s <unitebasetest>` voir un titre personnalisé {ref}`Tableau des 7 unités SI <unitebasetest>`

:::::{tab-set}
::::{tab-item} Référence 1
```none
{numref}`nom_tableau`
```
::::

::::{tab-item} Référence 2
```none
{numref}`Tableau %s <nom_tableau>
```
::::

::::{tab-item} Référence 3
```none
{ref}`Tableau des 7 unités SI <nom_tableau>`
```
::::

:::::

ou encore sans légende:

| Vitesse $m/s$ | Vitesse $km/h$ | Distance    | Temps           |
|:--------------|:---------------| :-----------|:----------------| 
| $12\,m/s$     |$43.2\,km/h$    |$32.4\,km$   | $45\,m$         | 
|$23.6\,m/s$    |$85\,km/h$      |$162.9\,km$  | $1\,h\,55\,min$ |
|$8.3\,m/s$     |$30\,km/h$      | $8.5\,m$    | $1.02\,s$       |
|$9.5\,m/s$     |$34.2\,km/h$    | $5.0\,km$   |$8\,min\,46\,s$  |
|$28.8\,m/s$    |$103.8\,km/s$   | $1.5\,km$   | $52\,s$         |
|$0.654\,m/s$   |$2.354\,km/s$   | $2550\,m$   | $1\,h\,05\,min$ |

ou encore :
```{csv-table} Frozen Delights!
:header: >
:    "Treat", "Quantity", "Description"
:widths: 15, 10, 30

"Albatross", 2.99, "On a stick!"
"Crunchy Frog", 1.49, "If we took the bones out, it wouldn't be crunchy, now would it?"
"Gannet Ripple", 1.99, "On a stick!"
```

(chap:MySTlistes)=
## Listes particulières
Term *with Markdown*
: Definition [with reference](https://myst-parser.readthedocs.io/en/latest/configuration.html)

  A second paragraph
: A second definition

Term 2
  ~ Definition 2a
  ~ Definition 2b

Term 3
:     A code block
      on two line
: > A quote\
    on two line too
: A final definition, that can even include images:


(chap:MySTreference)=
## Référence à un chapitre
mettre `(chap:MySTreference)=` juste au dessus du titredu chapitre.

Et voilà comment référencer ce chapitre :
- Avec un nom : [Cette partie](chap:MySTreference) ou
- Directement avec le titre du chapitre {ref}`chap:MySTreference`

:::::{tab-set}
::::{tab-item} Référence 1
```none
[Cette partie](chap:MySTreference)
```
::::

::::{tab-item} Référence 2
```none
{ref}`chap:MySTreference`
```
::::
:::::