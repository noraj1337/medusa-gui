# Medusa Gui

[![Rawsec's CyberSecurity Inventory](http://list.rawsec.ml/img/badges/Rawsec-inventoried-FF5050_flat-square.svg)](http://list.rawsec.ml/tools.html#Medusa-gui)

Medusa Gui will automatically detect your operating system and compile for it.

## Usage

Commands are as follow

```
$ ant dist    //creates medusa-gui.jar under bin/
$ ant clean   //cleans up compiled files
# ant install //installs the Medusa-GUI
# ant remove  //uninstalls the Medusa-GUI
```

## Installation

How to install:
Run the following command as root -

```
# ant install
```

and the Medusa-GUI will be installed to the /usr/local directory.

## Uninstallation

How to uninstall:

```
# ant remove
```

## Note
JAVA_HOME has to be set to your JDK

For example in your `.bashrc`, `.zshrc` or `.profile`.

```
JAVA_HOME=/usr/lib/default-java
export JAVA_HOME
```
