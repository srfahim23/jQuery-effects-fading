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

# jQuery fadeOut() Method
The jQueryOut() method is used to fade out a visible element.

Syntax:

    $(selector).fadeOut(speed,callback);

The optional speed parameter specifies the duration of the effect. It can take the following value: "slow", or milisecond.

The optional callback parameter is a function to be executed after fading competes.

The following example demonstrates the fadeOut() method with different parameters:

Example

    $("button").click(funciton(){
        $("#div1").fadeOut();
        $("#div2").fadeOut("slow");
        $("#div3").fadeOut(3000);
    });

# jQuery fadeToggle() Method
The jQuery fadeToggle() method toggles between the fadeIn() and fadeOut() methods.

If the elements are faded out, fadeToggle() will fade them in.

If the elements are faded in, fadeToggle() will fade them out.

Syntax:

    $(selector).fadeToggle(speed.callaback);

The optional speed parameter specifies the duration of the effect. It can take the following values: "slow", "fast", or milisecond.

The optional callback parameter is a function to be executed after the fading competes. 

The following example demostrates the fadeToggle() method with different parameter:

Example

    $("button").click(function(){
        $("#div1").fadeToggle();
        $("#div2").fadeToggle("slow");
        $("$div3").fadeToggle(3000);
    });

# jQuery fadeTo() Method
The jQuery fadeTo() method allows fading to a given opacity (value between 0 and 1).

Syntax:

    $(selector).fadeTo(speed,opacity,callback);

The required speed parameter specifies the duration of the effect. It can take the following values: "slow", "fast", or miliseconds.

The required opacity parameter in the fadeTo() method specifies fading to a given opacity (value between 0 and 1).

The optional callback parameter is a function to be executed after the function completes.

The following example demonstrates the fadeTo() method with different parameter:

Example

    $("button").click(function(){
        $("#div1").fadeTo("slow", 0.15);
        $("div2").fadeTo("slow", 0.4);
        $("#div3").fadeTo("slow", 0.7);
    });