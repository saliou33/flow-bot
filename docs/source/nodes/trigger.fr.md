# Nœuds de Déclenchement

Les nœuds de déclenchement initient les flux avec quatre types :

- **Message** : Déclenché lorsqu'un utilisateur WhatsApp envoie un message (texte ou média) à l'entreprise. Après exécution, la variable globale `${{context}}` fournit le numéro de téléphone de l'expéditeur avec `.sender`, et `prev.output` donne accès au texte ou média de l'utilisateur, avec `prev.meta.media_type` indiquant le type de média.
- **Webhook** : Exécute un flux via un appel HTTP. `prev.output` contient les données de réponse, et `prev.meta` inclut les détails de l'événement ou autres informations liées au webhook.
- **Manuel** : Lance le flux sur demande.
- **Planification** : Planifie l'exécution à l'aide d'une configuration de type crontab.
