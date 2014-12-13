Homepage
====

![alt tag](screenshots/preview.png "Homepage preview")

**Gokouris live Demos: [Dark](http://gokoururi.github.io/homepage/) - [Light](http://gokoururi.github.io/homepage/index-light.html)**

This repository contains a custom homepage made using html, css and javascript (node.js). Feel free to download and modify. Comments and suggestions appreciated. Please don't expect too much.

Features:
* Plays that catchy jitterbug song
* Random quote picker
* Flashy links
* Flashy Slidy sublinks
* Flashy Slidy searchbars 
* Randomly selected cute 2D girls
* Column style links.
* **New**: Light color theme. See [Live Demo](http://gokoururi.github.io/homepage/index-light.html)

Customizing and adding mascots
===

To hide the jitterbug controls to stop people pausing it change to this

```<audio autoplay>
   <source src="http://www.directlinkupload.com/uploads/138.199.64.75/jitter.mp3" type="audio/mpeg">
   </audio> 
```

===
To customize mascots modify the following values in [javascript](js/scripts.js):

```javascript
    var mascotEnable    = true;
    var mascotPath      = "images/mascots/"
    var mascotList      = [ 'ruri1.png', 'ruri2.png', 'ruri3.png' ];
```

Disclaimer
----
Images of cute girls were made by Anons from /w/ and stolen from their [Google Drive](https://drive.google.com/folderview?id=0B_VmbVyD4eT3N1VUbGN4Wjd5OVE).
