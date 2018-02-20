Browser default font-size is 16px. Once you set a font-size in pixels people with bad eye sight can no longer user browser settings to increase text size.

However you can work around this by using a percentage in the root font size.
The percentage is calculated off of the default 16px.
   So for example: font-size: 100% = font-size: 16px;

To set font-size to 16px while using percentages use:

html {
   font-size: 62.5%;
}

This allows 1rem to be 10px
This makes measurements in rems much easier than having to make calculations using 16px

An easy technique to follow for responsive design is to use the rem unit. It calculates size in relation to the the root element's font-size.

!!!!!!
Rem is not supported below IE 9 :(