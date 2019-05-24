# wildfly-keyclaok

error: Keycloak Unknown authentication mechanism
solution:
il faut unziper le keyclaoak adapter zip dans le dossier home de wilfly ( choisir la version de keycloack adapter ici: http://central.maven.org/maven2/org/keycloak/keycloak-wildfly-adapter-dist/)
dans wildfly, lancer la commande jboss-cli.sh -c --file=adapter-install.cli avec serveur démarré
