# Magento2 ReCaptchaB2b

Extension is integrate Google Recaptcha with B2B Extension your Magento2 store.

## Compatibility

Magento EE 2.2.x, 2.3.x, 2.4.x

## Install

Before installation, you need to install the [ReCaptcha](https://github.com/karliuka/m2.ReCaptcha) module

#### Install via Composer (recommend)

1. Go to Magento2 root folder

2. Enter following commands to install module:

    ```bash
    composer faonni/module-re-captcha-b2b
    ```
   Wait while dependencies are updated.

#### Manual Installation

1. Create a folder {Magento root}/app/code/Faonni/ReCaptchaB2b

2. Download the corresponding [latest version](https://github.com/karliuka/m2.ReCaptchaB2b/releases)

3. Copy the unzip content to the folder ({Magento root}/app/code/Faonni/ReCaptchaB2b)

#### Completion of installation

1. Go to Magento2 root folder

2. Enter following commands:

    ```bash
    php bin/magento setup:upgrade
    php bin/magento setup:di:compile
    php bin/magento setup:static-content:deploy  (optional)
    ```
### New Company page

<img alt="Magento2 ReCaptchaB2b" src="https://karliuka.github.io/m2/re-captcha-b2b/createCompany.png" style="width:100%"/>

## Uninstall
This works only with modules defined as Composer packages.

#### Remove Extension

1. Go to Magento2 root folder

2. Enter following commands to remove:

    ```bash
    composer remove faonni/module-re-captcha-b2b
    ```
### Completion of uninstall

1. Go to Magento2 root folder

2. Enter following commands:

    ```bash
    php bin/magento setup:upgrade
    php bin/magento setup:di:compile
    php bin/magento setup:static-content:deploy  (optional)
    ```
