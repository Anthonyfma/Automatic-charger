# Automatic-charger

Francais

Ce répertoire contient le code nécessaire pour charger automatiquement 6 lipo en serie avec un charger IMax B6. Le fonctionnement est simple: le boitier sert de commutateur entre les batteries. Le chargeur y est relié, et une batterie sera mise en lien avec le chargeur. Une fois la charge terminée, la batterie suivante sera connectée et la charge redemarre.

Important : Le chargeur Imax B6 doit etre sur l'écran du type de charge voulu (charge, balance, etc). Celui avec le nombre de cells, l'amperage...

Composants:
- une carte arduino nano
- 6 relais 4 contacts (1 par batterie)
- une puce ULN2803 pour alimenter les relais (l'arduino ne peut pas alimenter elle même)
- des prises batteries
- des pins
- du fil
- une carte pour souder les composants
- un servo-moteur





English

This repository contains all the necessary code to create an automatic charger from a Imax B6. It will charge 6 lipo in a raw, automatically. The way it works is really simple: the box is a simple commutator between batteries. The charger is pluged, and one battery will be linked to the charger. Once the charge is over, the next battery will be linked and the charge process will start again.

Important thing : for initialisation, the Imax B6 charger needs to be on the charge type screen (charge, balance, etc). With the cell number, the current.

Components:
- arduino nano
- 6 relais 4 contacts
- an ULN2803 to power relais
- batteries connectors
- pins
- wires
- a board to solder components
- a servo motor
