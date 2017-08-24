+ Make sure you have these lines of code in your program to set up your connection with the Sense HAT. If you already have these, there is no need to add the code more than once.

```python
from sense_hat import SenseHat
sense = SenseHat()
```

+ Add this code to display a single letter on the LED matrix

```python
sense.show_letter("Z")
```

The letter "Z" will appear on the screen. You can change which letter is displayed by altering the letter in quotes (`""`).

You can try it out here:

<iframe src="https://trinket.io/embed/python/e273580768" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
