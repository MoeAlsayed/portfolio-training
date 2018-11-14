# published at https://moealsayed.github.io/portfolio-training/

## Requirements

* NodeJS 8+
* npm package manager

## Installation

**Important for Ubuntu 16.04:**

Run the following command to fix a problem with the file watcher that is used to watch for changes of the SCSS and JS files in your project:

```echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p```

**Installation Steps:**

* Install NodeJS, if you haven't done already. I suggest to use the [Node Version Manager](https://github.com/creationix/nvm).
* Download the ZIP file from [here](https://github.com/noreading/bootstrap4-custom-boilerplate/archive/master.zip).
* Extract the files to your project directory:<br>
 ```unzip bootstrap4-custom-boilerplate.zip```
* Run the setup script:<br>
 ```npm run setup```

## Editing SCSS + JavaScript

### CSS

The SCSS files are located in the __/assets/src/sass/__ directory.  

### JavaScript

The JavaScript files are located in the __/assets/src/js/__ directory.  
Add your own code to the __/assets/src/js/app.js__.

### Watching for changes

Every time you want to change CSS or JavaScript file you should use the __watch__ command, so that you don't have to start the build process manually. The __watch__ command will recompile all CSS and JavaScript files, if you change them.

```npm run watch```

## License

This project is available under [MIT License](./License.md) and is free for private and commercial usage.
