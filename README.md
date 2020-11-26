# Blinky Blinky

## Introduction @fullscreen
Let's program! This tutorial will guide you through creating
a program for the Circuit Playground Express. The tutorial was
written for parents and children. Once you've finished this
tutorial I hope you feel confident to experiment with your
own programs. To get started click "Next" to the right.

## Step 1
Get a ``||light.showRing()||`` block from ``||light:Light||``
and place it inside of the ``||loops.forever()||`` block. 
```blocks
    forever(function () {
        light.showRing(
            "red red red red red red red red red red"
        )
    })
```

## Step 2
Drag a ``||loops:pause||`` block from ``||loops:Loops||`` and
place it after your ``||light.showRing()||`` block.
```blocks
    forever(function () {
        light.showRing(
            "red red red red red red red red red red"
        )
        pause(100)
    })
```
## Step 3
Change the pause time from 100 ms to 2 seconds (2000 ms).
```blocks
    forever(function () {
        light.showRing(
            "red red red red red red red red red red"
        )
        pause(2000)
    })
```
## Step 4
Get at ``||light.clear()||`` block from ``||light:light||``
and place it after the pause block.

```blocks
    forever(function () {
        light.showRing(
            "red red red red red red red red red red"
        )
        pause(2000)
        light.clear()
    })
```
## Step 5
Drag a ``||loops:pause||`` block from ``||loops:Loops||`` and
place it after your ``||light.clear()||`` block. Next change
the pause time from 100 ms to 2 second (2000 ms).

```blocks
    forever(function () {
        light.showRing(
            "red red red red red red red red red red"
        )
        pause(2000)
        light.clear()
        pause(2000)
    })
```
## Step 6
To the right you should see your lights blinking. This is our
simulator. Use the left most button to stop and start the
simulator. Give it a try.

## Step 7
Running your program in the simulator is a great way to test it.
We can even use the simulator to see which block is running. To do 
this enable Slow-Mo mode by click on the Snail icon below the
Circuit Playground picture. The yellow outline shows you which
block of your programming is active.

## Step 8
Now that we've seen our program working in the simulator let's
download it to the Circuit Playground.

## Step 9
Click the big Download button and remember where your computer
downloaded the file to. Follow the instructions that pop-up to
put the program onto your Circuit Playground Expresss.

## Finish
