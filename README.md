# Hey!

This is a starter kit for setting up any web project faster.

## Requires

* [Install NodeJS](https://docs.npmjs.com/getting-started/installing-node)
* [Install Compass](http://compass-style.org/install/)
* Hologram (`sudo gem install hologram`)

## Installation

### Symfony
The folder `assets` goes in `app/Resources/`.

Adjacent files (`.gitignore`, `gulpfile.js`, `package.json`, `package-lock.json`) go at the project root.

### Wordpress
The folder `assets` goes in `wp-content/themes/{my-theme}`.

Adjacent files (`.gitignore`, `gulpfile.js`, `package.json`, `package-lock.json`) go at the project root.

### Drupal
The folder `assets` goes in `sites/all/themes/{my-theme}`.

Adjacent files (`.gitignore`, `gulpfile.js`, `package.json`, `package-lock.json`) go at the project root.

### Bolt
The folder `assets` goes in `public/theme/{my-theme}`.

Adjacent files (`.gitignore`, `gulpfile.js`, `package.json`, `package-lock.json`) go at the project root.

Then, run :

`npm install`

Then, open `gulpfile.js` and set the variable `techName` to :
 
 * bolt
 * drupal
 * symfony
 * wordpress
 
Set `themeName` to the name of your theme (used by Gulp in Drupal, Bolt and Wordpress).