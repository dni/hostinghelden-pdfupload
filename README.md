# Hostinghelden Magento2 PDF Upload
lets you upload and hyperlink PDF's in the wysiwyg

# Requirements

Magento Composer Installer: To copy the module contents under app/code/ folder. In order to install it run the below command on the root directory:

```sh
composer require magento/magento-composer-installer
```

Add the VCS repository: So that composer can find the module. Add the following lines in your composer.json

```json
"repositories": [{
  "type": "vcs",
  "url": "https://github.com/dni/hostinghelden-pdfupload"
}],
```

# Installation

Add the module to composer:

```sh
composer require hostinghelden/hostinghelden-pdfupload
```
