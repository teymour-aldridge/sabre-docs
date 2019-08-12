# Customising Sabre.
### Guide
Sabre is written in SCSS which makes it easy to customise. To customise Sabre you will need to have a sass compiler installed on your computer.

To start clone Sabre to your local machine.
```commandline
git clone https://github.com/teymour-aldridge/sabre
```
This should create a folder with roughly the following file structure:
```
sabre/
    sass/
        styles.scss # You can delete this file
        base/
            # There should be some .scss files in this folder. 
        components/
            # There should be some .scss files in this folder. 
        layout/
            # There should be some .scss files in this folder. 
        colours/
            # There should be some .scss files in this folder. 
        forms/
            # There should be some .scss files in this folder. 
        typography/
            # There should be some .scss files in this folder. 
```
Create a new file scss in the sabre directory (any name will do).
```commandline
cd sabre
touch custom-styles.scss 
``` 
Open this file a text editor and type the following code.
```scss
@import "./sass/base/variables";
// Update some variables
$primary: $hotpink;
// Import the rest of Sabre
@import "./sass/colours/colours";
@import "./sass/layout/layout";
@import "./sass/components/components";
@import "./sass/typography/typography";
@import "./sass/forms/forms";
```
This works by the default SCSS variables which are set in `sass/base/variables.scss` with custom ones before importing the rest of Sabre.
There are many different variables you can change.