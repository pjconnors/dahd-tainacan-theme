# dahd-tainacan-theme

This is just a light fork of the default Tainacan theme, with some modifications made to suit the Digital Art History Directory. 

# Building

You'll need a sass implementation. Since the ruby version is deprecated, better get this via node. 
You'll also need Composer. 

Copy `build-config-sample.cfg` to `build-config.cfg`, and change `destination` to the full path for the themes directory, e.g., /var/www/html/wp-content/themes. 

Then, run `./build.sh` 
