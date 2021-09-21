## Position

### poition: static;

* default option. all elements get it
* top/left/bottom/right doeasn't apply
* "standart document flow"
* used very rarely, only when override is needed

### position: relative;

* top/left/bottom/right can be used
* when positioned, still takes space in the standard flow
* top/bottom and left/right cant be used simultaneously
* negative values moves element outward, positive - inward
* usually px are used, but anything can be used
* percents mean percents from parent (usually)

### position: abolute;

* takes element out from standard flow
* positioning positions element in the nearest parent container, which has position - not static
* gets display:block no matter what
* width of this container difined by its content
* left-right and top-bottom can be used simultneously - they set distance from parent container border

### position: fixed;

* same as absolute, but always sticks to viewport

### position: sticky;

* when on screen, behaves as position : absolute;
* when touches the border, becomes fixed

## Measurment units

**not used anymore:** mm, cm, pt, pc

* font size is some unit which is part of font 

### px

* basic
* can be 0.5px
* con - always static

### em, rem

* relative to font size of the parent container
* ex, ch - size of "x" and "0" - never used
* rem is relative to font size in html element

### %

* percent is taken from parent font size

### vh, vw, vmax, vmin

* vh - 1% from height
* vw - 1% from width
* vmax - maximum from width/height
* vmin - minimum

## display

### display: none

* element is taken from DOM completely

### display: flex, display: grid

* used for flexbox and grid only (own places)

### display: block

* by default, <p>, <div>, <h1>
* width/height can be set
* takes max possible width
* always goes one under another (if no float) 

### display: inline

* by default, <span>, <img>, <a>
* cant use width/height, decided by content
* rectangles, but goes one after another in a row (like text)
* if inline is near block element, there will be newline between them

### display: inline-block

* goes like text, but width/height can be used
* verical-align allows to do vertical align (middle, sub, ...)

### display: table-*

* allows to give table property to any set of divs
* actually, current table tags are these ones
* table-cell can be used to do vertical-align

## elements centring

horizontal

For 
