[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=22480792)
# 8-5-JS-Function-Parameters

## Video

[Video](https://youtu.be/ptyuZL6I56c) <-- Make sure to watch this video first

## Directions

### Step #1 - Draw a mole! <br>

Our grass is filled with holes, but has no moles. Thankfully, we've already defined a mole drawing function, drawMole, so that all you have to do to get a mole to show up is call that function.
<br><br>
Try it out ! Call the `drawMole` function in `setup` to make a mole show up.
<br><br>

### Step #2 - Parameter-ize the mole <br>

Right now, our `drawMole` function will draw a mole in the same place every time we call it. We want to be able to tell the `drawMole` function where to draw the mole, so that, each time we call the `drawMole` function the mole can be drawn in a different place.
<br>

Add two parameters to the drawMole function, to tell it where to draw the mole:

- one for the x position
- the other for the y position

> `var drawMole = function(moleX, moleY){....`
> <br>

After you have modified the `drawMole` function, test it out:

- On the previous step, you called `drawMole()` without any arguments. Now, pass two arguments into that call, so that it draws the mole in the middle of the center hole.

> `drawMole(200, 200)`
> <br><br>

### Step #3 - MORE moles! <br>

Now that you made that change, it's easy to add more moles. Call the function three more times, and pass values in that make the moles show up in the holes.
<br><br>

### Step #4 - Radomize! <br>

Add randomness to your code using random() to set the color of each mole.

> `fill(random(0,255), random(0,255), random(0,255));`
