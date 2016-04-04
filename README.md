# elfinder-boostrap-theme
Theme for elFinder to fit in with Bootstrap

This Theme modifies the `theme.css` theme file, and adds SVG Icons from LibreICONS to elFinder.

Simply download this repo, and copy the `theme.css` and `svg/` files/folder to the elFinder `css` folder, and include it like any other theme for elFinder.

### SVG Version
````html
<link rel="stylesheet" type="text/css" href="elfinder/css/theme-bootstrap-svg.css">
````
https://github.com/summernote/summernote
### LibreICONS Version
We recommend using [LibreICONS](https://github.com/StudioJunkyard/LibreICONS) locally within your application, and commenting out the @import
[LibreICONS](https://github.com/StudioJunkyard/LibreICONS) also support the Icons for [Summernote](https://github.com/summernote/summernote/), so it's Font Icons aren't necessary.
````html
<link rel="stylesheet" type="text/css" href="elfinder/css/theme-bootstrap-libreicons.css">
````

### FontAwesome Version
We recommend using FontAwesome v4.4.0 locally within your application, and commenting out the @import
````html
<link rel="stylesheet" type="text/css" href="elfinder/css/theme-bootstrap-fontawesome.css">
````

![elfinder-bootstrap-theme-screenshot](https://github.com/StudioJunkyard/elfinder-bootstrap-theme/blob/master/elfinder-bootstrap-theme.png)

### TODO:
- Get Font Icons working for those that want to use Font Icons, FontAwesome, and LibreICONS.
