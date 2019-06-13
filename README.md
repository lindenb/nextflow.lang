gtksourceview / gedit / nano support for **nextflow** files ( https://www.nextflow.io ).

## Installation

### gtksourceview / gedit 

Move the `*.lang` file in the preinstalled language directory located in `${PREFIX}/share/gtksourceview-4/language-specs/` (for example, prefix can be `/usr/` ).

**Or** move it into  `~/.local/share/gtksourceview-4/language-specs/`.

**Note**: replace 4 with 2.0 or 3.0 in the path for GtkSourceView version 2 or version 3. 


### nano

copy `nextflow.nanorc` in `~/.nano/nextflow.nanorc`

in `~/.nanorc` add the following line : `include ~/.nano/nextflow.nanorc`

## History

  * 2190613 added nanorc
  * 2190606 added some keywords
  * 2190605 creation

## Pointers

  * https://developer.gnome.org/gtksourceview/stable/lang-reference.html
  * https://developer.gnome.org/gtksourceview/4.2/lang-tutorial.html
  
## Author

Pierre Lindenbaum PhD

