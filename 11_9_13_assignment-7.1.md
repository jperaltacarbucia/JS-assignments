1. function JSGameSoup(canvas, framerate) {
        /** The number of frames that the app has been running for */
        
        this.frameCount = 0;
        /** How fast we are running in FPS */
        
        this.framerate = framerate;
        /** The current/last position of the pointer */
        
        this.pointerPosition = [0, 0];
        /** The current/last pointer up/down status */
        
        this.pointerDown = false;
        // where we will output the graphics
        
        if (typeof canvas == "string") {
        // the caller has supplied the ID of a canvas
        
        canvas = document.getElementById(canvas);
        }

    //Name: JSGameSoup, Arguments: canvas and framerate

2.  function myFunction(a,b) {
        return a*b;
    }
    document.getElementById("demo").innerHTML=myFunction(4,3);

    //Name: myFunction, Arguments: a and b, Return: 12
    
3. function shortFunction(x,y) {
    var x=5;
    var y=5;
    return x+y;
}

    //Name: shortFunction, Arguments: x and y, Return: 10