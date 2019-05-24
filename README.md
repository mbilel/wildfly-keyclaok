# wildfly-keyclaok

error: Keycloak Unknown authentication mechanism
solution:
il faut unziper le keyclaoak adapter zip dans le dossierhome de wilfly
dans wildfly, lancer la commande jboss-cli.sh -c --file=adapter-install.cli avec serveur démarré
