# Counter
## Basic
### Description
The goal is to have a number on the screen. Using buttons you can then increase or decrease the number and see the changes live on screen.

### Tasks
1. Have a number, a button named "grow" and a button named "shrink" on the screen.
2. If you click on the button "grow" the counter increases by 1 and if you click on the button "shrink" the counter decreases by 1. Automatically update the counter on screen.
3. Add two more buttons to grow or shrink by 10 at once.
4. Only change the counter value if the new value will not be above 100 or below 0.
* Make sure the functionality is properly implemented and does not have any bugs.
* Feel free to add additional functionality, improve the features you just made or make the style and feel of the features nicer.

## Advanced
*This part is based on the basic part above.*

### Description
I assume you have declared your counter value globally. This would mean you can simply access it from everywhere.

Try it! Open up your website and press F12. I would recommend using Google Chrome because it makes developing JavaScript much easier.

After pressing F12 a window should open to the side of your browser. Switch to the console tab and type in the name of your counter variable. If you get back the current value then you declared your counter globally. You can even change the variable using normal JavaScript syntax. This might not be what you want in some cases.

Try rewriting your code so that you can not directly access and especially not change your counter variable from the Chrome console. Do this without changing any functionality of your website.

### Tasks
1. Declare the counter so that it is not global.

### Hint
~~One clean way to do this is using what is called a closure. Look it up!~~

## Extra
### Description
Try adding some visiualization of the counter.

In the solution a bar that has a width of x percent has been added. This might be a good idea but maybe you can come up with a different, more creative visualization. 

Maybe it even involves numbers that do not necessarily need to be on a range from 0 to 100.

Be creative!

### Tasks
1. Add a bar with a width of x percent. (x being the value of the counter)
2. Make sure it updates automatically.
* Try coming up with more creative visualizations.
* Style it nicely and maybe even add some transitions to make it smoother.
