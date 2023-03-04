# jQuery-Effects---Fading
With jQuery you can fade elements in and out of visiblity.

# Example
jQuery fadeIn()
Demonstrate the jQuery fadeIn() method.

jQuery fadeout()
Demonstrates the jQuery fadeout() method.

jQuery fadeToggle()
Demonstrates the jQuery fadeToggle() method.

jQuery fadeTo()
Demonstrates the jQuery fadeTo() method

# jQuery Fading Methods
With jQuery you can fade an element in and out of visiblity.

jQuery has the following fade methods:

.fadeIn()
.fadeOut()
.fadeToggle()
.fadeTo()

# jQuery fadeIn() Method
The jQuery fadeIn() method is used to fade in a hidden element.

Syntax:

    $(selector).fade(speed,callback);

The optional speed parameter specifies the duration of the effect. It can take the
following values: "slow", "fast", or miliseconds.

The optional callback parameter is a funciton to be executed after the fading
competes.

The following example demonstrates the fadeIn() method with different
parameters:

Example

    <!DOCTYPE html>
    <html>
    <head>
    <script
    src="https://ajax.googleapis.com
    /ajax/libs/jquery/3.6.3
    /jquery.min.js"></script>
    $(document).ready(function(){
        $("button").click(funciton(){
            $("#div1").fadeIn();
            $("#div2").fadeIn("slow");
            $("#div3").fadeIn(3000);
        });
    });
    </script>
    </head>
    <body>

    <p>Demonstrate fadeIn() with different parameters.</p>

    <button>Click to fade in boxes</button>br<br>

    <div id="div1" style="width:80px;height:80px;display:none;background-color:red;"></div><br>
    div id="div2" style="width:80px;height:80px;display:none;background-color:green;"></div><br>
    <div id="div3" style="width:80px;height:80px;display:none;background-color:blue;"></div>

    </body>
    </html>
    # jQuery-Effects---Fading
# jQuery-effects-fading
# jQuery-effects-fading