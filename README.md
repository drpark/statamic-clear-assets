# Statamic Clear Assets

![Statamic 3.0+](https://img.shields.io/badge/Statamic-3.0+-FF269E?style=for-the-badge&link=https://statamic.com)
[![Latest Version on Packagist](https://img.shields.io/packagist/v/swiftmade/statamic-clear-assets.svg?style=for-the-badge)](https://packagist.org/packages/swiftmade/statamic-clear-assets)

> Get rid of unused assets taking up space in your project.

Works by scanning your entire `content` directory. An asset will be removed if none of the files in this directory points to it.

![Screenshot](screenshot.png?raw=true "This is how it looks like in action")

## How to Install

You can search for this addon in the `Tools > Addons` section of the Statamic control panel and click **install**, or run the following command from your project root:

```bash
composer require swiftmade/statamic-clear-assets
```

## How to Use

Simply run:

```bash
php please assets:clear
```