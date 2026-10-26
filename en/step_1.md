Make sure you have the following lines of code in your program to set up your connection with the Sense HAT. There is no need to add the code more than once.

```python
from sense_hat import SenseHat
sense = SenseHat()
```

+ Add this code to display a single letter on the LED matrix:

```python
sense.show_letter("Z")
```

If you run this code, the letter "Z" will appear on the screen. You can change which letter is displayed by altering the letter in the quote marks (`""`).

Try it out here:

<iframe src="https://editor.raspberrypi.org/en/embed/viewer/rpi-sensehat-show-letter-example" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

The Code Editor shows the Sense HAT on its side, so the picture is turned a quarter-turn clockwise. If you see a white smiley face, click **Run** again.

[Open this code in the Code Editor](https://editor.raspberrypi.org/en/projects/rpi-sensehat-show-letter-example){:target="_blank"}
