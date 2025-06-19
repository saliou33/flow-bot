# Exécution des Flux de Travail

Une exécution est le processus de lancement d'un flux déclenché par un événement. Par exemple, un message déclencheur envoyé par un utilisateur WhatsApp (texte ou média) initie l'ensemble du flux. L'exécution peut réussir, échouer ou produire un message d'erreur disponible pour le débogage. La plateforme permet un suivi en temps réel des exécutions. Chaque exécution dispose de son propre contexte, où les variables sont évaluées (par ex., `${{context.sender}}` pour le numéro de téléphone de l'expéditeur).
