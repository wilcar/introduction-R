Installation de R et Rstudio
================
w cariou ufr HHAUuniversité de Nantes
6 avril 2018

# Installation

## R et R studio

Le langage R possède une interface (*GUI*) limitée qui n’a plus vocation
à être directement utilisée. Vous devez également utiliser
l’environnement de développement R Studio qui assure le rôle
d’interface entre R et l’utilisateur.

⚠️ Vous devez d’abord installer R avant d’installer R Studio.

### Installer R (Windows et MacOsX)

Pour une installation sous Windows ou OSX, vous devez vous rendre sur la
page **Page d’accueil** du [projet R](https://www.r-project.org/) puis
sélectionnez **Download Cran** suivi de **0-Cloud**. Vous devez
télécharger la **distribution binaire précompilée** (*Precompiled
binary distributions of the base system and contributed packages*)
correspondant à votre système d’exploitation. Une fois le programme
d’installation lancé, acceptez l’ensemble des options par défaut
offertes par l’installateur.

<div class="figure" style="text-align: center">

<img src="images/landing-r.png" alt="Page d'accueil du [projet R](https://www.r-project.org/), avril 2020." width="100%" />

<p class="caption">

Page d’accueil du [projet R](https://www.r-project.org/), avril 2020.

</p>

</div>

<div class="figure" style="text-align: center">

<img src="images/tele-r.png" alt="Page de téléchargement de R, avril 2020." width="100%" />

<p class="caption">

Page de téléchargement de R, avril 2020.

</p>

</div>

#### Linux

Si vous travaillez sous Linux, vous trouverez R *via* Gestionnaire (ou
bibliothèque) de logiciels .

### Installer RStudio

1.  Une fois R correctement installé, rendez-vous sur
    <http://www.rstudio.com/products/rstudio/download/> pour télécharger
    la l’édition Open Source de RStudio Desktop gratuite.
2.  Choisissez l’installateur correspondant à votre système
    d’exploitation.

<div class="figure" style="text-align: center">

<img src="images/tele-rstudio.png" alt="Page de télchargement de RStudio (1), avril 2020." width="100%" />

<p class="caption">

Page de télchargement de RStudio (1), avril 2020.

</p>

</div>

<div class="figure" style="text-align: center">

<img src="images/tele-rstudio2.png" alt="Page de télchargement de RStudio (2), avril 2020." width="100%" />

<p class="caption">

Page de télchargement de RStudio (2), avril 2020.

</p>

</div>

### Installer et mettre à jour des bibliothèques (*packages*).

R fait appel à de nombreux *packages* qui viennent se greffer sur son
noyau (R-Base). Les *packages* sont téléchargés depuis le site du CRAN
par le biais de la fonction `install.packages()` ou le panneau dédié de
R Studio.

<div class="figure" style="text-align: center">

<img src="images/packages1.png" alt="Panneau packages dans RStudio." width="40%" />

<p class="caption">

Panneau packages dans RStudio.

</p>

</div>

⚠️ Il est important de distinguer l’installation des *packages* et leur
utilisation à travers la fonction `library()`. l’installation télécharge
les *packages* sur internet et les installe localement sur le disque dur
de l’ordinateur dans le dossier `R` (Cette opération n’est à réaliser
qu’une seule fois). la fonction `library()` permet de faire appel aux
fonctions du *package*. Elle doit être appelée à chaque fois que cela
est nécessaire.

⚠️ Lors d’une nouvelle installation de R, vous serez amené à télécharger
un grand nombre de packages.
