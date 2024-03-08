# GitHub Pages
## Welcome to my GitHub Pages

You can use the [editor on GitHub](https://github.com/PhPittet/phpittet.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing.

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/PhPittet/phpittet.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

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


