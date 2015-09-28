# activemq
Broker ActiveQM lancé sur un java7 avec le scheduler activé

## Pour lancer
```bash
docker run -d -p 8161:8161 -p 61616:61616 rayquiz/activemq
```

## Java
La version de java utilisée est openjdk-7.

En attente de la résolution du JIRA https://issues.apache.org/jira/browse/AMQ-5356 pour utiliser la version 8