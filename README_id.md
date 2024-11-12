<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Litecart untuk YunoHost

[![Tingkat integrasi](https://dash.yunohost.org/integration/litecart.svg)](https://ci-apps.yunohost.org/ci/apps/litecart/) ![Status kerja](https://ci-apps.yunohost.org/ci/badges/litecart.status.svg) ![Status pemeliharaan](https://ci-apps.yunohost.org/ci/badges/litecart.maintain.svg)

[![Pasang Litecart dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=litecart)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Litecart secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Litecart is an open source shopping-cart in 1 file of embedded database (SQLite), convenient dashboard UI and simple site.

### 🏆 Features

💰 Support for Popular Payment Systems: Accept payments seamlessly with support for popular payment systems, ensuring a smooth checkout experience for your customers.

🔑 Sell Files and License Keys: Whether you're selling digital files or license keys, litecart has you covered, providing flexibility in the types of products you can offer.

⚙️ Lightweight and Efficient: litecart utilizes SQLite as its embedded database. This results in a lightweight website that performs exceptionally well.

☁️ Easily Customizable: Modify and customize your litecart website effortlessly to match your branding and unique requirements, making it truly your own.

🧞‍♂️ Convenient Administration Panel: With a user-friendly dashboard UI, litecart offers a hassle-free administration panel, allowing you to manage your store, inventory, and orders with ease.


**Versi terkirim:** 0.1.12~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Litecart](./doc/screenshots/banner.png)

## Dokumentasi dan sumber daya

- Dokumentasi admin resmi: <https://github.com/shurco/litecart?tab=readme-ov-file#adding-payment-systems>
- Depot kode aplikasi hulu: <https://github.com/shurco/litecart>
- Gudang YunoHost: <https://apps.yunohost.org/app/litecart>
- Laporkan bug: <https://github.com/YunoHost-Apps/litecart_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/litecart_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/litecart_ynh/tree/testing --debug
atau
sudo yunohost app upgrade litecart -u https://github.com/YunoHost-Apps/litecart_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
