# Text to ASCII ART
This script converts your text to ASCII art
```
####################################
   ██    █  █     █   █        █
  █  █      █     █   █        █
 █       █ ███    █   █  █  █  ███
 █  ███  █  █     █████  █  █  █  █
 █    █  █  █     █   █  █  █  █  █
  █  █   █  █     █   █  █  █  █  █
   ██    █  ██    █   █   ███  ███
####################################
```

## Installation
  * Install pip, if you haven't install it yet. ([Click](https://pip.pypa.io/en/stable/installing/))
  * Instal Dependencies (`pip install -r requirements.txt` or `pip install Pillow`)
  * All done

## Using
  Parameters:
  * -text TEXT            Your text (Required)
  * -char CHAR            Your char for ASCII (Optional, default char — █)
  * -space-char SPACE_CHAR Your space char (Optional, default space char — space¯)
  * -gap-char GAP_CHAR    Your char between letters (Optional, default space char — empty)
  * -font FONT            Your Font (Optional, default font — Arial)
  * -align ALIGN          Text Align(center, left, right) (Optional, default align — left)
  * -spacing SPACING      Text Spacing (Optional, default spacing — 0)
  * -size SIZE            Font Size (Optional, default size — 10)
  * -signature SIGNATURE  Your Signature. \n — for new line (Optional, default signature — mine)
  * --left                If argument is defined, script writes you signature left side
  * --hr                  If argument is defined, script writes hr
    * -hr-char HR_CHAR      Your HR char (Optional, default char - '_')
  * --save-image          Save text image to PNG (to file named 'out.png')

## Examples
```
python text_to_ascii.py -text "Git Hub" -signature "" --hr -hr-char "#"

####################################
   ██    █  █     █   █        █
  █  █      █     █   █        █
 █       █ ███    █   █  █  █  ███
 █  ███  █  █     █████  █  █  █  █
 █    █  █  █     █   █  █  █  █  █
  █  █   █  █     █   █  █  █  █  █
   ██    █  ██    █   █   ███  ███
####################################
```
```
python text_to_ascii.py -text "♥" -char "♥" -signature "" --hr -gap-char "  " -font "Arial Unicode.ttf" -size 20 #You may not have this font
____________________________________________
      ♥  ♥  ♥  ♥           ♥  ♥  ♥  ♥
   ♥  ♥  ♥  ♥  ♥  ♥     ♥  ♥  ♥  ♥  ♥  ♥
   ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥
   ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥
   ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥
      ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥
      ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥
         ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥  ♥
            ♥  ♥  ♥  ♥  ♥  ♥  ♥
               ♥  ♥  ♥  ♥  ♥
               ♥  ♥  ♥  ♥  ♥
                  ♥  ♥  ♥
                     ♥
                     ♥
____________________________________________
  ```
