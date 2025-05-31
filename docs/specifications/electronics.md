# Instrumentation

* Tableau de bord : Ecran TFT 6.9" et liaison optique, résolution de 1280*480px

# Equipements

## Equipement de Série

- DPL - Aide au départ arreté (Ducati Power Launch)
- DQS - Shifter Ducati (DQS) montée/descente 2.0
- DRL - Eclairage Full LED avec feux diurnes (Daytime Running Light)
- Amortisseur de direction Sachs
- Boutons de réglage rapide
- Pit Limiter
- Clignotants à extinction automatique

# Riding Modes et Configuration

Le tableau suivant indique les valeurs par défaut définies par Ducati, pour tous les paramètres de tous les Riding Modes :


|                   | Race A                  | Race B                  | Sport                   | Road                     | Wet                      |
| ------------------- | ------------------------- | ------------------------- | ------------------------- | -------------------------- | -------------------------- |
| Usage prévu      | Track                   | Track                   | Track/Road              | Road                     | Road                     |
| Power Mode        | High                    | High                    | Medium                  | Medium                   | Low                      |
| Max Power         | 158,9 kW à 13500trs/mn | 158,9 kW à 13500trs/mn | 158,9 kW à 13500trs/mn | 158,9 kW à 13500 trs/mn | 120,94 Nm @ 11250 tr/min |
| Throttle response | Dynamic                 | Dynamic                 | Smooth                  | Smooth                   | Dynamic                  |
| ABS               | 1                       | 3                       | 6                       | 6                        | 7                        |
| DTC               | 2                       | 3                       | 5                       | 6                        | 8                        |
| DWC               | 2                       | 3                       | 5                       | 6                        | 6                        |
| DSC               | 1                       | 2                       | 2                       | 2                        | 2                        |
| EBC               | 2                       | 2                       | 2                       | 2                        | 3                        |
| DQS               | On                      | On                      | On                      | On                       | On                       |

## Modes de Puissance (Power Mode)

La Panigale V4 2025 offre quatre configurations de moteur : Full, High, Medium et Low.

Le mode Full Power est le plus extrême. Il permet au moteur d'exprimer tout son potentiel, avec des courbes de couple sans filtres électroniques, à l'exception de la première vitesse.

Le mode High Power (Associé aux modes de conduite Race A et Race B) répond aux besoins des pilotes amateurs et professionnels sur circuit, tandis que le mode Medium Power est associé aux modes de conduite Sport et Road.

Tous deux peuvent délivrer la pleine puissance et utilisent une gestion matricielle du couple des pneus qui permet à l'ECU d'optimiser les courbes requises pour chaque rapport, améliorant ainsi la continuité et réduisant les compromis.

Le mode Low Power, quant à lui, est conçu pour les surfaces à faible adhérence et les conditions humides. Associé au mode de conduite sur sol mouillé, il limite la puissance maximale à 160 ch pour une réponse à l'accélérateur très gérable.

- DVO - Ducati Vehicle Observer ()
- EBC - Paramétrage du frein moteur (Engine Braking Control)
                                                                                                                    |             
## Assistance au Départ Sportif (Ducati Power Launch - DPL)

Le système Ducati Power Launch (DPL) assiste le pilote dans la manœuvre de départ sportif arrêté avec l'objectif de contrôler la puissance délivrée par le véhicule.
Le système DPL travaille sur la base de 3 différents niveaux d'intervention, chacun desquels a été calibré pour offrir une valeur différente d'assistance au démarrage.
Le tableau suivant indique le niveau d'intervention du DPL plus approprié aux différents types de conduite lors du départ.
Tous les niveaux sont à considérer optimisés pour des pneus OEM (Original Equipment Manufactured).


