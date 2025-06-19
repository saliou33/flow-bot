# Nœuds de Message

Les nœuds de message envoient des messages WhatsApp dans divers formats :

- S'il est suivi d'une variable, un nœud de message attend une réponse ; sinon, il continue le flux (sauf pour les types interactifs, qui exigent toujours une réponse de l'utilisateur).
- **Texte** : Envoie du texte avec les propriétés `to` (par ex., `${{context.sender}}`) et `text`.
- **Média** : Envoie du média (vidéo, document, audio, image) avec les propriétés `to` et `content` (fichier téléchargé).
- **Interactif** : Envoie des messages interactifs avec boutons, utilisant les propriétés `caption`, `buttons`, `buttonType`, et `content`.
