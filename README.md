Autocomplete Deluxe
===================

The Autocomplete Deluxe module is an enhanced autocomplete element that uses the
JQuery UI autocomplete. It will also implement a widget for taxonomy. This
module does not require any 3rd party jQuery libraries.

This is a Backdrop port of the Drupal 7 Autocomplete Deluxe module
https://www.drupal.org/project/autocomplete_deluxe


Requirements
------------

This module requires no modules outside of Backdrop core.


Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.


Configuration
-------------

To set up a field named Tags which uses an Autocomplete Deluxe widget to set
values for that field from the Tags taxonomy, do the following:

 * Navigate to Administration > Modules and enable the Autocomplete Deluxe
   module.
 * Navigate to Administration  > Structure > Content types and select manage
   fields of the content type you wish to edit.
 * Add a new field of "Term reference" named "Tags". Select the Widget Type
   "Autocomplete Deluxe" in the drop down menu. Save.
 * Select the Tags vocabulary.  Save field settings.
 * Customize or keep the default Autocomplete Deluxe settings for the field.
   Save settings.

Now when new content is added the Tags widget allows editors to enter
existing tags as well as create new ones.

Issues <!-- This section is required. -->
------

Bugs and feature requests should be reported in [the Issue Queue](https://github.com/backdrop-contrib/autocomplete_deluxe/issues).


Current Maintainers
-------------------

- [Juan Olalla](https://github.com/juanolalla).


Credits
-------

- Ported to Backdrop CMS by [Juan Olalla](https://github.com/juanolalla).
- Originally written for Drupal by [Edward Chan (edwardchiapet)](https://www.drupal.org/u/edwardchiapet)
 and [LNakamura](https://www.drupal.org/u/lnakamura).
- Inital development sponsored by [Mediacurrent](http://www.mediacurrent.com/)

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
