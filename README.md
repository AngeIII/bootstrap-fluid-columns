# bootstrap-fluid-columns
Extension for twbs/bootstrap: Add an ability to bootstrap to allow create layouts for 3, 5, 6, 7, 8, 9, 10, 11 equals columns.

## Version

    Under development, V: 0.1

## Usage
Same as default bootstrap grid work: class col-[type]-size:
Types:

    xs
    sm
    md
    lg
Sizes:

    1_1
    1_2,
    2_2,
    1_3,
    2_3,
    etc// up to 12_12
    
## Classes example

    col-sm-1_3 ( 33.3 % of width )
    col-sm-2_3 ( 66.6 % of width )
    
## Files

    /dist/fluid-grid.css - compiled less files and optimized with http://www.codebeautifier.com/
    /dist/fluid-grid.min.css - minified code fluid-grid.css
    /src/less/fluid-grid.less - main less file where is defined a logic

## HTML

    Include bootstrap library in your project and include fluid-grid.min.css. Then you are free to use combinations for standard bootstrap classes and fluid layout classes.
    For example if you want to create 5 columns grid just use *_5 classes ( col-sm-1_5 (20%), col-sm-2_5(40%), col-sm-3_5(60%) and etc. ).
    
### Copyright and license

Copyright 2015 Pavel I, thq.lv.
Code released under [the MIT license](https://github.com/AngeIII/bootstrap-fluid-columns/blob/master/LICENSE).

### Author
    Pavel Ivanov
    pavel.thq [at] gmail.com

<a href="http://thq.lv/">http://thq.lv</a>