# Torganizer

Torganizer est une application de bureau qui aide à organiser des fichiers et
des dossiers. Elle permet de préparer des classements, de normaliser des noms,
de repérer des doublons et de créer des archives ZIP.

## Fonctionnalités

- Parcourir le contenu d'un dossier et afficher ses fichiers et sous-dossiers
  immédiats.
- Préparer un classement par extension, taille, première lettre, catégorie ou
  date de modification, avec plusieurs niveaux de critères.
- Obtenir des suggestions de classement intelligent à partir des noms de
  fichiers et des dossiers existants.
- Prévisualiser les changements proposés avant de les appliquer.
- Préparer la normalisation des noms et repérer les fichiers identiques. La
  détection de doublons ne les supprime pas.
- Créer une archive ZIP des éléments sélectionnés, avec un mot de passe
  facultatif. Les originaux sont conservés.
- Consulter l'historique des opérations et annuler certaines opérations de la
  session en cours.
- Choisir la langue de l'interface (français, anglais ou kirundi) et son thème.

## Installation sous Windows
Téléchargez l'installateur Windows depuis la [publication v0.1.0](https://github.com/Tresor2004/Torganizer/releases/download/V.0.1.0/Torganizer-Setup-0.1.0.exe).

SHA-256 : `dcab2a5ad577a4b4a922633c6a33fae8147116ea044b1032d9c09af54123ccf5`

Après le téléchargement :

1. double cliquer sur le fichier téléchargé (` Torganizer-Setup-0.1.0.exe` ) et suivez les étapes affichées par
   l'installateur.
2. Lancez Torganizer depuis le menu Démarrer ou depuis le raccourci créé par
   l'installation, s'il y en a un.

L'installateur fourni n'est pas signé numériquement. Téléchargez-le uniquement
depuis une source de confiance et vérifiez que son nom correspond à celui de la
publication.

## Utilisation

### Organiser un dossier

1. Ouvrez l'application et choisissez le dossier à examiner.
2. Sélectionnez les critères de classement souhaités. Pour un classement à
   plusieurs niveaux, choisissez les critères dans l'ordre voulu.
3. Demandez un aperçu et vérifiez les destinations proposées dans le tableau.
4. Si le plan vous convient, validez-le pour appliquer les déplacements.
   Sinon, effacez le plan en attente.

L'aperçu ne modifie pas les fichiers. Les déplacements ne commencent qu'après
validation. Le classement est placé dans un dossier `Organized` sous la racine
choisie.

### Autres actions

- **Classification intelligente :** demandez des suggestions, examinez le plan
  proposé, puis validez-le si vous souhaitez effectuer les déplacements.
- **Normalisation des noms :** générez les propositions, vérifiez-les dans le
  tableau, puis validez les changements.
- **Doublons :** lancez la détection pour afficher les fichiers identiques.
  Cette action est uniquement informative.
- **Archivage :** sélectionnez les éléments à archiver et préparez une archive
  ZIP. Vous pouvez définir un mot de passe; les fichiers d'origine restent en
  place.
- **Paramètres :** changez la langue et le thème depuis l'onglet des paramètres.
- **Historique :** consultez les opérations récentes et utilisez le bouton de
  retour arrière lorsqu'il est disponible.

## Données et précautions

- L'application affiche les éléments immédiats du dossier choisi, pas son
  contenu récursif complet.
- Vérifiez toujours le plan avant de le valider. Pensez à conserver une
  sauvegarde de vos fichiers importants.
- Le retour arrière concerne la dernière transaction de la session en cours.
  L'historique reste enregistré après fermeture, mais les informations
  nécessaires pour restaurer une transaction ne sont pas conservées entre les
  lancements.
- Le retour arrière interne ne peut pas restaurer un fichier envoyé dans la
  Corbeille Windows.
- Les préférences et l'historique sont conservés dans
  `%APPDATA%\Torganizer` sous Windows.

