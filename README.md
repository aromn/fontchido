# Fontchido
Fontchido is an alternative to some fonts providers for web design/development.
Fontchido uses a custom font called fontchido.ttf, this let us create our own logotypes as a font.

In order to edit or add your logotype to be a part of the fontchido project, you need fontforge(https://fontforge.github.io/en-US/) to edit the font, the fontchido.sfd file, contains the data of each logo. 
I started this project because I needed some logotypes that fontawesome does not have, or are still on unavailable and because there are some people asking for logotypes they need. Of course, for now this project does not have a lot icons. 

# How to use it:

1. Clone the repo
```console
foo@bar:~$ git clone https://github.com/aromn/fontchido.git
```
2. Call the .css in your html file
```html
	<link rel="stylesheet" href="path/to/fontchido.css"></head>
```

3. Call your icon like the following example:
```html
	<span class="ic-archlinux"></span>
```

**NOTE:** If you have an special need about the style of your logo, you can change the size in the fontchido.css file with 'font-size: ;',
alternatively you can do it like this:
```html
    <span class="ic-archlinux" style="color: ; font-size: ; /* etc...*/"></span>
```
	
checking the style on the .css file to avoid conflicts.

# Example:
[![fontchido-demo.png](https://i.postimg.cc/Y01qrKMP/fontchido-demo.png)](https://postimg.cc/p5LtCS9Q)

# How to contribute:

1. Clone the repo:
```console
    foo@bar:~$ git clone https://github.com/aromn/fontchido.git
```
2. Install fontforge. **NOTE:** THIS IS NOT A TUTORIAL TO LEARN HOW TO INSTALL/USE FONTFORGE.
3. Run fontforge, and then open *fontchido.sfd* file
4. Double click on the free letter space following the initial secuence(A, B, C..Z, a, b, c..z), import your .svg file that contains the logotype you want, or, create your own.
5. Once you have it created, save the .sfd file, and export the fontchido.ttf
6. Open the file fontchido.css, add your logotype according to the style that the fontchido.css has.


If you have a question about this project, or a better idea that can help the project, always is a pleasure to hear/read what you have, contact me aldoromnn@gmail.com or romndesh@gmail.com
