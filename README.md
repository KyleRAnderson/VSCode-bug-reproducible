# Reproducing the Bug

1. Create a logpoint on line 6 in [one.py](./one.py)
1. Make sure that you currently do not have the debug console in view. I would usually just have the terminal window open.
1. Run the program using the "1" configuration. Note that there should now be the output of
    both the program and the logpoint in the debug console.
1. Switch off of the the debug console again (if you switched to it to look at it), and run the program with launch configuration 2 this time.
1. Switch back to the debug console, make sure that the label of the terminal from which the output
   came is correct.

If you succeeded in reproducing the issue with the above steps, you should have something that looks like this:
![screenshot](./screenshot.png)