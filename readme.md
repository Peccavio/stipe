#Stipe Compass Extension
Stipe is the life blood of the Toadstool style guide framework. Consisting of a series of mixins, extends and defaults that give Toadstool that 'instant on' experience. 

[Stipe](https://rubygems.org/gems/stipe)

##To install
`gem install stipe`

##To use 
To use the Stipe gem, using Bundler `gem 'stipe'`

Stipe is a Compass Extension, so Compass is set as a depdency. You will need to include `require 'stipe'` in your config.rb file.

# Stipe Changelog
###0.0.5.6
* Over-hauled color palette CSS
* Updated forms extends to include `stipe_` in the name to increase visibility of where code is coming from in Toadstool
* Added UI for `contenteditable` new functionality 
* Deprecated support for other button libraries
	* Code is still there, just need to decide on 100% supporting them or not, this 1/2 way crap isn't awesome
* New button mixins for generating a single button gradient based off Ultimate CSS Gradient Generator 
* Updates to `/stipe/stylesheets/stipe/toadstool/ui_patterns/_color_grid.scss`
	* Added new `extend_color_loop` mixin
	* Dynamically looping through list of OOCSS names to create color block classes
*  New `extend_color_loop` mixin 
	* Added to `/stipe/stylesheets/stipe/toadstool/ui_patterns/_color_grid.scss`
	* All extends generated in memory from lists of objects

###0.0.5.5
* Fixed order of `@imports` in `_manifest.scss`

###0.0.5.4
* Removed Google Font from Toadstool

###0.0.5.3
* Added new feature for hidpi image management

###0.0.5.2
* UI adjustments to `color_palettes` view

###0.0.5.1
* Adding new configutation support for form UI

###0.0.5.0
* Updated stipe manifest to allow for single import
