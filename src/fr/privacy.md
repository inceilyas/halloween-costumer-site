title: Politique de confidentialité
description: Comment {{APP_NAME}} traite tes photos et tes données : ce qui est envoyé au service d'IA, les bases juridiques, ce qui est conservé et pendant combien de temps, et tes droits dans le monde entier.

# Politique de confidentialité

> Date d'entrée en vigueur : {{EFFECTIVE_DATE}}

{{APP_NAME}} (l'« App ») transforme tes photos en portraits de monstres d'Halloween à l'aide d'un service tiers de génération d'images par IA. La présente politique explique quelles informations l'App traite, pourquoi et sur quelle base juridique, qui les reçoit, combien de temps elles sont conservées, et quels droits et choix tu as, où que tu vives. L'App est exploitée par {{DEVELOPER_NAME}} (« nous »), responsable du traitement de tes données personnelles (la partie qui décide comment et pourquoi elles sont traitées). Nos coordonnées figurent à la section 14.

## 1. En bref

- Les photos que tu choisis sont envoyées à un service d'IA externe (OpenAI) uniquement pour créer le portrait que tu as demandé. Nous te demandons ton autorisation expresse avant que cela se produise pour la première fois, et tu peux la retirer à tout moment.
- Nous ne conservons pas les photos que tu envoies. Nous les transmettons, en mémoire, au service d'IA et renvoyons le résultat sur ton téléphone. L'App conserve une copie réduite de l'original uniquement sur ton téléphone, pour une comparaison avant/après (section 2c).
- Tes portraits terminés sont enregistrés sur ton téléphone. Pour qu'un portrait ne soit pas perdu si ta connexion saute ou si l'App est fermée pendant sa création, nous conservons une copie chiffrée de chaque portrait nouvellement généré sur notre serveur pendant 24 heures au maximum. Elle sert uniquement à livrer le portrait à ton téléphone, et elle est supprimée dès que ton téléphone confirme l'enregistrement, ou au plus tard après 24 heures.
- Nous n'utilisons pas tes photos ni ton visage pour entraîner des modèles d'IA, pour la publicité ou pour des analyses. Nous n'identifions ni ne reconnaissons personne à partir de son visage.
- Il n'y a ni compte, ni SDK publicitaire ou d'analyse dans l'App, ni pistage à travers les apps et sites web d'autres entreprises. Notre serveur partage ton identifiant anonyme et tes enregistrements d'achats (jamais de photos) avec un fournisseur d'analyse des abonnements (RevenueCat, section 4).
- Tu peux supprimer tes données depuis l'App à tout moment (Profil > Supprimer toutes mes données) et retirer ton consentement à l'IA (Profil > Retirer le consentement à l'IA).

## 2. Informations que nous traitons

**a. Photos que tu choisis ou que tu prends.** Lorsque tu choisis une photo dans ta photothèque ou que tu en prends une avec l'appareil photo, puis que tu touches pour créer un portrait, la photo (un JPEG redimensionné) et le look sélectionné sont envoyés à notre backend, puis au service d'IA. Si tu choisis un look de groupe ou de couple avec des selfies séparés, chaque selfie est envoyé. Les photos peuvent montrer ton visage et celui d'autres personnes. Nous n'accédons qu'aux photos que tu choisis explicitement ; l'App n'analyse pas ta photothèque.

**b. Vérification des visages sur ton appareil.** Avant l'envoi d'une photo, l'App utilise le framework Vision d'Apple sur ton appareil pour vérifier qu'un nombre approprié de visages est présent (par exemple exactement deux pour un look de couple). Cette vérification s'exécute entièrement sur ton téléphone. Elle détecte l'emplacement des visages et leur nombre. Elle ne crée ni gabarit facial ni identifiant biométrique, elle n'identifie ni ne reconnaît personne, et ses résultats ne sont envoyés nulle part, si ce n'est sous la forme d'un nombre de visages servant à rédiger les instructions destinées au service d'IA. Pour une création faite à partir d'une seule photo, la position du visage (un simple rectangle, normalisé par rapport à la photo) est en plus conservée dans les données de la création, sur ton téléphone uniquement, pour aligner la comparaison avant/après (section 2c).

**c. Portraits générés.** Le résultat du service d'IA revient dans l'App et est enregistré sur ton téléphone. Une copie temporaire de chaque portrait généré est conservée chiffrée dans notre stockage cloud pendant 24 heures au maximum, uniquement pour le livrer à ton téléphone en cas d'échec de la connexion ; nous ne conservons jamais tes selfies ni tes autres photos d'origine sur nos serveurs. Sur ton téléphone uniquement, une création faite à partir d'une seule photo (solo ou une photo de groupe) garde aussi, à côté du portrait, une copie réduite de la photo d'origine (grand côté de 1280 pixels), afin d'afficher une comparaison avant/après. Cette copie n'est jamais envoyée, est exclue des sauvegardes de l'appareil et est supprimée avec la création ou par Supprimer toutes mes données. Les créations faites à partir de selfies séparés et les portraits récupérés depuis notre copie de livraison de 24 heures n'ont pas de copie de la photo d'origine.

**d. Identifiant anonyme et crédits.** L'App crée un identifiant Firebase anonyme pour ton installation. Nous l'utilisons pour tenir ton solde de crédits et pour enregistrer les achats et les mouvements de crédits (ID de transaction, produit, date). Nous ne te demandons pas de créer un compte et nous ne collectons dans l'App ni ton nom, ni ton adresse e-mail, ni ton numéro de téléphone. Lorsque nous appelons le service d'IA, nous incluons un identifiant pseudonyme dérivé de ton identifiant anonyme au moyen d'un hachage à clé à sens unique ; ce n'est pas ton véritable identifiant et le service d'IA ne peut pas le relier à toi. Il aide le service d'IA à détecter les abus.

**e. Achats.** Les achats et abonnements sont traités par Apple. Nous ne recevons jamais ta carte bancaire ni les données de ton compte Apple. Nous recevons la confirmation d'une transaction (ID de transaction, produit, dates, état du renouvellement ou du remboursement) afin d'accorder ou de retirer des crédits. Si tu touches Restaurer les achats, l'App envoie à notre serveur les enregistrements d'achat signés par Apple afin que nous les vérifiions et rattachions de nouveau tes achats et tes crédits restants à l'App sur cet appareil. Ces enregistrements contiennent le produit, les dates et l'identifiant d'achat aléatoire par installation que nous avons généré ; ils ne contiennent ni ton nom, ni ton adresse e-mail, ni tes données de paiement. Si les enregistrements correspondent à une autre installation de l'App, les crédits restants de cette installation sont déplacés (et non copiés) vers celle-ci. La restauration ne demande aucune connexion et ne crée aucun nouveau type de données personnelles. Nous transmettons aussi ces enregistrements d'achats, avec ton identifiant anonyme, de notre serveur à RevenueCat (section 4) afin de pouvoir consulter des statistiques d'abonnements et de revenus ; l'App elle-même ne contient aucun logiciel RevenueCat et n'envoie rien à RevenueCat.

**f. Intégrité de l'appareil.** Pour protéger le service contre les abus, nous utilisons App Attest d'Apple (via Firebase App Check) pour confirmer que les requêtes proviennent d'une copie authentique de l'App, et DeviceCheck d'Apple pour retenir, au moyen d'un simple indicateur activé/désactivé stocké par Apple, qu'un appareil a déjà utilisé son premier portrait offert. DeviceCheck ne nous dit pas qui tu es.

**g. Journaux techniques.** Nos services cloud et le service d'IA peuvent journaliser des informations techniques telles que l'adresse IP, l'heure de la requête et les codes d'erreur, pour la sécurité et le fonctionnement du service. Notre propre code n'écrit dans les journaux ni photos, ni données faciales, ni données personnelles. Nous n'utilisons pas ces journaux pour établir des profils te concernant.

**h. Messages à l'assistance.** Si tu nous écris, nous recevons ton adresse e-mail et ce que tu écris, et nous ne l'utilisons que pour te répondre.

**i. Réglages sur l'appareil.** L'App enregistre sur ton téléphone des préférences simples (par exemple le fait que tu as terminé l'introduction et que tu as accepté l'avis sur l'IA).

Nous ne collectons ni ta position précise, ni tes contacts, ni tes données de santé, ni ton historique de navigation.

## 3. Pourquoi nous les utilisons, et bases juridiques

| Finalité | Informations | Base juridique (RGPD et UK GDPR ; bases équivalentes dans les autres lois) |
| --- | --- | --- |
| Créer le portrait que tu demandes : envoyer tes photos et le look choisi au service d'IA | Photos, look sélectionné, nombre de visages, identifiant pseudonyme | Ton consentement (art. 6, par. 1, point a), donné dans l'App avant la première création. Tu peux le retirer à tout moment ; le retrait n'affecte pas les traitements antérieurs. |
| Crédits, achats, abonnements, restauration des achats, remboursements de crédits | Identifiant anonyme, solde de crédits, enregistrements d'achats | Exécution de notre contrat avec toi (art. 6, par. 1, point b) ; conservation des enregistrements que la loi nous impose de conserver (art. 6, par. 1, point c) |
| Comprendre les abonnements et les revenus (analyse des abonnements) | Identifiant anonyme, enregistrements d'achats et de renouvellements signés par Apple | Nos intérêts légitimes à exploiter et à améliorer un service payant (art. 6, par. 1, point f). Tu peux t'y opposer (section 7). |
| Prévenir la fraude et les abus, faire respecter la règle d'un seul portrait offert par appareil, assurer la sécurité du service (App Check, DeviceCheck, limites de débit, filtres de sécurité, journaux) | Identifiant anonyme, signaux d'intégrité de l'appareil, journaux techniques | Nos intérêts légitimes à protéger le service, les autres utilisateurs et nous-mêmes (art. 6, par. 1, point f). Tu peux t'y opposer (section 7). |
| Répondre aux demandes d'assistance | Adresse e-mail, message, ID d'assistance | Notre contrat avec toi et notre intérêt légitime à t'aider |
| Respecter la loi et traiter les demandes en justice | Enregistrements décrits à la section 6 | Obligation légale et intérêts légitimes |

**Visages et photos.** Les visages et les photos présents dans tes images servent uniquement à générer le portrait que tu as demandé. Ils ne sont pas utilisés pour entraîner ou améliorer un modèle d'IA, ni pour de la publicité ou du marketing, ni pour des analyses ou du profilage, et ne sont ni vendus ni partagés à ces fins. Nous ne constituons pas de base de données de visages, et nous n'analysons pas les photos pour déduire des caractéristiques sensibles de qui que ce soit.

Si tu n'acceptes pas l'envoi de photos au service d'IA, tu peux toujours ouvrir l'App, mais elle ne peut pas créer de portraits.

## 4. Qui reçoit les informations

Nous ne partageons des informations qu'avec les prestataires de services nécessaires au fonctionnement de l'App :

- **OpenAI** (génération d'images). Tes photos et le look sélectionné sont envoyés à l'API d'OpenAI pour produire ton portrait. OpenAI agit en tant que notre sous-traitant. Selon la politique de données de l'API publiée par OpenAI, les données envoyées à l'API ne servent pas à entraîner ou à améliorer les modèles d'OpenAI sauf si le client y consent (nous n'y avons pas consenti), et le contenu de l'API peut être conservé dans des journaux de détection des abus jusqu'à 30 jours, voire plus longtemps si la loi l'exige ou si cela est nécessaire pour protéger les services. Politique d'OpenAI : https://developers.openai.com/api/docs/guides/your-data . OpenAI peut également analyser les images importées pour détecter des contenus pédopornographiques et conserver une image signalée pour examen, comme le décrit cette politique.
- **Google (Firebase et Google Cloud)** (hébergement du backend, identifiant anonyme, enregistrements de crédits et d'achats, contrôles d'intégrité de l'app, stockage chiffré temporaire des portraits générés). Google agit en tant que notre sous-traitant, en vertu de ses conditions de traitement des données. Notre backend s'exécute aux États-Unis (Iowa).
- **RevenueCat, Inc.** (États-Unis) (analyse des abonnements et des achats). Notre serveur envoie à RevenueCat ton identifiant anonyme et les enregistrements d'achats signés par Apple pour tes achats (produit, dates, environnement, identifiant d'achat aléatoire, et événements de renouvellement, de remboursement et d'annulation). RevenueCat agit en tant que notre sous-traitant. Aucune photo, aucun visage, aucun nom, aucune adresse e-mail ni aucun identifiant d'appareil n'est envoyé, et l'App ne contient aucun logiciel RevenueCat. Lorsque tu utilises Supprimer toutes mes données, nous demandons aussi à RevenueCat de supprimer son enregistrement lié à ton identifiant anonyme.
- **Apple** (achats sur l'App Store, App Attest, DeviceCheck, et partage facultatif de tes portraits via la feuille de partage d'iOS, que tu lances toi-même). Apple agit en tant que responsable du traitement indépendant pour ses propres services.
- **Autorités ou ayants cause**, lorsque la loi l'exige ou pour protéger des droits et la sécurité, ou dans le cadre d'un transfert d'activité, avec information préalable lorsque la loi l'impose.

Nous ne vendons pas tes informations personnelles et nous ne les partageons pas à des fins de publicité comportementale intercontextuelle.

Lorsque tu partages un portrait vers une autre app (par exemple depuis la feuille de partage), la politique de confidentialité propre à cette app s'applique à ce que tu partages.

## 5. Transferts internationaux

Nous sommes établis en Turquie, et nos prestataires traitent les données aux États-Unis et éventuellement dans d'autres pays où ils sont présents. Si tu utilises l'App dans l'Espace économique européen, au Royaume-Uni, en Suisse, en Turquie, au Brésil, en Corée du Sud, au Japon ou ailleurs, tes informations sont donc transférées vers d'autres pays, y compris des pays dont la législation sur la protection des données peut différer de la tienne.

Nous appliquons les garanties que ta loi exige pour de tels transferts, lorsqu'elles s'appliquent : une décision d'adéquation (par exemple le Cadre de protection des données UE-États-Unis, lorsque le destinataire y participe), des clauses contractuelles types (UE et addendum britannique) figurant dans les conditions de traitement des données de nos prestataires, d'autres mécanismes licites reconnus par le droit local (voir la section 8), et ton consentement lorsque la loi l'autorise. Nous limitons en outre les envois à ce qui est nécessaire, nous utilisons des connexions chiffrées et nous n'envoyons au service d'IA ni ton nom, ni ton adresse e-mail, ni ton véritable identifiant de compte. Tu peux nous demander des informations sur ces garanties (section 14).

## 6. Durée de conservation des informations

| Informations | Conservation |
| --- | --- |
| Photos envoyées pour une création | Non conservées par nous. Gardées en mémoire uniquement pendant le traitement de la requête. Le service d'IA peut les conserver jusqu'à 30 jours dans des journaux de détection des abus (voir la section 4). |
| Portraits générés et, pour les créations faites à partir d'une seule photo, copie de la photo d'origine | Sur ton téléphone jusqu'à ce que tu les supprimes ou que tu utilises Supprimer toutes mes données. La copie réduite de la photo d'origine et son rectangle de visage ne quittent jamais ton téléphone et sont exclus des sauvegardes de l'appareil. Une copie de livraison temporaire du portrait est conservée chiffrée sur notre serveur pendant 24 heures au maximum (supprimée lorsque ton téléphone confirme l'enregistrement, et par Supprimer toutes mes données). |
| Identifiant anonyme, solde de crédits, mouvements de crédits, enregistrements d'achats (y compris ceux utilisés par la restauration des achats) | Jusqu'à ce que tu supprimes tes données dans l'App. Les enregistrements dont le solde est nul, sans abonnement actif et sans utilisation de l'App depuis 24 mois sont supprimés automatiquement (vérification quotidienne), avec l'enregistrement de connexion anonyme. |
| Enregistrement chez RevenueCat (identifiant anonyme, enregistrements d'achats et de renouvellements) | Jusqu'à ce que tu supprimes tes données dans l'App ou que l'enregistrement soit supprimé automatiquement après 24 mois d'inactivité (voir ci-dessus) ; nous demandons alors à RevenueCat de le supprimer. Les conditions propres à RevenueCat régissent les copies de sauvegarde. |
| Enregistrements de transactions d'achat après la suppression de tes données dans l'App ou après la suppression automatique | L'ID de transaction, le produit et les dates sont conservés sans aucun lien avec ton identifiant anonyme, afin de traiter les remboursements, d'éviter d'accorder deux fois des crédits et lorsque la loi l'exige (par exemple pour la comptabilité). Si tu avais un abonnement actif, l'enregistrement d'abonnement anonymisé conserve aussi les crédits hebdomadaires restants de la période en cours, toujours sans aucun lien avec ton identifiant anonyme, afin que l'abonnement puisse être restauré après une nouvelle installation (Restaurer les achats) ; ils ne servent qu'à cela et sont conservés aussi longtemps que ces enregistrements de transactions. |
| Marqueur de suppression | Après la suppression de tes données, nous conservons ton ancien identifiant anonyme aléatoire et l'heure de la suppression, afin que l'enregistrement supprimé ne puisse pas être recréé. Il ne contient aucune autre information. |
| Journaux techniques | Une durée limitée nécessaire à la sécurité et à l'exploitation (par exemple, Firebase Authentication journalise les adresses IP pendant quelques semaines). |
| E-mails à l'assistance | Aussi longtemps que nécessaire pour t'aider, puis supprimés. |

## 7. Tes droits et tes choix

Selon l'endroit où tu vis, tu disposes de tout ou partie des droits suivants : savoir si nous traitons tes données et en obtenir une copie (accès) ; les rectifier ; les supprimer ; limiter le traitement ; recevoir tes données dans un format portable ; t'opposer à un traitement fondé sur des intérêts légitimes ; retirer ton consentement à tout moment ; ne pas faire l'objet d'une décision fondée exclusivement sur un traitement automatisé produisant des effets juridiques ou des effets similaires significatifs (nous n'en prenons aucune) ; et introduire une réclamation auprès d'une autorité de protection des données.

Comment les exercer :

- **Supprimer toutes mes données (dans l'App).** Profil > Supprimer toutes mes données supprime les portraits, les photos d'origine, les miniatures de selfies et le consentement à l'IA stockés sur ton téléphone, et nous demande de supprimer l'enregistrement côté serveur lié à ton identifiant anonyme (solde de crédits et enregistrements d'achats), et demande à RevenueCat de supprimer son enregistrement lié à cet identifiant. Les packs de crédits non utilisés sont perdus lorsque tu le fais. Les crédits hebdomadaires restants d'un abonnement actif ne sont pas perdus : ils sont conservés avec l'enregistrement d'abonnement anonymisé (section 6) pour que tu puisses restaurer l'abonnement après une nouvelle installation. Supprimer simplement l'App ne supprime pas l'enregistrement côté serveur.
- **Retirer le consentement à l'IA.** Profil > Retirer le consentement à l'IA. Aucune photo ne sera envoyée de nouveau tant que tu n'auras pas accepté à nouveau.
- **Accès, portabilité, rectification, limitation, opposition.** Écris à {{SUPPORT_EMAIL}} en indiquant l'ID d'assistance affiché dans l'onglet Profil, afin que nous retrouvions ton enregistrement. Nous ne pouvons pas consulter tes données sans lui, car l'App est anonyme. Nous t'enverrons l'enregistrement lié à ton ID d'assistance (solde de crédits, mouvements de crédits et enregistrements d'achats) dans un format courant et lisible par machine. Tes portraits se trouvent déjà sur ton téléphone.
- **Accès aux photos.** Tu peux modifier les autorisations de l'appareil photo et des photos dans les Réglages d'iOS. L'App utilise le sélecteur de photos du système, qui ne lui donne accès qu'aux photos que tu sélectionnes, et n'enregistre dans ta photothèque que lorsque tu touches Enregistrer.
- **Les abonnements** se gèrent ou se résilient dans les réglages de ton compte Apple (voir nos Conditions d'utilisation).

Nous répondons dans un délai d'un mois (RGPD et UK GDPR ; nous pouvons le prolonger de deux mois supplémentaires au maximum pour les demandes complexes, et nous t'en informerons), ou dans le délai fixé par la loi qui s'applique à toi. Nous pouvons te demander de confirmer qu'une demande émane du titulaire de l'ID d'assistance. Tu peux aussi introduire une réclamation auprès de ton autorité locale de protection des données (dans l'EEE, l'autorité de contrôle du pays où tu vis ou travailles, par exemple la CNIL en France ; au Royaume-Uni, l'Information Commissioner's Office ; en Turquie, l'Autorité de protection des données personnelles ; au Brésil, l'ANPD ; en Corée du Sud, la PIPC ; au Japon, la PPC). Nous apprécierions d'avoir d'abord la possibilité de régler ton problème.

## 8. Informations propres à certaines régions

### 8.1 Espace économique européen, Royaume-Uni et Suisse

{{DEVELOPER_NAME}} est le responsable du traitement. Les bases juridiques figurent à la section 3, les transferts à la section 5, la conservation à la section 6 et tes droits à la section 7, y compris les droits d'opposition et de retrait du consentement. Nous n'avons pas désigné de délégué à la protection des données ; les questions relatives à la vie privée sont à adresser à l'adresse indiquée à la section 14. Lorsque la loi de ton pays fixe, pour consentir au traitement de données personnelles, un âge supérieur à 13 ans (par exemple de 14 à 16 ans dans plusieurs pays européens), voir la section 9.

### 8.2 Turquie (loi n° 6698, KVKK)

{{DEVELOPER_NAME}} est le responsable du traitement. Nous traitons les données personnelles pour les finalités de la section 3, sur le fondement de ton consentement explicite (envoi des photos au service d'IA), de la conclusion et de l'exécution d'un contrat, de nos intérêts légitimes (prévention de la fraude et sécurité) et d'obligations légales. En vertu de l'article 11 de la loi n° 6698 relative à la protection des données personnelles, tu peux demander si tes données sont traitées, demander des informations, connaître la finalité du traitement et savoir s'il est conforme à cette finalité, connaître les tiers auxquels elles sont transférées en Turquie ou à l'étranger, demander leur rectification ou leur suppression, demander que ces opérations soient notifiées aux tiers, t'opposer à un résultat défavorable pour toi et demander la réparation du préjudice subi. Adresse-toi à nous à l'adresse indiquée à la section 14, en indiquant ton ID d'assistance ; nous répondons dans un délai de trente jours au plus tard. Si tu n'es pas satisfait, tu peux introduire une réclamation auprès du Conseil de protection des données personnelles (Kişisel Verileri Koruma Kurulu, KVKK). Les données sont transférées à l'étranger (section 5) dans les conditions de l'article 9 de la loi n° 6698.

### 8.3 Brésil (LGPD)

{{DEVELOPER_NAME}} est le responsable du traitement, et le point de contact des personnes concernées est l'adresse indiquée à la section 14. Nos bases juridiques au titre de l'article 7 de la loi n° 13.709/2018 (Lei Geral de Proteção de Dados, LGPD) sont le consentement, l'exécution d'un contrat, l'exercice régulier de droits et les intérêts légitimes. Tu disposes des droits prévus à l'article 18 (confirmation du traitement, accès, rectification, anonymisation, blocage ou suppression, portabilité, information sur le partage, information sur les conséquences d'un refus de consentement, et révocation du consentement) et tu peux saisir l'ANPD (Autoridade Nacional de Proteção de Dados). Les transferts internationaux sont effectués comme indiqué à la section 5 et à l'article 33 de la LGPD.

### 8.4 Corée du Sud (PIPA)

Nous traitons les informations personnelles décrites à la section 2 uniquement pour les finalités de la section 3 et nous les conservons pendant les durées de la section 6. Nous ne communiquons pas d'informations personnelles à des tiers autrement que comme décrit à la section 4. Nous confions à OpenAI, à Google et à RevenueCat les traitements décrits à la section 4, et nous les contrôlons par des clauses contractuelles. Tes photos et les informations associées sont transférées à l'étranger comme suit, avec ton consentement donné dans l'App :

| Destinataire et pays | Éléments | Finalité | Quand et comment | Conservation |
| --- | --- | --- | --- | --- |
| OpenAI, États-Unis | Photos, look sélectionné, identifiant pseudonyme | Générer le portrait | À chaque création de portrait, par un réseau chiffré | Jusqu'à 30 jours dans des journaux de détection des abus |
| Google (Firebase et Google Cloud), États-Unis | Identifiant anonyme, enregistrements de crédits et d'achats, copie temporaire du portrait généré | Hébergement, registre des crédits, livraison du portrait | À chaque utilisation de l'App, par un réseau chiffré | Comme à la section 6 |
| RevenueCat, États-Unis | Identifiant anonyme, enregistrements d'achats et d'abonnements | Analyse des abonnements | À chaque achat, renouvellement ou remboursement traité, par un réseau chiffré | Comme à la section 6 |

Tu peux exercer tes droits d'accès, de rectification, de suppression, de suspension du traitement et de retrait du consentement au titre de la loi sur la protection des informations personnelles (개인정보 보호법, PIPA) en nous contactant à l'adresse indiquée à la section 14 ; tu peux refuser ton consentement, mais l'App ne peut alors pas créer de portraits. Le responsable de la protection de la vie privée est {{DEVELOPER_NAME}} ({{SUPPORT_EMAIL}}). Tu peux aussi demander de l'aide à la Commission de protection des informations personnelles (개인정보보호위원회) ou au Centre de la vie privée de la KISA (118).

### 8.5 Japon (APPI)

{{DEVELOPER_NAME}} est l'opérateur traitant les informations personnelles. Nous n'utilisons les informations personnelles que pour les finalités de la section 3. Lorsque tu y consens dans l'App, tes photos et les informations associées sont communiquées à des entreprises situées dans un pays étranger : OpenAI et Google, aux États-Unis et dans d'autres pays où elles sont présentes. Ton identifiant anonyme et tes enregistrements d'achats sont aussi communiqués à RevenueCat, aux États-Unis. Les États-Unis n'ont pas de loi unique et générale de protection des informations personnelles comparable à la loi japonaise sur la protection des informations personnelles (個人情報の保護に関する法律, APPI) ; nos prestataires traitent les données selon leurs propres engagements et les conditions contractuelles décrits à la section 4 (pas d'entraînement sur les données de l'API, conservation limitée, chiffrement). Tu peux demander la communication, la rectification, la suppression et la cessation d'utilisation des données personnelles conservées, ainsi que le registre des communications à des tiers, en nous contactant à l'adresse indiquée à la section 14.

### 8.6 États-Unis

Selon l'endroit où tu vis (par exemple la Californie, le Colorado, le Connecticut, la Virginie, le Texas, l'Oregon et d'autres États dotés de lois sur la protection des consommateurs en matière de vie privée), tu peux avoir le droit de savoir quelles informations personnelles nous détenons, d'y accéder, de les rectifier, de les supprimer, d'en recevoir une copie portable et de faire appel de notre décision. Nous ne vendons pas d'informations personnelles, nous ne les partageons pas à des fins de publicité ciblée et nous ne les utilisons pas pour un profilage produisant des effets juridiques ou des effets similaires significatifs. Nous ne traitons pas les photos pour identifier une personne de manière unique. Pour exercer ces droits, utilise Supprimer toutes mes données dans l'App ou écris à {{SUPPORT_EMAIL}} ; nous répondrons dans un délai de 45 jours (prolongeable une fois lorsque la loi l'autorise) et nous ne te ferons subir aucune discrimination pour avoir exercé tes droits. Tu peux recourir à un mandataire autorisé ; nous pouvons demander l'ID d'assistance pour vérifier la demande. Si nous refusons une demande, tu peux faire appel en répondant à notre e-mail, et tu peux contacter le procureur général de ton État.

Les demandes relevant du « Shine the Light » californien et celles du Nevada peuvent être envoyées à la même adresse. Nous ne répondons pas aux signaux « Do Not Track » (« Ne pas me suivre »), car nous ne te pistons pas.

### 8.7 Autres pays

Si la loi de ton pays te confère des droits supplémentaires sur tes données personnelles, nous les respecterons dans la mesure où ils s'appliquent à nous. Écris à l'adresse indiquée à la section 14.

## 9. Enfants

L'App ne s'adresse pas aux enfants, et nous ne collectons pas sciemment d'informations personnelles auprès d'enfants de moins de 13 ans. N'utilise pas l'App et n'importe pas de photos d'enfants de moins de 13 ans. Lorsque la loi de ton pays fixe un âge minimum supérieur pour consentir au traitement de données personnelles (par exemple 14 ans en Corée du Sud, et de 14 à 16 ans dans plusieurs pays européens), tu dois avoir au moins cet âge, ou avoir le consentement d'un parent ou d'un tuteur, pour utiliser l'App. Si tu penses que les informations d'un enfant nous ont été envoyées, contacte {{SUPPORT_EMAIL}} et nous les supprimerons.

## 10. Traitement automatisé et données biométriques

Les portraits sont créés par un modèle d'IA à partir de ta photo et d'un look choisi par nous. Nous ne prenons aucune décision te concernant qui produise des effets juridiques ou des effets similaires significatifs, et nous ne faisons pas de profilage. Les seuls contrôles automatisés sont des mesures de lutte contre la fraude et les abus (par exemple des limites par appareil et des filtres de sécurité des contenus) ; si une création est refusée, tu peux réessayer avec une autre photo ou nous contacter.

Nous n'utilisons pas d'identification biométrique. La détection des visages s'exécute uniquement sur ton appareil, pour vérifier qu'un visage est présent et pour compter les visages. Nous ne créons ni ne conservons de gabarits faciaux, nous ne comparons pas les visages et nous n'utilisons pas les visages pour identifier qui que ce soit. Le rectangle de visage (position et taille uniquement) qui reste sur ton téléphone pour la comparaison avant/après n'est pas un gabarit facial, ne sert à rien d'autre et ne nous est jamais envoyé.

## 11. Photos d'autres personnes

N'ajoute que des photos de personnes qui ont donné leur accord. Les photos d'autres personnes sont envoyées au service d'IA comme les tiennes. Il t'appartient d'avoir leur autorisation.

## 12. Sécurité

Les données circulent entre l'App, notre backend et le service d'IA par des connexions chiffrées (HTTPS/TLS). Nos prestataires cloud chiffrent les données stockées au repos. La clé d'API OpenAI est conservée sur notre serveur et ne se trouve jamais dans l'App. Aucun système n'est parfaitement sûr, nous ne pouvons donc pas garantir une sécurité absolue. Si une violation de données touche tes données personnelles, nous t'en informerons, ainsi que les autorités, comme la loi l'exige.

## 13. Modifications, et ce site web

Si nous modifions cette politique de manière significative, nous mettrons à jour la date ci-dessus et, si la modification concerne ce qui est envoyé au service d'IA, nous te demanderons de nouveau ton autorisation dans l'App. Si cette politique t'est présentée dans ta langue, la traduction est fournie pour ta commodité ; la version anglaise prévaut en cas de divergence entre les versions.

Ce site web est statique. Il ne dépose aucun cookie et n'utilise ni outil d'analyse ni ressource externe. Il est hébergé sur GitHub Pages, et GitHub peut traiter des données techniques telles que ton adresse IP lorsque ton navigateur charge une page.

## 14. Contact

{{DEVELOPER_NAME}}
{{SUPPORT_EMAIL}}
{{SITE_URL}}/privacy.html
