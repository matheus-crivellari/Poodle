# POODLE
## CLI Tool for Moodle Plugin development
---
Many of the most used and powerful web development frameworks around the world work with the help a CLI tool in order to ease the development job.

The idea behind this project is to provide a CLI tool for Moodle as well, so that Moodle Plugin developers can work with ease, and avoid common human mistakes when developing, leaving the hard work of creating files and structuring folders for the machine.

## Documentation
### Getting started
1. Create a folder where we're going to put our plugin files inside;

2. Then enter the just created folder and paste the poodle file inside it;


3. The first and handful command, is `init`, it brings up a basic folder structure and the minimum required files for a Moodle plugin to work.

        php poodle init <type> <name> <"Exhibition name">
    - `<type>` (required): Following the Frankenstyle Moodle's convention for naming a plugin you must choose one of the available plugin types;
    - `<name>` (required): Following the Frankenstyle Moodle's convention for naming a plugin you must choose a name for your plugin;
    - `<"Exibition name">` (optional): You can set an exhibition name which will be displayed to the user in Moodle administration pages, if you leave it blank, it will use the same value as the component name which is `<type>`_`<name>`;



## Contributing
Feel free to clone this repository and work on any feature you feel like, make a pull request and we will moderate your contribution and if we judge it's worth we'll make it live.