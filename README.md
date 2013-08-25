TABBY
=====

Tabby is designed to simplify the creation of tab set navigation.  All you do
is tell Tabby what tabs you want and where to find their content.  

Each tab's content is provided by its own url, local or remote.

HOWTO
=====

  * Include the tabby.js javascript file 
  * Include the tabby.css stylesheet 
  * After the initial html loads, call the Tabby() function, passing it: 
    * The id of the element within which you would like the tab set to be created 
    * An object relating tab names to content urls 
    * A set of other non-mandatory options you may wish to specify (such as
      the default tab to display) 

OPTIONS
=======
Keys you can pass into Tabby():

  * tabs

Required. This is an object where the keys are the tab names, and the values are
the urls that provide the corresponding content.

  * defaulttab

This is the pane to open when the tab set is first created. If not present, no
tab will be open by default.

  * doslide

If true, a slide animation will be used to show panes. Default false.

  * hotkeys

If true, allows hotkeys to be used for tab switching ('h' or 'p' for previous
tab, 'l' or 'n' for next tab). Default false.

DEPENDENCIES
============

jQuery
