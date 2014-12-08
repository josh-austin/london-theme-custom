london-theme-custom
===================

Source code to quickly customize colors for the London Theme in Outsystems

![alt text](https://github.com/josh-austin/london-theme-custom/blob/master/london_teal_and_brown.PNG "Custom theme example")


## Compilation
To compile to CSS, run the command `lessc london.less > london.css`  
For details, refer to [this page](http://lesscss.org/#using-less).

## Create a new theme
Simply change the color variables in `variables.less`, compile, and copy/paste the contents of your generated london.css into your project theme.  

## Variables
`@color-1-bg` - the background color for the page header, primary buttons, links, and active menu items  
`@color-1-fg` - the foreground color for the page header, primary buttons, links, and active menu items  
`@color-2-bg` - the background color for the menu bar and non-primary buttons  
`@color-2-fg` - the foreground color for the menu bar and non-primary buttons