| Niveau DPL   | Performance | Utilisation                                                                                                                                                                                                                    |
| -------------- | ------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Expert       | High        | Utilisation orientée au maximum de performance pour des pilotes très experts. Le système permet le cabrage et le patinage de la roue arrière, mais réduit la vitesse avec laquelle ces phénomènes se produisent.        |
| Intermediate | Medium      | Utilisation pour pilotes experts. Le système réduit la tendance au cabrage et au patinage de la roue arrière, en plus d'intervenir sensiblement au cas où ces phénomènes se produiraient.                                |
| Beginner     | Medium      | Niveau pour tous les types d'utilisateurs. Le système réduit au minimum la tendance au cabrage et au patinage de la roue arrière, en plus d'intervenir de manière importante au cas où ces phénomènres se produiraient. |

La fonction DPL n'est pas disponible si le DTC ou le DWC sont réglés sur Off.

## Pit Limiter

Cette fonction est uniquement présente dans l’Infomode Track.
Pour activer le Pit limiter, il faut appuyer longuement sur le bouton.
Avec le Pit limiter activé les systèmes DTC, DWC, DSC et DPL ne fonctionnent pas.
| WET         |

## Assistance Anti Cabrage (Ducati Wheeling Control - DWC)

Le tableau suivant indique le niveau d'intervention du système DWC le plus approprié aux divers types de conduite et les niveaux des « Riding Modes » programmés par défaut qui peuvent être sélectionnés par l'utilisateur :


| NIVEAU | DWC                  | SURFACE    | PROFIL                           | TYPE DE CONDUITE                                                                             | PAR DÉFAUT |
| -------- | ---------------------- | ------------ | ---------------------------------- | ---------------------------------------------------------------------------------------------- | ------------- |
| OFF    |                      |            | Le système DWC est désactivé. |                                                                                              |             |
| 1      | HIGH PERFORMANCE     | TRACK      | PILOT                            | Le système permet le cabrage tout en réduisant la vitesse à laquelle la moto peut cabrer. |             |
| 2      | MEDIUM PERFORMANCE   | TRACK      | PILOT                            | Le système permet le cabrage tout en réduisant la vitesse à laquelle la moto peut cabrer. | RACE A      |
| 3      | PERFORMANCE          | TRACK      | PILOT                            | Le système permet le cabrage tout en réduisant la vitesse à laquelle la moto peut cabrer. | RACE B      |
| 4      | PERFORMANCE          | TRACK      | Tous les types d'utilisateurs.   | Le système permet le cabrage tout en réduisant la vitesse à laquelle la moto peut cabrer. |             |
| 5      | SPORT                | ROAD/TRACK | Tous les types d'utilisateurs.   | Le système réduit la tendance à cabrer et intervient sensiblement en cas de cabrage.      | SPORT       |
| 6      | MEDIUM SAFE & STABLE | ROAD       | Tous les types d'utilisateurs.   | Le système réduit la tendance à cabrer et intervient sensiblement en cas de cabrage.      | ROAD, WET   |
| 7      | MEDIUM SAFE & STABLE | ROAD       | Tous les types d'utilisateurs.   | Forte réduction du cabrage. Le système intervient sensiblement en cas de cabrage.          |             |
| 8      | HIGH SAFE & STABLE   | ROAD       | Tous les types d'utilisateurs.   | Réduction maximum du cabrage, intervention forte du système.                               |             |

## Assistance de Contrôle de Traction Ducati (Ducati Traction Control - DTC)

Ducati Traction & DQS EVO 2 est derivé de la Ducati MotoGP, qui communique avec la plateforme inertielle Bosch (Inertial Measurement Unit, IMU) à 6 axes pour adapter son intervention et optimiser la glisse du pneu arrière selon l'angle d'inclinaison de la moto, mais le logiciel améliore aussi considérablement la transmission de la puissance en sortie de virage grâce au nouvel algorithme de contrôle prédictif.

Il utilise la valeur instantanée de la rotation arrière, en repérant plus rapidement la perte d'adhérence et en lissant les variations de glisse, ce qui assure une intervention plus rapide et plus douce.

