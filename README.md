# Magento2 ReCaptchaB2b

[![Total Downloads](https://poser.pugx.org/faonni/module-re-captcha-b2b/downloads)](https://packagist.org/packages/faonni/module-re-captcha-b2b)
[![Latest Stable Version](https://poser.pugx.org/faonni/module-re-captcha-b2b/v/stable)](https://packagist.org/packages/faonni/module-re-captcha-b2b)

Extension is integrate Google Recaptcha with B2B Extension your Magento2 store.

### New Company page

<img alt="Magento2 ReCaptchaB2b" src="https://karliuka.github.io/m2/re-captcha-b2b/createCompany.png" style="width:100%"/>

## Compatibility

Magento EE 2.2.x

## Install

#### Install via Composer (recommend)

1. Go to Magento2 root folder

2. Enter following commands to install module:

    ```bash
    composer require faonni/module-re-captcha-b2b
    ```
   Wait while dependencies are updated.
   
#### Manual Installation
   
1. Install [ReCaptcha](https://github.com/karliuka/m2.ReCaptcha)
   
2. Create a folder {Magento root}/app/code/Faonni/ReCaptchaB2b

3. Download the corresponding [latest version](https://github.com/karliuka/m2.ReCaptchaB2b/releases)

4. Copy the unzip content to the folder ({Magento root}/app/code/Faonni/ReCaptchaB2b)

### Completion of installation

1. Go to Magento2 root folder

2. Enter following commands:

    ```bash
	php bin/magento setup:upgrade
	php bin/magento setup:di:compile
	php bin/magento setup:static-content:deploy  (optional)

### Configuration Frontend

In the Magento Admin Panel go to *Stores > Configuration > Customers > Customer Configuration > ReCAPTCHA*.

<img alt="Magento2 ReCaptchaB2b" src="https://karliuka.github.io/m2/re-captcha-b2b/config.png" style="width:100%"/>

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



