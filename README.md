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

Comment utiliser ce gabarit:
----------------------------

La branche `master` est encombrante à utiliser puisqu'elle contient de `README`
et d'autres fichiers qui n'ont pas besoin d'être copié dans un nouveau projet.
De ce fait, je recommande d'utiliser la branche `template` pour initialiser vos
projets. Elle ne contient que l'essentiel:

```
git clone -b template https://git.chausse.xyz/sherbrooke-tex now-de-votre-projet
```

Il peut aussi être utile de garder le repo hors ligne pour faciliter son
utilisation comme gabarit. Ainsi, je recommande le prodédé suivant:

```sh
# Choisissez l'emplacement et le nom du dossier pour le gabarit ici:
path="~/gabarit"

# Création du gabarit hors-ligne dans le dossier choisi:
git clone https://git.chausse.xyz/sherbrooke-tex $path

# Copie du gabarit lors de la création d'un nouveau projet:
git clone -b template $path
```

Autres informations utiles
--------------------------

Le gabarit est basé sur les information contenues dans le guide de rédaction
technique en génie (fourni dans le cadre du projet d'équipe en S1). Afin d'en
rendre son accès facile, je l'ai inclus dans le repo
(`Guide-redaction-technique_version1-7.pdf`). Cette référence prime sur les
autres. Toutefois, s'il s'avère qu'une information est manquante de ce guide,
le Protocole de rédaction disponible sur l'intranet de la faculté est utilisé
(`Protocole_Redaction_ESup.pdf`). S.V.P. faites une PR si je m'avère à être
dans le tort dans ce gabarit. PAS DE ISSUES! S'il y a un problème, ayez une
solution avant de m'en parler.
