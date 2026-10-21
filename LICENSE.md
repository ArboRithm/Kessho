# Contrat de Licence Utilisateur Final (CLUF) — Kessho

**Version 2.0 — Gratuiciel propriétaire. English version below ; en cas de divergence, la version française prévaut.**
*Date d'effet : 11 octobre 2026.*
*Copyright © 2026 Benjamin Dubois, EI, exerçant sous le nom commercial ArboRithm. Tous droits réservés.*

**Éditeur** : Benjamin Dubois, entrepreneur individuel (EI), exerçant sous le nom commercial « ArboRithm » — SIREN : 490 123 296 — contact : app@arborithm.fr. Dans le présent Contrat, « ArboRithm » désigne cet éditeur.

En téléchargeant, installant ou utilisant l'application Kessho (l'« Application » ou le « Logiciel »), vous acceptez d'être lié par les termes du présent Contrat. Si vous n'acceptez pas ces termes, vous ne devez ni installer ni utiliser le Logiciel.

---

### 1. Objet et champ d'application
La présente licence régit exclusivement l'utilisation des exécutables et binaires de Kessho mis à disposition par ArboRithm, y compris son serveur MCP `kessho-mcp`, de leurs mises à jour et de leur documentation. Elle ne confère aucun droit sur le code source du Logiciel, qui demeure strictement confidentiel et non publié.

### 2. Concession de licence
ArboRithm vous concède une licence non exclusive, personnelle, gratuite, mondiale et non transférable d'installation et d'utilisation du Logiciel, pour un usage tant personnel que professionnel ou commercial, sur un nombre illimité de postes dont vous avez l'usage ou le contrôle, pour la durée de protection des droits.

### 3. Propriété intellectuelle
1. **Le Logiciel** : le Logiciel est concédé en licence, non vendu. ArboRithm conserve la propriété pleine et entière du Logiciel, de son architecture, de son ergonomie, de sa documentation et des noms et marques « Kessho » et « ArboRithm ». Aucun droit de propriété n'est transféré à l'Utilisateur.
2. **Votre vault et vos Données** : vous conservez l'entière et exclusive propriété de votre vault de mémoire — notes, atomes, archives, fichiers Markdown et tout autre fichier qu'il contient — et de tout ce que vous y déposez ou y faites déposer, y compris par des agents ou services tiers que vous connectez au Logiciel (les « Données Utilisateur »). ArboRithm ne revendique aucun droit, de quelque nature que ce soit, sur vos créations, et le présent Contrat ne lui en concède aucun.

### 4. Restrictions d'utilisation
Sauf autorisation écrite préalable d'ArboRithm, vous vous interdisez expressément de :
1. Vendre, louer, prêter, sous-licencier, redistribuer ou héberger le Logiciel sous forme de service tiers (SaaS, bureau distant partagé ou miroir de téléchargement non autorisé) ;
2. Décompiler, désassembler, rétro-concevoir ou tenter d'extraire les secrets de fabrication du Logiciel, sauf dans les strictes limites prévues par l'article L. 122-6-1 du Code de la propriété intellectuelle pour des besoins d'interopérabilité logicielle ;
3. Modifier, altérer, adapter, traduire ou créer des œuvres dérivées du Logiciel ;
4. Supprimer ou altérer les mentions de propriété, de marque ou de licence ;
5. Neutraliser, contourner ou désactiver tout mécanisme de sécurité ou de vérification d'intégrité ;
6. Utiliser le Logiciel à des fins illégales ou contraires aux réglementations applicables.

