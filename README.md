# elfinder-boostrap-theme
Theme for elFinder to fit in with Bootstrap

This Theme modifies the `theme.css` theme file, and adds LibreICONS Font Icons, or Font Awesome Icons, of SVG Icons from LibreICONS to elFinder.

Simply download this repo, then:

### SVG Version
Copy the `elfinder-bootstrap-svg.css` file and `libre-svg-black.svg/` to the elFinder css folder, then add the below link to the stylesheet to your markup after linking in the elFinder css file:
````html
<link rel="stylesheet" type="text/css" href="elfinder/css/theme-bootstrap-svg.css">
````

### LibreICONS Version
We recommend using [LibreICONS](https://github.com/StudioJunkyard/LibreICONS) locally within your application, and commenting out the @import as the Icons will already be available within your application, otherwise leave the @import as is to bring in the Icons for use.
[LibreICONS](https://github.com/StudioJunkyard/LibreICONS) also support the Icons for [Summernote](https://github.com/summernote/summernote/), so it's Font Icons aren't necessary.
Copy the `elfinder-bootstrap-libre-icons.css` file to the elFinder css folder, then add the below link to the stylesheet to your markup after linking in the elFinder css file.
````html
<link rel="stylesheet" type="text/css" href="elfinder/css/theme-bootstrap-libreicons.css">
````

### FontAwesome Version
We recommend using FontAwesome v4.4.0 locally within your application, and commenting out the @import, otherwise leave the `@import` as is to bring in the Icons for use.
Copy the `elfinder-bootstrap-fontawesome.css` file to the elFinder css folder, then add the below link to the stylesheet to your markup after linking in the elFinder css file.
````html
<link rel="stylesheet" type="text/css" href="elfinder/css/theme-bootstrap-fontawesome.css">
````

This screenshot shows the LibrICONS Font version of the theme:
![elfinder-bootstrap-theme-screenshot](https://github.com/StudioJunkyard/elfinder-bootstrap-theme/blob/master/elfinder-bootstrap-theme.png)

### TODO:
- Modify Quicklook Dialog
