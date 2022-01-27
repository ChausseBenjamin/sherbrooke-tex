Gabarit LaTeX pour étudiants en génie à l'UdeS.
===============================================

Je me suis basé sur le guide méthodologique présent sur intranet pour créer le
gabarit. Je l'ai inclu dans le repo pour lui en faciliter l'accès. La feuille
de style `document.sty` contient toutes sortes de paramètres utiles pour le
formattage des documents (tailles des marge intérieures/extérieures,
positionnement des numéros d'équations, tailles des polices,dimensions
d'interlignes, etc...). Il importe aussi une multitudes de packages utiles en
génie (par exemple: `siunitx` rend facile le formattage d'unités
internationales).

La branche `master` est encombrante à utiliser puisqu'elle contient de
`README`, un exemple de pdf précompilé, ainsi que le pdf des réglementations au
sujet des normes de formattage de documents en génie. De ce fait, je recommande
d'utiliser la branche `template` pour initialiser vos projets:

```
git clone -b template https://git.chausse.xyz/sherbrooke-tex now-de-votre-projet
```

Il peut aussi être utile de garder de repo hors ligne pour faciliter son
utilisation comme gabarit. Ainsi, je recommande le prodédé suivant:

```
# Création du gabarit hors-ligne dans un dossier nommé gabarit:
git clone https://git.chausse.xyz/sherbrooke-tex ~/gabarit
# Copie du gabarit lors de la création d'un nouveau projet:
git clone -b template ~/gabarit
```
