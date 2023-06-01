# dynamiser-un-site-web
Dynamiser un site web statique avec JavaScript (Eval d'entraînement)

.- Création d'une instance EC2 sur AWS dans l'offre "Free Tier" sous Debian (ec2-13-38-238-213.eu-west-3.compute.amazonaws.com) avec une connexion (en ligne de commande) par clef SSH générée sur AWS.
.- Mise à jour des paquets et installation dans du pare-feu UFW + restriction des ports en laissant juste l'accès SSH ouvert en IP-V4 et IP-V6
.- Installation du serveur Apache2
.- Ouverture du port 80 sur le pare-feu UFW
.- Connexion via SFTP et transfert d'un fichier HTML et un CSS pour tester le serveur.

= = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = =
= = = = = = = = = = = = = = = = = = INFOS DE CONNEXION AU SERVEUR AWS = = = = = = = = = = = = = = = = = =
= = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = =

.- Connexion SSH : ssh -i ~/.ssh/SSH-LAMP-Server-OpenClassRoom.pem admin@ec2-13-38-238-213.eu-west-3.compute.amazonaws.com
= = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = = =
