# Motherplate: A SCSS, HTML5, CSS3, Responsive Boilerplate
This is the boilerplate HTML/CSS I'll start off most projects with.

## Features
* Uses SASS partials to help structure the CSS
* Uses Compass to take advantage of CSS3 mixins so you don't have to worry about browser prefixes (-webkit- etc.)
* Responsive ready 12-column grid system to work across many devices
* Uses Font-Awesome icon fonts for icons
* Uses Normalize to reset browser styles
* Only enough CSS to get you started; no visual styling with this boilerplate
* Only the HTML/JS you need to get started; very little components with this boilerplate

## How to Use
This will vary depending on the framework you are using. The following is how to for a basic static website.

### Install Ruby
Motherplate uses SASS and Compass, which rely on Ruby
Macs come pre-installed with Ruby but if you need to you can <a href="http://www.ruby-lang.org/en/downloads/">download ruby here</a>

### Install the compass gem
Open up terminal (or command line) and install compass 
```
$ gem update --system 
$ gem install compass
```

### Download Motherplate
Download and copy the motherplate files into your new project folder.

### Run compass watch
In terminal go to your project folder and run compass.
```
$ cd sites/mynewproject/
$ compass watch
```

### Sit back and watch your CSS automatically compile
When you make changes to any of the scss files, your main.css file will be automatically updated.
You don't edit main.css directly, compass takes care of that for you. You just edit the .scss files.

## HTML
A bare bones index.html template.

## CSS
* **_config.scss** Put all your variables in here e.g. colors, padding, border radius - this helps with consistency across your project.
* **_forms.scss** Some basic form styles.
* **_grid.scss** A basic responsive grid system with 12 columns.
* **_icons.scss** This is Font Awesome's CSS stylesheet.
* **_ie.scss** Any styles that you need to add in order for Internet Explorer to work.
* **_layout.scss** This is where your main styles go. I typically have header, footer, logo classes here.
* **_links.scss** Styles for any text links and/or buttons.
* **_media.scss** Styles for images, video etc.
* **_mixins.scss** Reusabled SASS mixins e.g. clearfix.
* **_other.scss** Small reusable other styles that don't fit the rest of the framework.
* **_print.scss** Basic print stylesheets to make your pages look better when printed.
* **_reset.scss** This is normalize.
* **_responsive.scss** Add any responsive styles here e.g. hide elements, show elements, resize elements.
* **_retina.scss** Style for retina/high-def displays e.g. large images.
* **_shame.scss** Keep this to hand for any quick and dirty CSS you need to add but plan to tidy later.
* **_tables.scss** Styles for tables.
* **_type.scss** Basic styling for your typography.
* **main.scss** This brings all the partials together. Compass only compiles files that don't have an underscore
* **/assets** Any images that the CSS references e.g. a sprite, goes in here.
* **/assets/fonts** For any fonts you reference in CSS including icon fonts or @font-face.


## JavaScript ##
* I've included some basic Javascript including the latest jQuery and the document ready function.

## Images ##
* There is a /img folder for images.
* For images referenced in the CSS I tend to keep them in the css/assets/ folder e.g. sp.png is a sprite I can reference.
* Images referenced in the HTML are storted in the /img folder.

## Documentation ##
* <a href="http://compass-style.org/">Compass Framework</a>
* <a href="http://sass-lang.com/">SASS</a>
* <a href="http://necolas.github.com/normalize.css/">normalize.css</a>
* <a href="http://fontawesome.io/">Font Awesome</a>
