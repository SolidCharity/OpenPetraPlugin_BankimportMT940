# Plugin BankimportMT940

This is a plugin for [www.openpetra.org](http://www.openpetra.org).

## Functionality

You can import bank statements into OpenPetra with the plugin [Bankimport](https://github.com/SolidCharity/OpenPetraPlugin_Bankimport).

Often banks allow in their online banking to download the bank statement as a MT940 file. MT940 is a SWIFT standard.
This plugin allows MT940 files to be imported.

## Dependencies

This plugin requires this plugin:

* https://github.com/SolidCharity/OpenPetraPlugin_Bankimport

## Installation

Please copy this directory to your OpenPetra working directory, to csharp\ICT\Petra\Plugins, or include it like this, if you are using git anyway:

    git submodule add https://github.com/SolidCharity/OpenPetraPlugin_BankimportMT940 csharp/ICT/Petra/Plugins/BankimportMT940

and then run

    nant generateSolution

Please check the config directory for changes to your config files.

## License

This plugin is licensed under the GPL v3.