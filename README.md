# Binary Ninja IPython Kernel (v1.0)
Author: **Florian Magin**

_Spawn an IPython Kernel inside binja ._

## Description:

This plugin starts an IPython kernel when binja starts which can be attached to with e.g.'jupyter console --existing'

To get access to the variables like the current open binary view load the extension with '%load_ext binjamagic'

This extension can be installed via 'pip install ./' from the root of the plugin repo

If you want the qt console, you will have to install it

## Minimum Version

This plugin requires the following minimum version of Binary Ninja:

 * release - 0
 * dev - 1.0.dev-576


## Required Dependencies

The following dependencies are required for this plugin:

 * pip - jupyter, qtconsole


## License

This plugin is released under a [MIT](LICENSE) license.


