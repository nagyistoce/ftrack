fTrack is a framework for rapid application development(RAD) in Objective-C.
It contanes:
<ul>
<b>Classes</b>
<li>SQLite - use out SQLite class for easier SQLite database management</li>
<li>Web service - classes to use for url requests and responses and a webservice class which should be used with your own APIs</li>
<li>Invocations - a class that wraps a common selector and target structure. It is used in our own buttons, lists, etc.</li>
<li>Assets manager - for easier management of photo assets</li>
<li>Date - contains various common methods for working with dates</li>
<li>Image cache - a class which is recommended when using images. Whenever you have a path or url to an image you should use this class</li>
<li>P2P - class which makes it easier to do peer to peer connections</li>
<li>ftrack also includes some commonly used classes like JSON, HttpEncoder and Facebook</li>
</ul>

<ul>
<b>Predesigned Forms</b>
<li>Payment - support Cash, Paypal, VISA, MasterCard, etc.</li>
<li>Shopping cart - create list of items from a menu, which can be divided into categories and subcategories with items</li>
<li>Gallery - grid and list view followed by fullscreen photo view with thumbnail preview of the other pics in the gallery</li>
<li>Calendar - put as many events as you want to each day</li>
</ul>

<ul>
<b>Controls</b>
<li>Repeater - similar to table view but allows you additionaly to put more than one item on a row, to set spaces between the items and many more. Can be used to create grid controls.</li>
<li>Checkbox - control imitating a desktop os checkbox</li>
<li>Checkbox list - list of checkboxes giving the possibility to select a single or multiple options</li>
<li>Scrollable label - label that occupies an exact rectangle with the option to scroll it if the text exeeds its bounds</li>
<li>Tab panel - container control for switching tabs on a single panel</li>
<li>Accordion - similar to tab panel, but in this case the selected tab expands pushing the other tabs around it</li>
<li>Audio control - simple audio contol (to be developed further)</li>
<li>Date selector - a button which invokes a date spinner</li>
<li>Stack panel - a stacked container control</li>
<li>Stack scroll panel - a convenient scroll panel containing only stack panel inside</li>
<li>All other controls are wrappers of the standard iOS controls which gives you the opportunity to customize them easily</li>
</ul>

fTrack also includes wrappers of most of the standard iOS view and view controllers including the FTApplication class, which gives you the opportunity to customize them easily.