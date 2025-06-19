# Configuration WhatsApp

Pour intégrer FlowBot avec WhatsApp, vous devez activer et configurer un compte WhatsApp Business API pour obtenir les identifiants requis : `token_id`, `app_id`, `app_secret` et `phone_id`. Suivez ces étapes :

1. **Créer un compte WhatsApp Business**

   - Inscrivez-vous sur [WhatsApp Business API](https://developers.facebook.com/docs/whatsapp/overview).
   - Complétez le processus de vérification commerciale pour accéder à l'API.

2. **Configurer une application sur Facebook for Developers**

   - Accédez au portail [Facebook for Developers](https://developers.facebook.com/).
   - Créez une nouvelle application sous 'Mes Applications' et sélectionnez 'Business' comme type d'application.
   - Notez l'`app_id` et l'`app_secret` dans le tableau de bord de l'application.

3. **Configurer l'API WhatsApp Business**

   - Dans le tableau de bord de l'application, naviguez vers 'WhatsApp' > 'Paramètres'.
   - Ajoutez un numéro de téléphone et enregistrez-le pour obtenir un `phone_id`.
   - Générez un `token_id` (jeton d'accès utilisateur système) avec les permissions nécessaires (par ex., `whatsapp_business_management`).

4. **Vérifier le profil dans FlowBot**
   - Connectez-vous à la plateforme FlowBot.
   - Allez dans 'Paramètres du profil' sous votre compte.
   - Entrez le `token_id`, l'`app_id`, l'`app_secret` et le `phone_id` dans la section d'intégration WhatsApp.
   - Enregistrez et vérifiez la connexion. Un message de succès confirme l'intégration.

Pour des instructions détaillées, consultez le [Guide de configuration de l'API WhatsApp Business](https://developers.facebook.com/docs/whatsapp/business-api/guides).
