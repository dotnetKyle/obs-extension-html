# OBS Extension for HTML/CSS/Javascript
A Template for a semi transparent OBS Extension that simply shows some text (an `<H1>` element).  Also has an updating timer that ticks.  Modify this template to fit your needs.

## Instructions
 1. Open OBS and choose the `Scene` that you want to add the extension to.
 1. Under `Sources` hit the `[+]` button to add a New Source.
 1. Choose `[Browser]`.
 1. Set the settings as follows:
    * Check the box for `"Local File"`.
    * Navigate to your custom extension HTML file.
    * Set the `Width` and `Height`.
    * Change the `Custom CSS` to match the following:
        `html, body { margin:0; padding:0; background-color: rgba(0, 0, 0, 0);overflow: hidden; }`.
    * If your page needs to be closed (if it is resource intensive) then check the box for `Shutdown source when not visible`.
    * Check the box for Refresh browser when scene becomes active.
    * Note: there is also a button for Refreshing the cache of the current page.  Sometimes this comes in handy when you are not sure if your plugin is reloading when you switch scenes.
 1. Hit the `OK` button to load the extension into your scene.