## npm init --y

# To create package.json with default values(Automatically).

## other wise we can create package.json file manually.

## set default values for automatic creation

# npm set init-author-name "chinmaya"

- to set author name as 'chinmaya' for all init --y commands

## to check defaults

# npm get init-author-name

## to delete defaults

# npm config delete init-author-name

## To install a Package

# npm install packageName or npm install packageName --save

- npm install lodash

# installs a node module called lodash from npm

## To install all the packages in package.json file

# npm install

## To install packages only in devlopement environment

# npm install gulp --save-dev

## install a package with particular version

# npm install packageName@version

## To install Multiple Packages at a time

# npm install package1 package2

## To install Modules in Production from Package.json (excludes dev dependencies)

# npm install --production

## To uninstall a package

# npm uninstall packagename (or) npm remove packagename (or) npm rm packagename

## Update a package

# npm update packagename

## Update all packages in Package.json

# npm update

---

# Local installation of modules means they are inside the project i.e in node_modules folder of your app

# Global installation the modules are installed in your system which are available system wide or all the projects in your system

---

## installing a package globally

# npm install -g packagename (or) npm install -global packagename

## To find the global modules location

# npm root -g

- usally we install nodemon, liveserver in global

---

## To list all the dependencies

# npm list

## npm list --depth 0 or 1 or 2
