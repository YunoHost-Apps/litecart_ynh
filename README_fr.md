<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Litecart pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/litecart.svg)](https://ci-apps.yunohost.org/ci/apps/litecart/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/litecart.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/litecart.maintain.svg)

[![Installer Litecart avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=litecart)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Litecart rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Litecart est une boutique en ligne open source en 1 fichier de base de données intégrée (SQLite), une interface utilisateur de tableau de bord pratique et un site simple.

### 🏆 Caractéristiques

💰 Prise en charge des systèmes de paiement les plus courants : Acceptez les paiements en toute transparence grâce à la prise en charge des systèmes de paiement les plus courants, ce qui garantit à vos clients une expérience de paiement fluide.

🔑 Vente de fichiers et de clés de licence : Que vous vendiez des fichiers numériques ou des clés de licence, litecart vous couvre, offrant une flexibilité dans les types de produits que vous pouvez offrir.

⚙️ Léger et efficace : litecart utilise SQLite comme base de données intégrée. Il en résulte un site web léger qui offre des performances exceptionnelles.

☁️ Facilement personnalisable : Modifiez et personnalisez votre site web litecart sans effort pour qu'il corresponde à votre image de marque et à vos besoins uniques, pour qu'il soit vraiment le vôtre.

🧞‍♂️ Panneau d'administration pratique : Avec un tableau de bord convivial, litecart offre un panneau d'administration facile à utiliser, vous permettant de gérer votre boutique, votre inventaire et vos commandes en toute simplicité.


**Version incluse :** 0.1.12~ynh1

## Captures d’écran

![Capture d’écran de Litecart](./doc/screenshots/banner.png)

## Documentations et ressources

- Documentation officielle de l’admin : <https://github.com/shurco/litecart?tab=readme-ov-file#adding-payment-systems>
- Dépôt de code officiel de l’app : <https://github.com/shurco/litecart>
- YunoHost Store : <https://apps.yunohost.org/app/litecart>
- Signaler un bug : <https://github.com/YunoHost-Apps/litecart_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/litecart_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/litecart_ynh/tree/testing --debug
ou
sudo yunohost app upgrade litecart -u https://github.com/YunoHost-Apps/litecart_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
