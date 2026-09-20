# Mission données — Révisions S2, technologie 5ème

Le site est entièrement contenu dans `dist/index.html` : télécharger ce fichier et l’ouvrir dans un navigateur récent suffit. Les jeux et les mémos fonctionnent hors connexion. Seul le lien facultatif vers la licence Creative Commons nécessite Internet.

## Utilisation en classe

- Distribuer le fichier HTML sur l’ENT ou dans l’espace de la classe. Selon l’ENT, l’élève doit télécharger le fichier puis l’ouvrir dans son navigateur.
- Choisir librement l’une des quatre missions : 8 étapes d’organisation, 9 étapes sur les formats, 11 sur les tailles et 14 sur la sécurité et le partage.
- Lire les corrections et utiliser les indices ou fiches mémo. Les quatre fiches peuvent être imprimées depuis le site.
- Lancer le défi final : 12 questions tirées parmi les 42 étapes, à raison de 3 par thème.
- À la fin, consulter le bilan et rejouer les erreurs. Le score reste indicatif et ne constitue pas une évaluation officielle.

La progression est limitée à la page ouverte. Le retour aux missions permet de reprendre l’entraînement ; fermer ou recharger la page remet le parcours à zéro. Il n’y a ni compte élève, ni collecte de nom, ni envoi des réponses, ni suivi enseignant à distance.

## Supports pédagogiques utilisés

Les quatre fiches professeur S21, S22, S23 et « Partager sans exposer ni blesser » (S24, intitulé S9 dans le document), la Synthèse S2 et l’Évaluation S2 P fournies par l’enseignant ont servi de référence. Les PDF sources ne sont pas inclus dans le site.

Les exercices emploient les conventions du cours : 1 octet = 8 bits ; à partir de l’octet, unités successives d’environ 1 000. Les chemins utilisent la notation Windows avec barre oblique inversée. Les scénarios de partage et les créateurs cités dans l’exercice CC BY sont fictifs.

## Modification

- `content.js` : fiches mémo et banque de questions.
- `app.js` : interactions et progression pendant la session.
- `shell.html` et `activity.css` : présentation.
- `assemble.py` : produit le fichier autonome `dist/index.html` à partir de ces sources.

La version Sites est privée par défaut ; le fichier HTML peut être distribué directement à la classe.
