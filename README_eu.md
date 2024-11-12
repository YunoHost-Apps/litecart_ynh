<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Litecart YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/litecart.svg)](https://ci-apps.yunohost.org/ci/apps/litecart/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/litecart.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/litecart.maintain.svg)

[![Instalatu Litecart YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=litecart)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Litecart YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Litecart is an open source shopping-cart in 1 file of embedded database (SQLite), convenient dashboard UI and simple site.

### 🏆 Features

💰 Support for Popular Payment Systems: Accept payments seamlessly with support for popular payment systems, ensuring a smooth checkout experience for your customers.

🔑 Sell Files and License Keys: Whether you're selling digital files or license keys, litecart has you covered, providing flexibility in the types of products you can offer.

⚙️ Lightweight and Efficient: litecart utilizes SQLite as its embedded database. This results in a lightweight website that performs exceptionally well.

☁️ Easily Customizable: Modify and customize your litecart website effortlessly to match your branding and unique requirements, making it truly your own.

🧞‍♂️ Convenient Administration Panel: With a user-friendly dashboard UI, litecart offers a hassle-free administration panel, allowing you to manage your store, inventory, and orders with ease.


**Paketatutako bertsioa:** 0.1.12~ynh1

## Pantaila-argazkiak

![Litecart(r)en pantaila-argazkia](./doc/screenshots/banner.png)

## Dokumentazioa eta baliabideak

- Administratzaileen dokumentazio ofiziala: <https://github.com/shurco/litecart?tab=readme-ov-file#adding-payment-systems>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/shurco/litecart>
- YunoHost Denda: <https://apps.yunohost.org/app/litecart>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/litecart_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/litecart_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/litecart_ynh/tree/testing --debug
edo
sudo yunohost app upgrade litecart -u https://github.com/YunoHost-Apps/litecart_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
