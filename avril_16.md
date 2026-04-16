# Jim Fan (NVIDIA) :

Jim Fan propose le concept de **« test de Turing physique »** : un robot devrait pouvoir, par exemple, ranger un salon en désordre et préparer un dîner aux chandelles sans qu'on puisse distinguer son travail de celui d'un humain. Or, on en est encore loin.

Le principal obstacle est la **rareté des données** : contrairement aux LLM qui exploitent l'immensité du web, la robotique n'a pas accès à ce « carburant fossile ». Les données doivent être collectées par téléopération, processus lent, coûteux et fondamentalement non scalable.

La solution proposée passe par la **simulation à grande échelle**, déclinée en deux paradigmes complémentaires :
- **Simulation 1.x (« digital twin/cousin »)** : moteurs physiques classiques massivement parallélisés (10 000 environnements simultanés avec randomisation de domaine), permettant un transfert *zero-shot* vers le réel — illustré par des résultats spectaculaires en manipulation dextre et locomotion humanoïde (avec seulement 1,5 million de paramètres pour le contrôle corps entier).
- **Simulation 2.0 (« digital nomad »)** : modèles de diffusion vidéo qui génèrent intégralement des scènes robotiques réalistes, capables de simuler fluides, déformations et interactions complexes que les moteurs classiques peinent à reproduire.

Ces deux approches alimentent les **modèles Vision-Language-Action**, dont **GR00T N1**, open-sourcé par NVIDIA lors de la GTC.

Sa vision finale : au-delà de l'IA physique, émergera une **« API physique »** permettant au logiciel d'agir sur les atomes comme il agit aujourd'hui sur les bits, ouvrant la voie à une nouvelle économie (app stores de compétences, services type « dîner étoilé à domicile »). Le jour où le test de Turing physique sera passé, ce sera, comme pour les LLM, « juste un mardi de plus ».

Le lien avec vos travaux sur les VLA et GR00T N1 est direct — cette présentation offre un cadre narratif intéressant (problème des données → simulation → VLA → vision sociétale) qui pourrait nourrir l'introduction ou la conclusion de votre document.