Cela se traduit par une plus grande stabilité de la moto en sortie des virages, même lorsque l'adhérence n'est pas excellente, une accélération accrue et des performances améliorées tant pour les tours chrono que pour des sessions plus longues. De plus, le DTC Evo 2 agit non seulement sur l'avance à l'allumage et l'injection, mais aussi sur les papillons des gaz lorsqu'aucune commande rapide n'est requise, assurant ainsi le maintien idéal des paramètres de combustion et une réponse plus fluide du moteur.

Lorsque le DTC est configuré sur OFF le DWC est également automatiquement réglé sur OFF ce qui signifie que l'assistance pour le contrôle du cabrage et l'assistance pour la stabilisation de la dynamique du véhicule sont toutes deux
désactivées.
Le système Ducati Traction Control (DTC) supervise le contrôle du patinage de la roue arrière et travaille sur huit niveaux différents dont chacun a été programmé pour offrir une différente valeur de tolérance au patinage de la roue arrière. Un niveau d'intervention prédéfini est assigné à chaque Riding Mode.

Le niveau 8 indique l'intervention du système à la moindre détection de patinage, alors que le niveau 1, réservé aux pilotes les plus experts se caractérise par une plus grande tolérance et donc par une intervention moins invasive du système.

Le tableau suivant indique le niveau d'intervention du système DTC le plus approprié aux divers types de conduite et les niveaux des « Riding Modes » programmés par défaut qui peuvent être sélectionnés par l'utilisateur.


| NIVEAU DTC | TYPE DE CONDUITE   | UTILISATION                                                                                                                                                                                                                                                                                                                                          | PAR DÉFAUT |
| ------------ | -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------- |
| OFF        |                    | Le système DTC est désactivé.                                                                                                                                                                                                                                                                                                                     |             |
| 1          | TRACK Professional | Ce niveau est conçu pour un usage exclusif sur piste et réservé aux pilotes très expérimentés. Bien qu'il soit compatible avec les pneus SP homologués, ce niveau est optimisé pour les pneus Pirelli Diablo Superbike en composé SC1 200/60, après exécution du tire calibration. Le DTC dans ce mode d'utilisation permet le dérapage. |             |
| 2          | TRACK              | Ce niveau est conçu pour un usage exclusif sur piste pour des pilotes experts et il est optimisé par les pneus OEM (Original Equipment Manufacturer). Le DTC dans ce mode d'utilisation permet le dérapage.                                                                                                                                       | RACE A      |
| 3          | SPORT / TRACK      | Ce niveau est conçu pour l'usage sur piste et réservé aux pilotes experts. Le DTC dans ce mode d'utilisation permet le dérapage.                                                                                                                                                                                                                 | RACE B      |
| 4          | SPORT / TRACK      | Ce niveau est conçu pour l'usage sur piste (et sur route pour des pilotes experts)                                                                                                                                                                                                                                                                  |             |
| 5          | SPORT              | Ce niveau est conçu pour la conduite, aussi bien sur route que sur piste, en conditions de surface sèche de bonne adhérence.                                                                                                                                                                                                                      | SPORT       |
| 6          | SAFE & STABLE      | Ce niveau est conçu pour l'usage en n'importe quelle condition de conduite et pour l'utilisation sur route.                                                                                                                                                                                                                                         | ROAD        |
| 7          | RAIN               | Ce niveau est conçu pour l'usage sur piste exclusivement avec des pneus Rain en conditions d'asphalte mouillé.                                                                                                                                                                                                                                     |             |

## Assistance de Contrôle de la Dérive (Ducati Slide Control - DSC)

Le niveau d’intervention de base est en fonction du niveau DTC sélectionné.


| NIVEAU | DSC                                              | UTILISATION PAR DÉFAUT  |
| -------- | -------------------------------------------------- | -------------------------- |
| OFF    | Le système DSC est désactivé.                 |                          |
| 1      | Le patinage latéral est réduit mais autorisé. | RACE A                   |
| 2      | Le patinage latéral est fortement limité.      | RACE B, SPORT, ROAD, WET |
