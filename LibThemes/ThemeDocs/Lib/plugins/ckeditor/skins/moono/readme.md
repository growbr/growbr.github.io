<h1 id="%22moono%22-skin">"Moono" Skin</h1>

<p>This skin has been chosen for the <strong>default skin</strong> of CKEditor 4.x, elected from the CKEditor
<a href="http://ckeditor.com/blog/new_ckeditor_4_skin">skin contest</a> and further shaped by
the CKEditor team. "Moono" is maintained by the core developers.</p>

<p>For more information about skins, please check the <a href="http://docs.cksource.com/CKEditor_4.x/Skin_SDK">CKEditor Skin SDK</a>
documentation.</p>

<h2 id="features">Features</h2>

<p>"Moono" is a monochromatic skin, which offers a modern look coupled with gradients and transparency.
It comes with the following features:</p>

<ul>
<li>Chameleon feature with brightness,</li>
<li>high-contrast compatibility,</li>
<li>graphics source provided in SVG.</li>
</ul>

<h2 id="directory-structure">Directory Structure</h2>

<p>CSS parts:
- <strong>editor.css</strong>: the main CSS file. It's simply loading several other files, for easier maintenance,
- <strong>mainui.css</strong>: the file contains styles of entire editor outline structures,
- <strong>toolbar.css</strong>: the file contains styles of the editor toolbar space (top),
- <strong>richcombo.css</strong>: the file contains styles of the rich combo ui elements on toolbar,
- <strong>panel.css</strong>: the file contains styles of the rich combo drop-down, it's not loaded
until the first panel open up,
- <strong>elementspath.css</strong>: the file contains styles of the editor elements path bar (bottom),
- <strong>menu.css</strong>: the file contains styles of all editor menus including context menu and button drop-down,
it's not loaded until the first menu open up,
- <strong>dialog.css</strong>: the CSS files for the dialog UI, it's not loaded until the first dialog open,
- <strong>reset.css</strong>: the file defines the basis of style resets among all editor UI spaces,
- <strong>preset.css</strong>: the file defines the default styles of some UI elements reflecting the skin preference,
- <strong>editor_XYZ.css</strong> and <strong>dialog_XYZ.css</strong>: browser specific CSS hacks.</p>

<p>Other parts:
- <strong>skin.js</strong>: the only JavaScript part of the skin that registers the skin, its browser specific files and its icons and defines the Chameleon feature,
- <strong>icons/</strong>: contains all skin defined icons,
- <strong>images/</strong>: contains a fill general used images,
- <strong>dev/</strong>: contains SVG source of the skin icons.</p>

<h2 id="license">License</h2>

<p>Copyright (c) 2003-2013, CKSource - Frederico Knabben. All rights reserved.</p>

<p>Licensed under the terms of any of the following licenses at your choice: <a href="http://www.gnu.org/licenses/gpl.html">GPL</a>, <a href="http://www.gnu.org/licenses/lgpl.html">LGPL</a> and <a href="http://www.mozilla.org/MPL/MPL-1.1.html">MPL</a>.</p>

<p>See LICENSE.md for more information.</p>
