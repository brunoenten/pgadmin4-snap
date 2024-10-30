# pgAdmin 4 Snap
[![pgadmin4](https://snapcraft.io/pgadmin4/badge.svg)](https://snapcraft.io/pgadmin4)

pgAdmin 4 is a rewrite of the popular pgAdmin3 management tool for the
PostgreSQL (http://www.postgresql.org) database.

This repository contains the recipe to build the pgadmin4 snap.


# Permissions

To allow pgadmin4 usage of the system password manager, you have to give permission to the snap:

```
snap connect pgadmin4:password-manager-service
```

Similarly, to be able to load and save files from the user home directory:

```
snap connect pgadmin4:home
```
