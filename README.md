burning-words.js
================

JavaScript function that uses HTML5 canvas element to creates effect of burning text 
with an ability to customize colors, fonts, speed and other parameters.


Usage
-----

1. Download the latest version of the libary from GitHub, unzip and upload the files into a folder on your server, for example `/lib/burning-words`.
2. Copy the code below and paste it into your HTML page.

    ```
    <script type="text/javascript" src="/lib/burning-words/burning-words.min.js"></script>
    ```

    If you have uploaded files into the folder other than `/lib/burning-words`, please modify the code above accordingly.
3. Copy the code below and paste it into your HTML page, where you want to have the text displayed.

    ```
    <script type="text/javascript">
    BurningWords("Hot Deals", {
       "text_color" : "FFFFCC",
       "font" : "Times New Roman",
       "font_size" : 30,
       "bg_color" : "EEEEEE",
       "bg_alpha" : 100,
       "speed" : "normal"
    });
    </script>
    ```


Demo
----
Demo is available at [gyrocode.com/projects/burning-words/](http://www.gyrocode.com/projects/burning-words/).


Copyright
---------

Michael Ryvkin, [gyrocode.com](http://www.gyrocode.com)


License
-------

GNU Lesser General Public License, [gnu.org/licenses/lgpl.html](http://www.gnu.org/licenses/lgpl.html)


