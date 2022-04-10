# Context WP Disable Version

Tested up to: 5.9.1  
Tags: wordpress, security  
Contributors: robertandrews  

## Description

Improve security and file caching issues by disabling display of WordPress version.

### 1. Disable 'generator' meta

WordPress shows its version number in mark-up.

![WP version number as generator](https://www.wpbeginner.com/wp-content/uploads/2021/06/wp-version-default.png)

> Many believe that removing the WordPress version number from your website’s source code can prevent some common online attacks. -- [WPBeginner](https://www.wpbeginner.com/wp-tutorials/the-right-way-to-remove-wordpress-version-number/)

The plugin stops this version number being displayed.

### 2. Disable version for style.css

WordPress appends its version number to stylesheets.

![wp version number in style.css](https://www.wpbeginner.com/wp-content/uploads/2021/06/wp-version-leaked.png)

This may make caching and reload of style.css problematic.

The plugin stops this version number being added.

## Installation

Add the plugin via *Plugins > Add New > Add Plugins > Upload Plugin*.