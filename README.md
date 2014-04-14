Sublime Text 3 Configuration
============================

For when I may not have access to my online file storage of choice.

## Usage
   *   Install [Sublime Text 3](http://www.sublimetext.com/3)
   *   Install [Sublime Package Control](https://sublime.wbond.net/installation)
   *   Clone this repository wherever you want to store your settings

      ```bash
      $ git clone https://github.com/btleffler/sublime-text-config.git my/awesome/config/location
      ```

   *   Install [Package Syncing](https://sublime.wbond.net/packages/Package%20Syncing)
      *   [Tell Package Syncing where you cloned your config](https://github.com/csch0/SublimeText-Package-Syncing#second-machine-or-after-a-fresh-installation)
   *   Get coding!
   *   Whenever changes are made, ``commit`` and ``push`` them. Next time you're on another machine without access to a syncing online file storage, ``pull`` changes from this repo and Package Syncing will do the rest.

## Notes
   *  Don't forget to install the dependencies for the various linters.
      *   node.js, npm
         *   coffee-script, coffeelint, jshint, csslint
      *   php
