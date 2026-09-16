# Politique de sécurité

Ce dépôt fait partie de l'écosystème **LucidForge Africa (LFA)**. Cette politique s'applique à l'ensemble des dépôts publics et privés de LFA (We Forge Business, LucidCleanHub, WeForgeEdu, ZANMI, Prod+ Entertainment, ForgeNet, ainsi que l'infrastructure interne), quel que soit le dépôt sur lequel vous vous trouvez.

## Signaler une vulnérabilité

**➡️ [Report a vulnerability](mailto:contact@lucidforgeafrica.com?subject=%5BSECURITY%5D%20Vulnerability%20report)**

Ce lien reste valable sur n'importe quel dépôt LFA : il ne dépend pas du dépôt courant, contrairement à un lien de signalement propre à un projet.

Merci d'inclure, dans la mesure du possible :

- une description claire de la vulnérabilité et de son impact potentiel ;
- le produit ou service concerné (ex. ForgeNet, WFB, LucidPay…) et sa version/commit si connu ;
- les étapes de reproduction, un proof-of-concept ou des logs pertinents ;
- votre évaluation de la sévérité (si vous en avez une).

**Merci de ne pas ouvrir d'issue publique pour signaler une faille de sécurité.** Utilisez exclusivement le canal ci-dessus.

## Ce que nous demandons (divulgation responsable)

- Laissez-nous un délai raisonnable pour analyser et corriger le problème avant toute divulgation publique.
- N'accédez pas, ne modifiez pas et n'exfiltrez pas de données au-delà de ce qui est strictement nécessaire pour démontrer la vulnérabilité.
- N'exploitez pas la faille contre des utilisateurs, des comptes ou des environnements de production réels.
- Agissez de bonne foi et évitez toute action pouvant dégrader un service (déni de service, spam, etc.).

## Ce à quoi vous pouvez vous attendre

| Étape | Délai indicatif |
| --- | --- |
| Accusé de réception | Sous 72 heures ouvrées |
| Évaluation initiale et sévérité | Sous 7 jours |
| Correctif ou plan de remédiation | Selon la sévérité, communiqué au rapporteur |

Nous vous tiendrons informé·e de l'avancement et vous créditerons (si vous le souhaitez) une fois le correctif publié.

## Portée

Sont concernés : le code source, les infrastructures self-hosted (« s0 »), les API, les applications mobiles et web, et les intégrations tierces des produits LFA. Sont hors périmètre : l'ingénierie sociale, le phishing contre les employé·e·s, et les attaques nécessitant un accès physique non autorisé aux locaux.

## Versions supportées

Chaque produit LFA précise, dans son propre `README.md`, quelles versions ou branches sont activement maintenues et reçoivent des correctifs de sécurité. En l'absence d'indication contraire, seule la branche par défaut (`main`) est couverte.
