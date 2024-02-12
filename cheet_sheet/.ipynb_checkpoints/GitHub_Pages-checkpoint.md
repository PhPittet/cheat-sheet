# GitHub Pages

## Petit guide pour mettre son fichier Jupyter Notebook en ligne sur GitHub Pages

### Création du site

TO Do....

Cloner le repo GitHub localement sur l'ordi avec GitHub Desktop


### Mise à jour du notebook et de l'url 
> *Pour l'explication suivante, on supposera que le notebook se trouve dans le dossier `...\GitHub\physique-gybe` qui est le dossier cloner de GitHub.\
> La racine du terminal de jupyterlab doit être `...\GitHub>`*

*[Instructions originales](https://jupyterbook.org/en/stable/start/publish.html) :\
To update your online book, make changes to your book’s content on the main branch of your repository, re-build your book with jupyter-book build mybookname/ and then use ghp-import -n -p -f mylocalbook/_build/html as before to push the newly built HTML to the gh-pages branch.*

#### Etape 1 : Modifier le notebook
1. Pour modifier le notebook, ouvrez JupyterLab et aller dans le dossier (repo cloner) GitHub de votre notebook.
2. Dans jupyterlab, vérifier que vous êtes bien dans la branche `main`. Pour cela cliquer sur l'icone `Git` dans la barre laterale à gauche, vérifier le `Current Repository` dans lequel se trouve votre projet et le `Current Branch`. Effectuer les modifications si besoin (naviguer simplement dans le bon dossier, puis choisir la branche `main` depuis `Git`)
3. Apporter les modifications à votre notebook.
4. `build` le dossier `_html` du  notebook avec la commande suivante :
   
   *Rappel : Le notebook se trouve dans le dossier `...\GitHub\physique-gybe`. La racine du terminal de jupyterlab doit être `...\GitHub>`*
   ```none
   jupyter-book build physique-gybe/
   ```
#### Etape 2 : Commit & Push
5. Mettre ensuite les mise-à-jour sur le repo GitHub en ligne. Pour cela ouvrez **GitHuB Desktop**, choisissez le bon `Current repository` (*en haut à gauche*) et vérifier que la branche et bien réglée sur `main`.
   - Cliquer sur `Commit to main` *(il faut ajouter un message qui explique brièvement les modifications)*
   - Cliquer sur `Push origin` *(en haut, au milieu)*

6. On doit pouvoir aussi faire ça depuis JupyterLab (**TO DO**)

#### Etape 3 : Update url
Utiliser `ghp-import` pour mettre à jour la page web :

7. Ouvrez un terminal (anaconda promt, par exemple)
8. Si le package `ghp-pages` est installé sur un autre environnement que *base (root)*, changer d'environnement :\
      *(ici, l'environnement choisit s'appelle jupyterlab4)*
      ```none
      conda activate jupyterlab4
      ```
9. Aller dans le dossier racine du projet `...\GitHub\physique-gybe` (celui qui contient le `dossier _build/html`
      ```none
      cd OneDrive - Education Vaud\GitHub\physique-gybe
      ```
10. Entrer la commande suivante :
      ```
      ghp-import -n -p -f _build/html
      ```
11. Croisez les doigts pour que ça marche


