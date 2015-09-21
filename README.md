octave_eu
=========

Translation octave GUI: basque language
This traslation applies to Octave 4.1.0+, the version that ships Ubuntu 14.04.
We hope to update to development version if/when it becomes easier to install.

INSTALL

1) Generate the translation binary file:

lrelease eu_ES.ts

2) Move the binary file to the right location:

sudo mv eu_ES.qm /usr/share/octave/4.1.0+/locale

(Restart Octave GUI and make sure eu_ES is selected
in the general configuration of Octave GUI)