### 5. Agents d'intelligence artificielle et services tiers
1. **Supervision humaine** : le Logiciel n'appelle lui-même aucun modèle d'intelligence artificielle ; il expose votre vault, par son serveur MCP, aux agents d'intelligence artificielle tiers que vous lui connectez, qui peuvent le lire et y écrire. L'Utilisateur reconnaît que les lectures, écritures et modifications de fichiers effectuées dans son vault par ces agents, ainsi que les commandes qu'ils demandent au Logiciel d'exécuter, relèvent de sa responsabilité exclusive de revue et de validation.
2. **Services tiers et coûts** : les agents que vous connectez au Logiciel, et les API de modèles tiers qu'ils emploient (fournisseurs de LLM, services distants), reçoivent le contenu du vault qu'ils demandent. L'Utilisateur demeure seul responsable du respect des conditions d'utilisation de ces tiers et de l'ensemble des coûts, jetons ou frais d'abonnement associés à l'usage de ses propres clés ou comptes. Ce que produisent ces services est régi entre l'Utilisateur et leurs fournisseurs par les conditions de ces derniers.

### 6. Données et vie privée
1. **Aucune collecte aujourd'hui** : ArboRithm ne collecte aucune donnée d'utilisation. Le Logiciel ne comporte aucune télémétrie, aucun outil de mesure d'audience, aucun rapport d'erreur envoyé à ArboRithm, et ne demande aucun compte. Il traite vos Données Utilisateur sur votre appareil ; ArboRithm n'y accède pas et ne les reçoit pas.
2. **Communications réseau** : le Logiciel ne se connecte à Internet que pour vérifier et télécharger ses mises à jour (article 7), et vers les services que vous configurez ou désignez vous-même — le dépôt Git distant de votre vault, et GitHub, au moyen de l'outil « gh » connecté sur votre poste, lorsqu'un agent lui demande l'historique d'un dépôt que vous désignez —, directement entre votre appareil et ces services, sans passer par ArboRithm. La synchronisation Git n'a lieu qu'avec le dépôt distant que vous avez choisi, et aucun autre : le Logiciel y recherche automatiquement les changements (`git fetch`) toutes les dix minutes tant que sa fenêtre est active, ainsi qu'avant chaque écriture d'un agent lorsque vous avez activé la synchronisation automatique ; il n'y envoie le contenu de votre vault (`git push`) que sur votre demande, directe ou formulée par un agent, ou par la synchronisation automatique si vous l'avez activée. Sous Windows, l'installateur peut télécharger auprès de Microsoft le composant WebView2 s'il est absent.
3. **Mesure d'usage future** : ArboRithm se réserve le droit d'introduire ultérieurement une mesure de l'usage du Logiciel, à seule fin de l'améliorer. Si elle le fait : la mesure sera limitée à des données techniques et anonymes (par exemple la version du Logiciel, le système d'exploitation, les fonctionnalités utilisées et les erreurs rencontrées) ; vous en serez informé avant toute collecte, par une nouvelle version du présent Contrat et par la note de la version qui l'introduit ; elle sera soumise à votre consentement préalable lorsque la loi l'exige, et vous pourrez la désactiver à tout moment dans les Réglages ; ces données ne seront ni vendues, ni louées, ni cédées.
4. **Garantie : vos données personnelles et privées ne feront en aucun cas l'objet d'une collecte.** Cette garantie vaut aujourd'hui et pour toute mesure future. Sont notamment concernés : votre identité, vos coordonnées et identifiants ; vos Données Utilisateur (contenu de votre vault : notes, atomes, archives, fichiers Markdown, consignes et échanges avec des agents) ; les noms et chemins de vos fichiers, dossiers, projets et vaults, et les adresses de vos dépôts Git distants ; vos secrets, jetons et clés ; et toute donnée permettant de vous identifier. L'adresse IP par laquelle transiterait une mesure future ne sera ni conservée, ni associée aux données mesurées.
5. Pour toute question relative à vos données : app@arborithm.fr.

### 7. Mises à jour
Le Logiciel vérifie la disponibilité de ses mises à jour auprès de son infrastructure de distribution (GitHub Releases, opérée par GitHub, Inc.), qui reçoit à cette occasion, comme pour toute requête réseau, l'adresse IP de votre appareil et des en-têtes techniques, et les traite selon sa propre politique de confidentialité. Le Logiciel ne vérifie jamais ses mises à jour au lancement : il ne le fait que sur votre action (Réglages › Mises à jour, « Vérifier »), ou lorsqu'un agent connecté au Logiciel appelle son outil de vérification de version (`mem_check_update`), au plus une fois par heure ; la variable d'environnement `KESSHO_NO_UPDATE_CHECK` désactive ce dernier. Pour un canal de distribution privé, le Logiciel emploie l'outil « gh » connecté sur votre poste, dont le jeton n'est transmis qu'à GitHub. Une mise à jour est téléchargée et installée sur votre action. Chaque version est régie par le Contrat qui l'accompagne.

### 8. Composants tiers et open source
Le Logiciel intègre des bibliothèques et composants logiciels distribués sous licences libres ou open source (notamment MIT, Apache 2.0, BSD, ISC, Mozilla Public License 2.0, Unicode). Ces composants demeurent soumis à leurs licences respectives, qui prévalent sur le présent Contrat pour les seuls composants concernés. Leurs textes et mentions de droits sont fournis avec le Logiciel (fichier « THIRD-PARTY-NOTICES », également consultable dans Réglages › À propos).

### 9. Absence de garantie (« en l'état »)
Le Logiciel est mis à disposition gratuitement « en l'état » (*as is*), sans garantie d'aucune sorte, expresse ou implicite, y compris, sans que cela soit limitatif, toute garantie d'adéquation à un besoin particulier, de disponibilité ininterrompue ou d'absence d'erreurs ou de vulnérabilités, dans toute la mesure permise par la loi. ArboRithm n'est tenue à aucune obligation de support technique, d'assistance personnalisée ou de maintenance corrective. Rien dans le présent Contrat ne limite les droits que la loi vous reconnaît de manière impérative, notamment en qualité de consommateur.

### 10. Limitation de responsabilité
Dans toute la mesure permise par le droit applicable :
1. ArboRithm ne saurait être tenue responsable d'aucun préjudice indirect, consécutif, spécial ou incident, ni d'aucune perte de données, altération ou suppression du contenu de votre vault, interruption d'activité ou manque à gagner, résultant de l'utilisation ou de l'impossibilité d'utiliser le Logiciel ou des actions des agents que vous lui connectez.
2. Il incombe à l'Utilisateur de maintenir des copies de sauvegarde régulières de son vault et de ses fichiers de travail, et de les placer sous gestion de versions, avant de confier des écritures à un agent.
3. Aucune stipulation du présent article ne saurait limiter la responsabilité d'ArboRithm en cas de dommage corporel, de dol ou de faute lourde, ni les droits que la loi reconnaît de manière impérative au consommateur, ni pour tout autre motif d'ordre public ne pouvant faire l'objet d'une exclusion légale.

### 11. Durée et résiliation
Le présent Contrat prend effet à l'installation du Logiciel et dure tant que vous l'utilisez. Vous pouvez y mettre fin à tout moment en désinstallant le Logiciel. La licence prend fin de plein droit et immédiatement en cas de violation de l'une quelconque de ses stipulations ; vous devez alors cesser tout usage du Logiciel et supprimer l'ensemble de ses copies de vos machines. Les articles 3, 6.4, 9, 10 et 13 survivent à la fin du Contrat.

### 12. Modification du Contrat
ArboRithm peut faire évoluer le présent Contrat. Une nouvelle version s'applique aux versions du Logiciel distribuées avec elle ; elle est publiée avec le Logiciel et signalée dans la note de version. Une version déjà installée reste régie par le Contrat qui l'accompagnait. Aucune modification ne pourra réduire la garantie de l'article 6.4.

### 13. Droit applicable, juridiction et dispositions générales
Le présent Contrat est régi et interprété conformément au droit français. En cas de litige relatif à sa validité, son interprétation ou son exécution, les tribunaux compétents du ressort du domicile professionnel d'ArboRithm seront seuls compétents, sous réserve des règles impératives de compétence applicables aux consommateurs. Le présent Contrat constitue l'intégralité de l'accord entre vous et ArboRithm sur le Logiciel. Si l'une de ses clauses est déclarée nulle, les autres restent en vigueur. Le fait de ne pas se prévaloir d'une clause ne vaut pas renonciation.

---

# End-User License Agreement (EULA) — Kessho

**Version 2.0 — Proprietary Freeware. This English version is a translation; the French version prevails.**
*Effective date: October 11, 2026.*
*Copyright © 2026 Benjamin Dubois, EI, trading as ArboRithm. All rights reserved.*

**Publisher**: Benjamin Dubois, sole trader (French "entrepreneur individuel", EI), trading under the name "ArboRithm" — SIREN: 490 123 296 — contact: app@arborithm.fr. In this Agreement, "ArboRithm" means this publisher.

By downloading, installing, or using Kessho (the "Software" or "Application"), you agree to be bound by the terms of this Agreement. If you do not agree to these terms, do not install or use the Software.

### 1. Scope
This Agreement governs exclusively the binary executables of Kessho distributed by ArboRithm, including its MCP server `kessho-mcp`, their updates and documentation. It grants no rights to the source code, which remains proprietary and unpublished.

### 2. Grant of License
ArboRithm grants you a non-exclusive, personal, royalty-free, worldwide, non-transferable license to install and use the Software, for personal, professional, or commercial purposes, on any number of machines you own or control, for the duration of the rights.

### 3. Intellectual Property
1. **The Software**: the Software is licensed, not sold. ArboRithm retains full and exclusive ownership of the Software, its architecture, design, documentation, and of the names and trademarks "Kessho" and "ArboRithm". No intellectual property right is transferred to you.
2. **Your Vault and Data**: you retain sole and exclusive ownership of your memory vault — notes, atoms, archives, Markdown files and any other file it contains — and of everything you place in it or have placed in it, including by third-party agents or services you connect to the Software ("User Data"). ArboRithm claims no right of any kind over your work or output, and this Agreement grants it none.

### 4. Restrictions
Unless explicitly authorized in writing by ArboRithm, you may not:
1. Sell, rent, lease, lend, sublicense, redistribute, or offer the Software as a hosted service (SaaS, shared remote desktop or unauthorized download mirror);
2. Decompile, disassemble, reverse engineer, or attempt to extract source code or trade secrets from the Software, except to the extent strictly allowed by article L. 122-6-1 of the French Intellectual Property Code for interoperability;
3. Modify, adapt, translate, or create derivative works of the Software;
4. Remove or alter any proprietary, trademark or license notice;
5. Circumvent, disable, or tamper with any security or integrity mechanisms;
6. Use the Software for any unlawful purpose.

### 5. AI Agents and Third-Party Services
1. **Human Oversight**: the Software does not itself call any AI model; through its MCP server, it exposes your vault to the third-party AI agents you connect to it, which can read it and write to it. You acknowledge that all reads, writes and file changes made in your vault by those agents, and all commands they ask the Software to execute, remain under your sole responsibility of review and validation.
2. **Third-Party Services and Costs**: the agents you connect to the Software, and the third-party model providers or APIs they use, receive the vault content they request. You remain solely responsible for adhering to their terms of service and covering any associated token usage, subscription fees, or API costs tied to your own keys or accounts. What these services produce is governed between you and their providers by the latter's terms.

### 6. Data and Privacy
1. **No collection today**: ArboRithm collects no usage data. The Software contains no telemetry, no audience measurement tool, no error report sent to ArboRithm, and requires no account. It processes your User Data on your device; ArboRithm does not access or receive it.
2. **Network communications**: the Software connects to the Internet only to check for and download its updates (article 7), and to the services you configure or designate yourself — the remote Git repository of your vault, and GitHub, through the "gh" tool signed in on your machine, when an agent asks it for the history of a repository you designate — directly between your device and those services, without going through ArboRithm. Git synchronisation only takes place with the remote repository you have chosen, and no other: the Software automatically checks it for changes (`git fetch`) every ten minutes while its window is active, and before each write by an agent when you have enabled automatic synchronisation; it sends the content of your vault to it (`git push`) only when you ask, directly or through an agent, or through automatic synchronisation if you have enabled it. On Windows, the installer may download the WebView2 runtime from Microsoft if it is missing.
3. **Future usage measurement**: ArboRithm reserves the right to introduce, at a later date, a measurement of the Software's usage, for the sole purpose of improving it. If it does so: the measurement will be limited to technical and anonymous data (for example the Software version, the operating system, the features used and the errors encountered); you will be informed before any collection, through a new version of this Agreement and through the release note of the version that introduces it; it will be subject to your prior consent where the law requires it, and you will be able to turn it off at any time in Settings; this data will not be sold, rented or transferred.
4. **Guarantee: your personal and private data will never be collected.** This guarantee applies today and to any future measurement. It covers in particular: your identity, contact details and identifiers; your User Data (the content of your vault: notes, atoms, archives, Markdown files, instructions and exchanges with agents); the names and paths of your files, folders, projects and vaults, and the addresses of your remote Git repositories; your secrets, tokens and keys; and any data that could identify you. The IP address through which a future measurement would transit will be neither stored nor associated with the measured data.
5. For any question about your data: app@arborithm.fr.

### 7. Updates
The Software checks for available updates with its distribution infrastructure (GitHub Releases, operated by GitHub, Inc.), which receives on that occasion, as for any network request, your device's IP address and technical headers, and processes them under its own privacy statement. The Software never checks for updates at launch: it only does so upon your action (Settings › Updates, "Check"), or when an agent connected to the Software calls its version check tool (`mem_check_update`), at most once per hour; the `KESSHO_NO_UPDATE_CHECK` environment variable turns the latter off. For a private distribution channel, the Software uses the "gh" tool signed in on your machine, whose token is sent to GitHub only. An update is downloaded and installed upon your action. Each version is governed by the Agreement that accompanies it.

### 8. Third-Party and Open Source Components
The Software includes libraries and software components distributed under free or open source licenses (including MIT, Apache 2.0, BSD, ISC, Mozilla Public License 2.0, Unicode). Those components are governed by their respective licenses, which prevail over this Agreement solely regarding those specific components. Their texts and copyright notices are provided with the Software ("THIRD-PARTY-NOTICES" file, also viewable in Settings › About).

### 9. Disclaimer of Warranties
The Software is provided free of charge "AS IS", without warranty of any kind, express or implied, including but not limited to fitness for a particular purpose, uptime, or error-free or vulnerability-free operation, to the fullest extent permitted by law. ArboRithm has no obligation to provide maintenance, support, or bug fixes. Nothing in this Agreement limits the rights the law grants you on a mandatory basis, in particular as a consumer.

### 10. Limitation of Liability
To the maximum extent permitted by applicable law:
1. ArboRithm shall not be liable for any indirect, incidental, special, or consequential damages, nor for any loss of data, corrupted or deleted vault content, downtime, or lost profits arising out of the use or inability to use the Software or the actions of the agents you connect to it.
2. You are responsible for maintaining regular backups and version control snapshots of your vault and working files before entrusting writes to an agent.
3. Nothing in this Agreement limits liability for bodily injury, wilful misconduct or gross negligence, nor the rights the law grants consumers on a mandatory basis, nor any other non-waivable statutory liability.

### 11. Term and Termination
This Agreement takes effect when the Software is installed and lasts as long as you use it. You may end it at any time by uninstalling the Software. This license terminates automatically and immediately if you breach any of its terms; you must then cease all use and remove all copies of the Software from your machines. Articles 3, 6.4, 9, 10 and 13 survive termination.

### 12. Changes to the Agreement
ArboRithm may change this Agreement. A new version applies to the versions of the Software distributed with it; it is published with the Software and flagged in the release note. A version already installed remains governed by the Agreement that accompanied it. No change may reduce the guarantee of article 6.4.

### 13. Governing Law, Jurisdiction and General Provisions
This Agreement is governed by French law. Any dispute arising in connection with this Agreement shall be submitted to the competent courts having jurisdiction over ArboRithm's professional domicile, subject to the mandatory jurisdiction rules applicable to consumers. This Agreement is the entire agreement between you and ArboRithm regarding the Software. If any clause is held void, the others remain in force. Failure to rely on a clause does not constitute a waiver.
