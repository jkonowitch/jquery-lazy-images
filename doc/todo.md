To-do
=======

* Allow user to specify that certain images should be eager-loaded
* Supply noscript version so that JS-less browsers can still see images
* Allow custom placeholder
* Expose various options in jquery.lazyload.js (or just tell user to require lazyload instead of lazyload-rails)
* Test multiple images on a page
* Test whether other image helpers are using image_tag under the hood.
* Add support for Rails 3.0 and below (by adding generator that copies assets into project)
* Switch to capybara-webkit for testing
* Add some documentation about how image_tag gets monkeypatched
* Check to see if images in emails are broken