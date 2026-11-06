# Politique de confidentialité — Hilitely

**Dernière mise à jour :** 7 novembre 2026

Cette politique décrit comment l'extension Chrome **Hilitely** (« l'Extension ») traite les informations.

## Qui fournit l'Extension

L'Extension est publiée par **PeterShift**.
Contact : **petershift.dev@gmail.com**

## Ce que fait l'Extension

Sur un site que vous activez, l'Extension surligne un passage que vous sélectionnez et retrouve ce surlignage après un rechargement ou une modification de la page, grâce aux mots et non à leur place dans la mise en page. Les notes, les étiquettes et la bibliothèque de citations restent sur cet ordinateur.

## Ce que l'Extension enregistre

Lorsque vous surlignez du texte, l'Extension enregistre une fiche sur votre ordinateur :

- le texte cité et environ 100 caractères avant et après, afin de retrouver le surlignage ;
- l'adresse de la page, son adresse canonique si la page en déclare une, et le titre de la page ;
- la couleur, ainsi qu'une note et des étiquettes si vous en saisissez ;
- la date de création et de modification du surlignage, et s'il a été retrouvé sur la page la dernière fois.

Les réglages restent aussi sur cet ordinateur : la dernière couleur choisie, le placement du curseur dans le champ de note, le tri des sites dans la bibliothèque et les sites activés que vous avez désactivés.

## Où vont les données

Nulle part. Les surlignages restent dans le navigateur, dans la base propre à l'Extension sur cet ordinateur. L'Extension n'a pas de serveur, pas de compte et pas d'analyse. Elle n'envoie aucune requête réseau. Nous ne recevons ni vos surlignages, ni vos notes, ni les adresses des pages que vous lisez.

## Quels sites elle peut lire

L'Extension ne demande pas à lire tous les sites. Elle ne fonctionne que sur les sites que vous activez depuis l'icône de la barre d'outils, un site à la fois, par la boîte de permission de Chrome. Tant que vous ne le faites pas, elle n'ajoute rien à la page.

Désactiver un site le met en pause. Les surlignages disparaissent des onglets ouverts de ce site, et le script n'y redémarre pas tant que vous ne le réactivez pas. L'autorisation de Chrome reste en place, donc la réactivation ne redemande pas l'accès. « Remove access to this site » retire l'autorisation. La prochaine fois que vous activez ce site, Chrome redemande. Les citations enregistrées restent dans la bibliothèque dans les deux cas.

## Sauvegardes

Un fichier de sauvegarde n'est créé que lorsque vous choisissez Download backup. Il est enregistré là où le navigateur place les téléchargements. L'import lit un fichier que vous choisissez. Ni l'un ni l'autre n'est envoyé où que ce soit.

## Supprimer vos données

Supprimez un surlignage depuis la page ou la bibliothèque, ou utilisez Delete all on this site dans la bibliothèque. Retirer l'Extension efface toutes ses données locales avec le nettoyage habituel du navigateur.

## Autorisations

| Autorisation | Pourquoi elle est demandée |
| --- | --- |
| `storage` | Enregistre les réglages sur cet ordinateur : la dernière couleur de surlignage, le placement du curseur dans la note, les sites activés que vous avez désactivés et le tri des sites dans la bibliothèque. Les citations sont dans la base propre à l'Extension ; cette autorisation ne les stocke pas. |
| `activeTab` | Lorsque vous cliquez sur l'icône de la barre, la fenêtre lit l'adresse de l'onglet actuel pour afficher l'interrupteur de ce site et parcourir les surlignages de la page. |
| `scripting` | Démarre le surlignage dans l'onglet actuel juste après l'activation du site, et dans les onglets déjà ouverts de ce site, sans recharger la page. Lorsque vous désactivez le site, les surlignages sont retirés de ces onglets. |
| Accès aux sites | Il n'est pas accordé à l'installation. Chrome demande un site à la fois, la première fois que vous l'activez. Le surlignage ne fonctionne que sur les sites que vous avez autorisés et pas désactivés. Le désactiver l'arrête sur ce site et conserve l'autorisation. « Remove access to this site » la retire. |

## Code distant

L'Extension n'exécute que les fichiers locaux livrés dans le paquet. Elle ne télécharge pas de JavaScript distant et n'en exécute pas.

## Usage limité

Les données servent uniquement à réafficher vos surlignages et à les lister dans la bibliothèque. Elles ne sont pas vendues, pas transmises à qui que ce soit, pas utilisées pour la publicité ni pour évaluer la solvabilité, et personne ne les lit. Cet usage est conforme à la Chrome Web Store User Data Policy (https://developer.chrome.com/docs/webstore/program-policies/limited-use), y compris aux exigences Limited Use.

## Modifications

Si une version ultérieure commence à envoyer des données quelque part, cette politique le dira avant la publication de cette version, et l'Extension vous le demandera d'abord.

## Contact

Questions sur cette politique : **petershift.dev@gmail.com**
